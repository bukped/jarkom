# Protokol


di layer aplikasi

## HTTP

<img width="474" height="355" alt="image" src="https://github.com/user-attachments/assets/128f6bec-b5d0-42c4-ba22-790da94bb446" />

Contoh protokol http
dia melayani di port 80, apabila akses browser:
![alt text]({2E3BA413-F68D-4F37-BB3C-9814516AD0B3}.png)

Protokol https melayani di port 443

![alt text]({55271989-5BC6-47A1-9F3C-030946EE1D4C}.png)

Semua browser itu methode GET ketika membuka pertama kali

Ketika mengirim data menggunakan HTTP Post

![alt text]({29DD4C70-0AD8-4002-8DDD-959B2BBF019F}.png)

sama halnya dengan PUT, PATCH, Delete itu biasanya menggunakan form.

Bedanya :
1. PUT : Update data keseluruhan
2. PATCH : Update data sebagian
3. DELETE : Menghapus satu data/keseluruhan

## SMTP / IMAP

Untuk pengiriman e-mail

## SSH / SFTP

Remote CLI dari UNIX Based Operating Sistem

## OpenVPN / PPTP

Untuk membuat jaringan Privat(Jaringan di dalam jaringan)

## FTP

Untuk penyimpanan file


Untuk Layer Transport

## TCP

Dia sifatnya state oriented, alias tidak ada boleh paket yang di drop/ilang

File transfer, biar file tidak korup ketika di kirim via Internet

## UDP

Dia sifatnya stateless, boleh ada paket yang ilang

Contoh : nonton youtube
