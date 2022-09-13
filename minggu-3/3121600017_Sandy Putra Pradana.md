# Praktikum Komputer Jaringan

### Mengamati Proses Ping

#### 1. PC 0 Ke PC 1

![Gambar 1](../assets/minggu-3/pkjpak1.PNG)

Gambar di atas adalah isi arp sebelum dilakukan broadcast.

![Gambar 2](../assets/minggu-3/pkjpak3.PNG)

Setelah itu kita lakukan ping dari pc 0 ke pc 1. 

![Gambar 3](../assets/minggu-3/pkjpak2.PNG)

Terjadi broadcast ke seluruh pc yang ada.

#### 2. PC 0 Ke PC 1 Setelah Broadcast

![Gambar 4](../assets/minggu-3/pkjpak4.PNG)

Gambar di atas adalah isi arp setelah dilakukan broadcast. Dapat dilihat pc 0 menyimpan alamat tujuan ping sebelumnya yaitu alamat pc 1.

![Gambar 5](../assets/minggu-3/pkjpak6.PNG)

Setelah itu kita lakukan ping pc 0 ke pc 1.

![Gambar 6](../assets/minggu-3/pkjpak5.PNG)

Dan yang terjadi adalah adanya broadcast lagi ke semua pc yang ada.

#### 3. PC 1 Ke PC 0

![Gambar 7](../assets/minggu-3/pkjpak7.PNG)

Isi arp pada pc 1 menyimpan alamat ip pc 0.

![Gambar 8](../assets/minggu-3/pkjpak8.PNG)

Kita lakukan ping, dan yang terjadi adalah masih melakukan broadcast ke semua pc.
