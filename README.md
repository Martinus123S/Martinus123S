# Membuat Web untuk Perhitungan Kamar Hotel

Web ini digunakan untuk melakukan perhitungan dimana tagihan Awal di set sebanyak 500000
Dan akan mendapatkan diskon jika melebihi promo yang ditentukan

![My Visitors](https://visitor-badge.glitch.me/badge?page_id=Martinus123S/Martinus123S)

### Requirement

PHP >== 5.17

### Installation

Clone project tersebut
Lalu masukkan kedalam Xampp/htdocs
Lalu Anda bisa menjalankan web tersebut

### Usage

````
function durasi($tglCekIn, $tglCekOut)
{
	$date1 = date_create($tglCekIn);
	$date2 = date_create($tglCekOut);
	$diff = date_diff($date1, $date2);
	$durasi = $diff->format("%d%");

	return $durasi;
}```
Digunakan untuk Menghitung durasi dari tanggal yang dibuat user

````

## Contributing

Project ini dibuka untuk pull request, silahkan ajuka issue jika menemukan hal tersebut
