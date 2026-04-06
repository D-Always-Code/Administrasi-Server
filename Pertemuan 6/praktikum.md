# Membuat elastic ip

1. nyalakan instance EC2 yang sudah di create sebelumnya
2. ke menu networl adan security pilih menu ELASTIC IP
    - klik menu allocate elastic ip
    - pilih amazon's pool of ipv4 addres
    - network border grup (south east asia)
    - isi tags(key-server-6B VALUE = praktikum elastic ip)
    - klik allocate
3. assosiacate kan elastic ip segera mungkin (>1 jam akan kena cost)
    - centang mana eip yang dipilih
    - pilih action -> assosicate elastic ip
    - resource type pilih instance
    - pilih instance
    - klik assosiacate
    ![alt text](image.png)