# Membuat EC2 / Instance / VM

1. Pilih Menu All services kemudian pilih EC2

![alt text](1_EC2.png)

2. didalam EC2 kita pilih instance

![alt text](2_EC2.png)

3. dalam menu instance pilih menu launch instance

![alt text](3_EC2.png)

4. Beri nama instance dengan Format NIM_server

![alt text](4_EC2.png)

5. Pilih OS server untuk Instance kita

![alt text](5_EC2.png)

6. Pilih resource instance T3.Micro (2VCPU, 1GB Memory)

![alt text](6_EC2.png)

7. Membuat Key Pair, pilih create new key pair, isi nama key, pilih RSA, format file .pem, create key pair

![alt text](7_EC2.png)

8. Setting kebijakan kemananan / security group
    -Allow SSH -> Artinya membolehkan remote dai luar
    -Allow HHTPS -> Artinya instance bisa di akses dari protokol HTTPS
    -Allow HHTP -> Artinya instance bisa di akses dari protokol HTTP

![alt text](8_EC2.png)

9. Setelah selesai set up pilih launc instance

![alt text](9_EC2.png)

10. Pastikan Launch Instance Sukses

![alt text](10_EC2.png)