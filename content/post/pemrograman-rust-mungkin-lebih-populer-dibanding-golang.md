---
title: "Mungkin Rust akan Menang"
thumbnailImagePosition: right
thumbnailImage: https://source.unsplash.com/7Nrb5I7heJI/200x200
coverImage: https://source.unsplash.com/7Nrb5I7heJI/1200x600
metaAlignment: center
coverMeta: out
coverCaption: "Spec illustration by Cathryn Lavery"
date: 2017-08-26T23:25:36+07:00
categories:
- startup
- development
tags:
- development
- programming
- analyst
- rust
- golang
- python
- node
draft: false
---
Jika kalian jengah mendengar banyak bahasa pemrograman baru yang muncul baru-baru ini, mungkin kali ini saya akan sedikit bercerita. Adalah tentang bahasa pemrograman yang pernah atau sedang saya amati, salah satunya adalah Rust by Mozilla yang mungkin akan banyak berperan di beberapa sektor terutama sistem programming.
<!--more-->

Agaknya cukup dini bagi saya mengklaim bahwa bahasa Rust ini akan populer suatu saat nanti, namun saya cukup percaya diri bahwa kedepannya manusia akan mengedepankan efisiensi proses dan simplicity, dimana akan merevolusi bagaimana kita mendesain suatu software dan mengembangkan suatu program. Saya sendiri pun agak skeptis pada awalnya, karena baru beberapa bulan terakhir melihat perkembangan Golang yang begitu masif dan di adaptasi di banyak produk dan startup.

## Mari Mengingat Masa Lalu
Seperti yang kita ketahui satu dekade terakhir banyak hal terjadi pada dunia programming, dari yang saya ketahui awal berdirinya perusahaan internet tidak lain dan tidak jauh berasal dari Perl atau PHP, ya PHP memang identik dengan Perl dimana PHP memang pengembangan yang terbentuk dari Perl. PHP di satu sisi is more easy to adapt and to understand as we start to code and build a simple thing. Ingat bagaimana XAMPP / LAMPP rule our world? ya semudah itulah instalasi dan memulai kegiatan pemrograman.

Namun dunia terus berjalan, satu demi satu bahasa memperlihatkan keunggulannya, Ruby dengan Rails, Python dengan Django dan PHP dengan banyak frameworknya. Microsoft dan Sun Microsystem juga mengejar dengan .NET dan Java (dimana saya saat itu juga penggemar berat Java). Di masa lampau orang tidak begitu memperhatikan bagaimana  suatu program dapat bekerja, dan dimana perbedaan bahasa yang membutuhkan kompilasi dan bahasa yang menggunakan interpretasi. Mereka hanya suka membuat program dengan berbagai metode yang mereka sukai, Java dengan OOP-nya, .NET dengan banyak pilihan bahasanya, PHP dengan simplisitasnya serta banyak lagi. Sampai suatu saat kita tersadar bahwa kecepatan suatu eksekusi program menjadi faktor utama.

Dari semua itu PHP keluar sebagai pemenang, orang-orang banyak membuat website, meramu produk dan sebagainya menggunakan PHP. Tidak lain dan tidak bukan karena PHP memberikan kita keleluasaan dalam berkreasi, mudah untuk dipelajari dan komunitas yang besar. Facebook dan Wordpress adalah beberapa produk yang terlahir dari bahasa tersebut. Jadi bisa dikatakan PHP merupakan pilihan yang mudah ketika kita membuat suatu aplikasi.

Lalu Ruby on Rails muncul, banyak yang mulai menggunakannya dalam pembuatan project-project berskala besar maupun kecil. Kemudahan scaffold dan fitur-fitur peringkas menjadikan orang cukup fanatik dengan bahasa ini. Dukungan OOP yang lebih baik menjadikan bahasa ini mulai diminati, Twitter adalah salah satu yang terlahir dari Ruby.

## Kita Butuh Yang Ringan
Bila di telaah secara spesifik, tiap bahasa mempunyai "waktunya" sendiri untuk hadir, namun kita selalu melihat kedepan. Menitik beratkan pada ringannya suatu proses CPU juga pada Memory. Beberapa bahasa pada saat itu belum benar-benar sempurna dalam penggunaan memory, kecepatan eksekusi, serta efisiensi processor hingga NodeJs hadir menjadi alternatif menjanjikan dengan konsep concurrency A.K.A non-blocking.

