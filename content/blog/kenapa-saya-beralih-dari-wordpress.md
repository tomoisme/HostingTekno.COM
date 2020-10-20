---
title: "Kenapa Saya Beralih Dari WordPress Ke Static Site Generator"
date: 2020-10-18T08:55:11+07:00
draft: false
layout: "single"
description: ""
summary: "Dulu saya ini fans-nya WordPress, tapi setelah mengenal static site generator, saya langsung pindah. Mau tau alasannya?"
---

Dulu pas awal-awal saya menjalani profesi sebagai tukang bikin website, saya terkesima saat melihat WordPress. Menurut saya CMS satu ini sangat mengagumkan karena membantu meringankan pekerjaan tukang bikin web company profile atau web bisnis seperti saya ini. Tapi seiring berjalannya waktu, saya menyadari kelemahan-kelemahan WordPress. Hingga munculnya Static Site Generator yang membuat saya kembali semangat menjalani kehidupan saya sebagai tukang bikin website.

Saya pun akhirnya memutuskan untuk beralih menggunakan Static Site Generator dalam tiap project website bisnis yang saya buat. Inilah 3 alasan utama mengapa saya memutuskan untuk beralih dari WordPress:

### wordPress seringkali kena hack

Yang udah lama pake WordPress pasti ngerti deh. Entah dari pluginnya, entah dari engine WordPressnya sendiri, banyak sekali celah keamanan yang seringkali bikin saya harus install ulang website WordPress milik klien saya. Untuk mencari celah keamanannya butuh waktu dan tenaga yang tidak sedikit pula. Kalo anda cuma ngelola 1-2 website sih ngga masalah ya, bayangin kalo klien anda ada 20an atau bahkan lebih. Puyeng deh tu kepala.

Buat yang belum ngerti, intinya gini: WordPress dibuat pake bahasa pemrograman PHP (dan banyak yang bilang core-nya WordPress sendiri itu udah berantakan), selain itu WordPress juga membutuhkan akses database MySQL untuk bisa beroperasi. Karena dibuat pake bahasa pemrograman, jadi WordPress memiliki potensi untuk diretas, apalagi kalo ada plugin-plugin yang penulisannya gak aman.

Beda dengan website yang dibuat dengan Static Site Generator yang cuma terdiri dari file-file HTML, CSS, Javascript dan file statis lainnya. Website yang menggunakan Static Site Generator kaga bakalan bisa di hack bro. Kecuali hostingnya kena hack. Tapi sekalipun hostingnya kena hack, tinggal upload ulang aja, gak kayak website WordPress yang ribet dalam hal recovery-nya.

### butuh hosting dengan performa yang bagus

Dulu sebelum ada PHP 7 seperti sekarang, PHP 5.6 itu lemot banget ya ampun. Dan karena dibuat menggunakan PHP, WordPress juga otomatis ikutan kena imbas lambatnya. Karena masalah ini pula, tukang bikin website kudu pinter-pinter cari hosting yang punya performa bagus. Dan hosting dengan performa bagus itu biasanya ngga murah.

Sekarang dengan adanya PHP 7, performa WordPress bisa lebih cepet lagi. Tapi itu pun masih kalah sama website Static Site Generator. Cara satu-satunya untuk ngakalin performa website WordPress itu dengan cache. Dengan plugin cache, performa website WordPress kurang lebih kecepatannya setara dengan website Static Site Generator. Lha wong hasil cache WordPress itu sama dengan file-file HTML, CSS dan Javascript, ya sama aja dengan Static Site Generator.

Bahkan saat ini sudah ada yang menggunakan WordPress sebagai static site generator. Mungkin karena udah puyeng sama masalah performa dan hacking juga seperti saya... hahahaha.

Dengan Static Site Generator hosting yang biasa-biasa aja jadi terasa kenceng bro. Karena gak perlu lagi ngandelin PHP dan MySQL yang bikin lemot. Tiap request yang masuk dari pengunjung langsung dapet response dari web server. Nggak perlu lagi optimize ini itu, karena web server memang awalnya ditujukan untuk serving halaman website statis. 

### themes sulit untuk diubah-ubah

Ini alasan yang sebenernya sih gak terlalu penting. Tukang bikin website WordPress pasti ngerti cara utak atik website WordPress sampe ke akar-akarnya. Cuman kadang-kadang kita dapet client yang hobi ngulik website sampe ke akar-akar juga, jadi butuh fleksibilitas tinggi. Dan kadang-kadang theme WordPress tidak se-fleksibel itu ferguso.

Berbeda dengan Static Site Generator, tukang bikin web bisa obrak abrik itu themes, bahkan punya beberapa themes dalam 1 website itu memungkinkan dengan memakai Static Site Generator.

Nah karena ketiga alasan diatas itulah saya beralih dari dari jasa pembuatan website WordPress jadi jasa pembuatan website bisnis yang menggunakan Static Site Generator. Gimana menurut sobat developer website?