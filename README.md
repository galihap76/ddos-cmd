# ddos-cmd
(SEBAGAI PEMBELAJARAN BUKAN UNTUK DI GUNAKAN TANPA IZIN OLEH PIHAK)

Hai yang baca, biar saya jelaskan DDOS itu DDOS (DISTRIBUTED DENIAL OF SERVICE) merupakan teknik yang melakukan banyak request terhadap server web dan membuat lalu lintas
jaringan yang sangat padat.
pelaku yang melakukan ini akan menggunakan koneksi internet pelaku dan alat DDOS yang tersedia di internet yang gratis di unduh ataupun melalui dark web jika pelaku telah
melakukan ini server web
tidak akan merespon dalam permintaan yang sah dan website akan lumpuh sama sekali tidak bisa di akses. penyerangan DDOS ini tergantung pada server atau firewall
seberapa kuat dalam menampung penyerangan DDOS. 

KATEGORI DALAM PENYERANGAN DDOS :
1.VOLUMETRIK DDOS dalam kategori penyerangan ini menggunakan protokol UDP (User Datagram Protocol) 
2.PROTOCOL ATTACK dalam kategori penyerangan ini menggunakan protokol TCP/IP yang menggunakan juga paket protokol ICMP tersedia dalam bentuk PING (Packet Internet Gopher)
3.LAYER APPLICATION dalam kategori penyerangan ini menggunakan protokol HTTP

ketiga kategori tersebut sama sama untuk melumpuhkan website dan yang saya jelaskan tadi penyerangan DDOS itu tergantung pada server dan firewall.

dalam hal ini saya akan bagikan penyerangan DDOS kategori PROTOCOL ATTACK perintah PING dalam menggunakan DDOS :
ping 8.8.8.8 -t -l 65500

MAKSUD PERINTAH:
-ping melakukan ping terhadap host server
-8.8.8.8 ip address host server (ip address tersebut hanya contoh saja)
-t melakukan permintaan terus menerus 
-l seberapa banyak bentuk data yang di buat
-65500 jumlah data yang di buat dan kapasitas yang di buat

ping ini tertanam pada windows (CMD) ataupun linux juga ada sih dalam hal ini biasanya orang orang menggunakan ping untuk mengecek apakah koneksi internet kita terhadap host
server aktif jika aktif host akan merespon permintaan kita dalam mengembalikan paket icmp berupa request reply dan beberapa waktu yang di terima jika tidak, akan mengeluarkan
paket icmp yaitu request timed out. konsep ini bisa di sebut 3 WAY HANDSHAKE dalam mengembalikan sinyal SYN & SYN ACK.
dalam hal ini PING bisa di salah gunakan dalam membentuk paket yang sangat besar, kebanyakan kalo kita ping akan muncul bytes 32 dalam hal ini bytes tersebut bisa di modifikasi
dengan membentuk hal yang tidak wajar jika hal ini di lakukan terhadap host, host akan merespon juga dalam paket yang terpecah dalam bentuk yang tidak wajar seperti perintah
PING di atas. ketika pelaku melakukan ini server yang tersedia akan mengalami buffer overflow (kelebihan ram atau permintaan) penyerangan ini bisa di sebut PING OF DEATH.

DDOS dalam cmd yang menggunakan PING ini bukanlah CMATRIX atau apalah jika sudah paham konsep sebuah DDOS itu dan juga sudah saya jelaskan saya tadi di atas.
zaman sekarang juga keamanan itu sudah canggih seperti firewall bahkan software database management system.

-MELAKUKAN UJI COBA PADA DDOS / DOS KUNJUNGI WEBSITE KHUSUS RESMI MELAKUKAN HAL INI > dstat.cc 
-PERINTAH BEKERJA 
-DDOS KATEGORI PROTOCOL ATTACK

PERINTAH LAIN JUGA SUDAH TERSEDIA DI FILE SEBELAH SEBAGAI PEMBELAJARAN SAJA BUKAN UNTUK DI SALAH GUNAKAN.