Yah mungkin kalian berkata, concurrency? well memang tidak sepenuhnya proses NodeJs itu berjalan parallel. Yang sebenarnya adalah pada Node terdapat loop dari proses yang di instruksikan dan karena proses ini berjalan begitu cepat maka bisa dikatakan hal ini merupakan non-blocking process. Because as we know even our CPU is blocking tapi tetap saja hal ini masih lebih menguntungkan karena kita dapat menjalankan beberapa instruksi sekaligus.

Namun NodeJs yang saya ketahui masih menitik beratkan pada memori, dan semakin banyak CPU yang digunakan semakin concurrent proses pada NodeJs dan ini merupakan alternatif yang sempurna karena NodeJs sendiri mempunyai banyak kelebihan bila digunakan untuk pembuatan aplikasi berbasis internet. Contohnya seperti non-blocking IO, websocket, kecepatan parsing JSON dkk, powerful HTTP feature dan banyak lagi. Tidak mengherankan karena NodeJs dibuat secara tidak sengaja dengan menggunakan Javascript basis engine milik Google yaitu V8. Well agak kurang pantas memang menyebut NodeJs sebagai bahasa, karena sejatinya NodeJs hanyalah semacam interpreter / JIT machine yang menggunakan javascript sebagai bahasanya.

Dengan NodeJs banyak yang mulai beralih ke dalam pemrograman non-blocking, menggunakan NodeJs berarti menghemat penggunaan resource dengan amount / spek server yang lebih kecil. Walmart, Paypal, AirBNB serta Google adalah beberapa perusahaan yang mengadaptasi Node di beberapa sektor aplikasinya. Karena NodeJs dapat melakukan proses yang lebih cepat dan efisien, Javascript pun menjadi primadona karenanya banyak Front-End developer kini dapat ikut membuat program yang berlaku sama seperti Back-End, dari sinilah muncul istilah Fullstack developer.

## Golang is Google with it's language
Tidak butuh waktu lama untuk Go hadir membayangi NodeJs sebagai bahasa yang populer pada saat itu, Golang muncul tidak lama setelah NodeJs hadir. Hanya berselang 2 tahun sejak kelahiran Node, Golang memberikan alternatif yang cukup "menjanjikan" untuk kebutuhan developer akan efisiensi dan concurrency. Bahasa Go memiliki Goroutines yang memudahkan pengeksekusian secara parallel namun tetap dalam penulisan kode yang prosedural. Hal ini di klaim lebih baik dari Node karena NodeJs pada satu sisi membawa mimpi buruk dengan penggunaan Callback-nya, meskipun selang beberapa saat fitur Promise dapat membuatnya lebih baik, namun tetap tidak terlihat "best practice" pada praktiknya.

Yang saya tahu, Google membuat golang bukan tanpa alasan. Ketika ketiga engineer Google bertemu dan berdiskusi dalam menciptakan bahasa yang bisa digunakan dengan kecepatan dan penulisan kode yang efisien. Agaknya mereka berhasil merepresentasikan hal ini. But remember mereka adalah Google, Go di desain berdasarkan kebutuhan google dalam menangani limitasi kemampuan Python yang digunakan pada saat itu, namun dapat bereaksi secepat C++. Sehingga tidak mengherankan beberapa pihak mengatakan bahasa Go terlihat aneh dengan struktur kodenya, karena memang diciptakan untuk kalangan developer professional Google.

## Golang Mungkin Belum Sempurna, But at Least We Use That for Profit.
Golang memang menang dari segi proses, concurency dan kecepatan compile program. Namun banyak hal yang menjadikan bahasa ini agak kurang disegani. Dimulai dari bahasa yang "aneh" jauh dari kata familiar oleh programmer, Tidak adanya Generic Functions sampai yang paling saya sorot adalah dependency management. Berbeda dengan NodeJs yang memiliki NPM, Golang tidak memiliki dependency management tool, malah Golang menggunakan url dan relative path sebagai pondasinya. 

