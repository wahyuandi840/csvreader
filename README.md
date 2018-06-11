# csvreader
librari sederhana untuk membaca file csv
Download package dengan composer
```
composer require wahyuandi840/csvreader
```
atau
```
{
	"require": {
		"wahyuandi840/csvreader" : "dev-master"
	}
}
```
Penggunaan librari
```php
//$kolom sesuaikan dengan kolom csv
$kolom=array("nama","alamat");
$csv=new Wahyu\CsvReader("file.csv",$kolom);
//$output return array
$output=$csv->proses();
print_r($output);
```
