# Remote Instance with SSH Putty

1. Pastikan sudah Install Putty

![alt text](1_RSSH.png)

2. Konversi File public key dari .pem ke .ppk di putty
    - buka puttygen di windows
    - cari file .pem yang didownload buka all file dulu agar ketemu
    - load file key.pem lalu ubah menjadi .ppk 
    - save file ke.ppk

![alt text](2_RSSH.png)
![alt text](2,1_RSSH.png)
![alt text](2,2_RSSH.png)

3. Set up putty untuk remote SSH
- buka apps putty 
- Isi iP public sesuai instance
- isi port untuk SSH sesuai security Group di instance
- isi nama session agar saat connect lagi tinggal load saja
- load file .ppk  (klik SSH -> Klik Auth -> klik Credential -> Load data )
- kembali ke sessions klik save
![alt text](3_RSSH.png)
- klik open
- masukan username sesuai instance
![alt text](4_RSSH.png)


4. sudo apt-get update (update os) lanjut "sudo apt-get upgrade"

![alt text](5_RSSH.png)

5. pembuktian remote SSH secara Visual
- copy public IP instance paste ke browser
![alt text](6_RSSH.png)
- Install web server seperti apache/Nginx 
- sudo apt install apache2
- reload web browser
![alt text](7_RSSH.png)

6. matikan Instance agar tidak kena tagihan 
 - sudo shutdown 
![alt text](8_RSSH.png)
 ![alt text](9_RSSH.png)