Well come on Google, kita semua tahu Golang tidak dibuat berdasarkan kebutuhan komunitas seperti NodeJs. Golang pada dasarnya dibuat dengan tujuan penggunaan oleh Google dalam service-servicenya. Tetap saja di samping itu kita hanya bisa memanfaatkan kelebihan Golang daripada kekurangannya. 

## NodeJS Level Up!!
Sejak kebangkitan javascript dari populernya NodeJs, banyak pihak yang mulai menggunakannya. Transpiler dan banyak tool diciptakan dengan tujuan untuk menggunakan javascript dengan fun. Typescript, Elm, Coffescript, Babel dan banyak lainnya hadir dengan satu tujuan, simplisitas. Kebanyakan dari kita tumbuh dengan konsep OOP dimana konsep ini menjadikan hal lebih simpel dengan merepresentasi segala hal ke dalam bentuk objek, so it is reusable. Hal ini tentunya tidak begitu baik mengingat Javascript sangat buruk dalam implementasi OOP. Keterbatasan ini berlanjut hingga belakangan konsep Functional Programming populer. Functional Programming adalah metode penulisan fungsi sederhana yang hanya bertujuan untuk melakukan satu hal saja, singkat kata satu fungsi hanya mempunyai satu tugas, very clear and easy to test that's it.

Singkat kata sejak munculnya standard javascript ES5 dan ES6, NodeJs semakin populer hingga yang paling saya sukai adalah konsep async-await pada standard ES7. Saya percaya hal ini memberikan dampak lebih besar lagi karena javascript akan lebih simpel dan lebih mudah untuk digunakan dari berbagai kalangan developer.

## Ssst... Rust...
Rust awalnya tidak begitu menyita perhatian saya, bahasa yang diciptakan oleh Mozilla ini memiliki konsep Memory Safety Guarantee. Dimana hal ini merupakan hal yang sangat-sangat signifikan, karena yang saya tahu Rust hadir untuk menggantikan C++ namun dengan konsep modern dan clear writen pada saat penggunaannya. Struktur bahasa Rust memang tidak bisa disandingkan dengan bahasa pemrograman lain seperti Python, Node, Java karena memang bertujuan untuk pemrograman berbasis sistem. Bisa diartikan Rust hadir untuk mereka yang menginginkan efisiensi memory namun juga pada kecepatan. Rust di satu sisi terlihat membingunkan pada awalnya, namun struktur bahasanya lebih jelas dan modern. Golang developer should try Rust btw.

Kecepatan dan efisiensi bukanlah masalah bagi Rust, dependency management, Generic Functions dan library juga sangat baik. Agaknya Mozilla memang mendesain bahasa ini untuk komunitas, dan bagi saya mereka cukup berhasil membuat saya tertarik. Rust merupakan bahasa yang jelas, kalian akan diarahkan menuliskan kode yang jelas mengenai tipe variabel dan variant dari tipe variabel seperti integer misalnya. Dari segi eksekusi Rust sangat cepat, stuktur project pada Rust juga sangat jelas. Cargo di satu sisi sebagai NPM bagi Rust dan masih banyak fitur lainnya untuk di eksplore lebih lanjut.

Meskipun agak timpang, karena sangat jauh membandingkan Rust dengan beberapa bahasa pemrograman tadi. Namun Golang developer mungkin suatu saat mencoba Rust dan memutuskan bahasa mana yang akan mereka pilih. Karena jika mereka menitik beratkan pada kecepatan, Rust adalah pilihan yang tepat. Rust mungkin masih baru, namun secara perlahan mengambil perhatian setelah Browser Firefox berbasis Servo mereka (yang dibuat dari Rust) mengalami peningkatan preforma yang luar biasa mengalahkan (hampir) seluruh test dengan Google Chrome.

Tidak ada yang sempurna dari semua hal yang saya ceritakan di atas, masing-masing bahasa ada dengan kelebihannya sendiri, pilih mana yang terbaik untuk project yang tepat. Mungkin Rust sempurna untuk Microcontroller, mungkin NodeJs untuk WebApp, mungkin Golang untuk RESTful, dan mungkin Python untuk Machine Learning dan Big Data. Tidak ada yang sempurna pada semua sisi, but we have a right to choose that. Have a Good Day.
