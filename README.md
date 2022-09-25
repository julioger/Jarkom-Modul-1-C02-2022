# Jarkom-Modul-1-C02-2022

![image](https://user-images.githubusercontent.com/100665785/191976982-ed21a6f0-fb03-424a-89ce-4874f7d75f73.png)

Soal

![image](https://user-images.githubusercontent.com/100665785/191977249-e17bb0cb-21f9-4a54-b4e8-0a3a24730051.png)
![image](https://user-images.githubusercontent.com/100665785/191977301-0444f67c-6591-42cf-86ea-b01558cf5815.png)

1. http.host contains “monta.if.its.ac.id”, klik kanan lalu pilih follow tcp stream lalu lihat server yaitu nginx ver 1.10.3

![image](https://user-images.githubusercontent.com/100665785/191973239-8ae985cb-6532-4d91-a191-2a6dd584d17b.png)

![image](https://user-images.githubusercontent.com/100665785/191976527-4dba80d4-5621-41b1-8cd4-516f7761d976.png)

![image](https://user-images.githubusercontent.com/100665785/191976569-f735789d-001a-4f9e-8c5f-b6f78c6fb178.png)

2. http contains “topik” lalu export object → HTTP  → pilih 194 lalu save (kenapa 194 karena “detail topik” sesuai dengan yang diminta soal) → kalau sudah disave maka ganti extension dengan .html lalu akan kebuka link dibawah

![image](https://user-images.githubusercontent.com/100665785/191977544-077cdfde-f404-488c-aae1-4e6230c97313.png)

![image](https://user-images.githubusercontent.com/100665785/191977593-0cf119a9-78ee-4630-a4c8-b276fd2afea2.png)

![image](https://user-images.githubusercontent.com/100665785/191977629-dd58c0dc-b261-4556-9d07-31c3c277be96.png)

![image](https://user-images.githubusercontent.com/100665785/191977695-66568ed1-065a-4589-b7a9-efddb2d33c44.png)

cara ke 2 untuk no 2 sama yaitu masukkan filter berikut http contains “topik” lalu pilih paket yang ada detail topik sesuai dengan yang diminta soal, klik kanan lalu pilih
follow lalu HTTP stream lalu find 194 karena pada paket detail topik ada angka 194 lalu lihat pada bagian judul topiknya

![image](https://user-images.githubusercontent.com/100665785/191978402-9461e2ee-a4ce-44c8-9774-d00d1fd50a2a.png)

3. tcp.dstport == 80 karena menuju / tcp dst port 80 kalau capture

![image](https://user-images.githubusercontent.com/100665785/191979231-c23e906b-a632-4f7f-ad29-4461d919decc.png)

4. tcp.srcport == 21 karena berasal / tcp src port 21 kalau capture

![image](https://user-images.githubusercontent.com/100665785/191978709-8e78c8f6-528b-45c0-8427-fe64a3458796.png)

5. tcp.srcport == 443 karena berasal / tcp src port 443 kalau capture

![image](https://user-images.githubusercontent.com/100665785/191978848-eba2c9bf-6065-4212-8f55-500fa2005e48.png)

no 3-5 untuk protokol bisa dispesifikasi , mungkin jika menggunakan udp bisa udp.dstport/srcport dan sebagainya jika menggunakan protokol lain

6. ping lewat command prompt untuk mendapatkan ip dari lipi.go.id

![image](https://user-images.githubusercontent.com/100665785/191979037-2f41fb5b-7180-4b9e-baf6-5ae8b7e69bca.png)

karena menuju maka pakai dst

ip.dst == 203.160.128.158

![image](https://user-images.githubusercontent.com/100665785/191979337-80570ff1-4914-4969-8a33-efb50527669c.png)

7. pertama ipconfig dulu di terminal lalu pilih bagian wireless LAN adapter WI-FI dan pilih bagian ipv4 yaitu 192.168.100.108 karena merupakan ip saya

![image](https://user-images.githubusercontent.com/100665785/191979443-e4ff1df2-7d3f-4a00-afa3-14509d912f0e.png)

lalu ip.src == 192.168.100.108 dimana ipnya sesuai dengan ip address kita masing”

![image](https://user-images.githubusercontent.com/100665785/191979556-51c568cd-c9be-4a67-a39c-e9e953a8571c.png)

8. menggunakan follow tcp stream di wireshark di dapatkan percakapan sebagai berikut

![gambar nomor 8](https://media.discordapp.net/attachments/221887784108032001/1023184353406238720/unknown.png)

9&10. mendapatkan data berupa hex lalu diconvert menjadi .des3 dan menggunakan openssl menggunakan password yang ditemukan

![gambar 9 10](https://media.discordapp.net/attachments/221887784108032001/1023185148738543758/unknown.png)
