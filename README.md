## CashAja API Proxy


API Proxy untuk melakukan Bypass Penarikan API untuk simulasi menuju MTF MCalc. Berikut adalah contoh pemanggilan:  
  
```
[URL Proxy Source Code ini Di Deploy] / [Alamat Tujuan Berbeda Domain]

* http://localhost:8080/http://google.com/ - Google.com dengan CORS headers
* http://localhost:8080/google.com - Sama seperti diatas
* http://localhost:8080/google.com:443 - Mem-proxy-kan https://google.com/
* http://localhost:8080/ - Halaman utama Proxy CashAja ada pada berkas libs/help.txt
* http://localhost:8080/favicon.ico - Replies 404 Not found
```
