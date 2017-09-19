# Scatter Echart

I. Jenis : Bubble Chart

II. Option : 

### **BACKGROUND** ###
1.  BackgroundColor : untuk memberi warna pada latar belakang.

### **TITLE** ###
1.	Title : Text (string) -> untuk membuat judul.
2.	Title : link (string) -> untuk memindahkan halaman dari judul.
3.	Title : Target (string) blank -> untuk membuka halaman lain di tab baru.
4.	Target (string) self -> untuk membuka halamanlain pada tab yang sama.
5.	Title : textAlign (string) -> menentukan letak teks (center,right,left).
6.	Title : textStyle (string) fontWeight lighter -> membuat judul menjadi tipis.
7.	Title : textStyle (string) fontStyle-> untuk mengubah gaya huruf 
8.	Title : textStyle (number) fontSize -> untuk mengubah ukuran text.
9.	Title : textStyle (string) color -> untuk mengubah warna

### **LEGEND** ###
1.	Legend : left (string, number) -> Jarak objek dari sebelah kiri.
2.	Legend : right (string, number) -> Jarak  objek dari sebelah kanan.
3.	Legend : top (string, number) -> Jarak objek dari sebelah atas.
4.	Legend : bottom (string, number) -> jarak objek dari sebelah  bawah.
5.	Legend : padding (number) -> membuat ruang di sekitar text.
6.	Legend : itemGap (number) -> jarak antara masing-masing legend, jarak horizontal dalam tata letak horizontal, dan jarak vertical dalam dalam tata letal vertical.
7.	Legend : itemWidth (number) -> lebar gambar symbol legend.
8.	Legend : itemHeight (number) -> panjang gambar symbol legend.
9.	Legend : formatter (string, function) -> digunakan untuk memformat label legend, yang mendukung template string dan function callback.
10.	Legend : selectedMode (string, boolean) -> mode legend yang dipilih, yang menggontrol apakah sama dapat ditampilkan secara bergantian dengan mengklik salah satu legend (single, multiple).
11.	Legend : inactiveColor (color) -> warna legend pada saat tidak aktif.
12.	Legend : textStyle (number) fontSize -> untuk mengubah ukuran text.
13.	Legend : textStyle (string) fontStyle-> untuk mengubah gaya huruf.
14.	Legend :  textStyle (string) color -> untuk mengubah warna.
15. Legend : textStyle (string) fontWeight  -> membuat judul menjadi tipis.

### **xAXIS** ###
1. 	xAxis : splitLine Line Type : dashed -> digunakan untuk tipe terputus-putus.

### **yAXIS** ###
1. 	yAxis : Scale (Boolean) true -> hanya tersedia dalam sumbu numerik, yaitu, ketik: 'value'.

### **SERIES** ###
1.  Series : Type Scatter -> Scatter (bubble) bagan. Diagram scatter dalam koordinat empat persegi panjang dapat digunakan untuk menyajikan hubungan antara x dan y. Jika data memiliki banyak dimensi, nilai dimensi lainnya dapat divisualisasikan melalui simbol dengan berbagai ukuran dan warna, yang menjadi grafik gelembung.
2.	Series : symbolSize (number, array, function) -> untuk ukuran symbol.

### **LABEL** ###
1.	Label : emphasis (boolean) true -> untuk menunjukan label.
2.	Label : position (string, array) top -> posisi label diatas. 

### **ItemStyle** ###
1.	ItemStyle : shadowBlur (number) -> Ukuran bayangan blur. Atribut ini harus digunakan bersamaan dengan shadowColor, shadowOffsetX, shadowOffsetY untuk mengatur bayangan ke komponen.
2.	ItemStyle : shadowColor (color) -> Warna bayangan Mendukung format yang sama dengan warna.
3.	ItemStyle : ShadowOffsetX (Number) -> Jarak offset pada arah horizontal bayangan.
4.	itemStyle : ShadowOffsetY (number) -> Jarak offset pada arah vertical bayangan.

### **GRID** ###
1.	Grid : left (string, nuber) -> jarak antara komponen grid dan sisi kiri.
2.	Grid : bottom (string, number) -> jarak antara komponen grid dan sisi bawah.
3.	Grid : top (string, number) ->jarak antara komponen grid dan sis atas.
4.	Grid : right (string, number) -> jaral antara komponen grid dan sisi kanan.
5.	Grid : show (string) true -> untuk menunjukan grid dalam koordinat.
6.	Grid : borderColor (color) -> untuk memberikan warna pada batas grid.


