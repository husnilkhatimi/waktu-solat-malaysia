Waktu Solat Malaysia Dan Tarikh Hijrah
==============
Data waktu solat untuk negeri-negeri di Malaysia setiap hari, dan pertukaran tarikh kalendar Masihi ke Hijrah sepanjang tahun, di dalam format JSON, MySQL, Sqlite dan API.

* [Data Tahunan Fail JSON](#data-tahunan-fail-json)
* [Data API eSolat.gov.my](#data-api-esolatgovmy)
* [Data API JomGeek](#data-api-jomgeek)

#### Data Tahunan Fail JSON

Contoh struktur data setahun, daripada fail `2019/WLY01.json`:

```json
{
  "prayerTime": [
    {
      "hijri": "1440-04-24",
      "date": "01-Jan-2019",
      "day": "Tuesday",
      "imsak": "04:51:00",
      "fajr": "05:01:00",
      "syuruk": "06:24:00",
      "dhuhr": "12:18:00",
      "asr": "15:38:00",
      "maghrib": "18:08:00",
      "isha": "19:23:00"
    },
  ...
    {
      "hijri": "1441-05-04",
      "date": "31-Dis-2019",
      "day": "Tuesday",
      "imsak": "04:51:00",
      "fajr": "05:01:00",
      "syuruk": "06:23:00",
      "dhuhr": "12:17:00",
      "asr": "15:37:00",
      "maghrib": "18:08:00",
      "isha": "19:23:00"
    }
  ],
  "status": "OK!",
  "periodType": "year",
  "lang": "ms_my",
  "zone": "WLY01",
  "bearing": "292&#176; 31&#8242; 16&#8243;"
}
```

#### Data API eSolat.gov.my

URL API daripada eSolat dengan respon data JSON. 

>Mungkin akan dikemaskini oleh pihak eSolat dan berhenti berfungsi pada bila-bila masa.

Senarai Zon Waktu Solat : [PDF](https://www.e-solat.gov.my/index.php?siteId=24&pageId=43) 

Hari Ini https://www.e-solat.gov.my/index.php?r=esolatApi/TakwimSolat&period=today&zone=WLY01

Minggu Ini https://www.e-solat.gov.my/index.php?r=esolatApi/TakwimSolat&period=week&zone=WLY01

Bulan Ini https://www.e-solat.gov.my/index.php?r=esolatApi/TakwimSolat&period=month&zone=WLY01

Tahun Ini https://www.e-solat.gov.my/index.php?r=esolatApi/TakwimSolat&period=year&zone=WLY01


#### Data API JomGeek

Gunakan data waktu solat melalui API percuma JomGeek.

https://api.jomgeek.com/module/waktusolat