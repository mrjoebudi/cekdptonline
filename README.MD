 # Private API CEK DPT PEMILU 2024
API private untuk memeriksa SCAN KTP ambil data NIK dan CEK Apakah terdaftar DPT atau belum pada website KPU.GO.ID 

**NOTE:** Saya mengembangkan menggunakan javasript NODE JS
tema 		: Periksa NIK DPT Pemilu 2024
Data sumber	: https://cekdptonline.kpu.go.id/
dibuat		: tim Gurita Langit
			: Kapten Ibnu Budi R. 

Location	: Bakungan Distric Of Osing
Date Oprek	: 12 Desember 2023 - 11:15 PM

====
cara penggunakan manual ketik saja : node cari.js --nik '3510153009810003'
versi		: 1.0
-add customUA for scurity reason
-fix element catch
-regext for number only
-fix typing keyboard like user human input ( scurity reason )
-estrak data dan kirim ke API --> whatsapp request ( next )
-loop permimtaan data request client

=== todo ==
-integrasi dengan framework laravel upload foto ktp scan dan auto input ke form tersimpan dalam database
-integrasi dengan aplikasi android melalui API Private 

== kelemahan / kekurangan ==
tidak bisa menggunakan IP luar indonesia ( proxy )

npx @puppeteer/browsers install chromedriver@116.0.5793.0
npx puppeteer browsers install chrome

## Quick Links

* [Guide / Getting Started](https://wwebjs.dev/guide) _(work in progress)_
 

## Cara instalasi
-belum ditulis
 

Membutuhkan  Node v12+  dan Otak encer

## Contoh Pemakaian
-belum dituis
