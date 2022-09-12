# Praktikum Jaringan Komputer

### Mengamati Jaringan Rumah

Mengetahui alamat IP pada jaringan rumah dengan menggunakan command ipconfig pada command prompt.

![Gambar 1](../assets/minggu-2/1.png)

Pada gambar di atas didapatkan IP nya yaitu 192.168.0.1. Selanjutny kita lakukan ping pada alamat IP tersebut dengan menggunakan command ping (alamat ip).

![Gambar 2](../assets/minggu-2/2.png)

Selanjutnya kita lihat hasil ping tersebut pada software wireshark.

![Gambar 3](../assets/minggu-2/3.png)

Setelah itu kita amati apa arti warna dari tiap baris dengan menggunakan tabel berikut 

![Gambar 4](../assets/minggu-2/4.png)

Berdasarkan tabel tersebut pada jaringan rumah, rata-rata bertipe ARP dan ICMP. Selanjutnya kita akan mencoba melihat isi dari ping yang kita lakukan tadi. Kita akan mengidentifikasi header ip dengan menggunakan tabel berikut

![Gambar 5](../assets/minggu-2/5.png)

Hasil dari capture adalah sebagai berikut

![Gambar 6](../assets/minggu-2/6.png)

Identifikasi:
Version = 4
IHL = 20 bytes
TOS = 0x00 (DSCP: CS0, ECN: Not – ECT)
Total Length = 60
Identification =  0x4bb9 (19385)
Flags = 0x00
Fragment Offset = 0
TTL = 128
Protocol = ICMP
Header Checksum = 0x6d47
Source Address = 192.168.0.1
Destination Address = 192.168.0.1
Selanjutnya kita akan mengidentifikasi ICMP dengan menggunakan tebal berikut 

![Gambar 7](../assets/minggu-2/7.png)

Type = 8 (Echo (ping) request)
Code = 0
ICMP Checksum = 0x4d55
Identifier = (BE) = 1 (0x0001), (LE) = 256 (0x0100)
Sequence Number = (BE) = 6 (0x0006), (LE) = 1536 ()x0600)
