---
title: Dasar Privasi CarbonOS
permalink: /privacy-ms/
lang: ms
---
# Dasar Privasi CarbonOS

*Berkuat kuasa 29 Oktober 2026 · [English](../privacy/) · [Terma Penggunaan](../terms/) (dalam bahasa Inggeris)*

CarbonOS menyimpan log anda di telefon anda. Pelayan kami hanya menyimpan akaun anda, pelan anda dan jumlah peruntukan yang telah anda gunakan, serta salinan log anda hanya jika anda menghidupkan Sandaran. Kami tidak sekali-kali menjual data anda, memaparkan iklan atau menjejaki anda merentas aplikasi lain.

Versi Bahasa Malaysia ini disediakan selaras dengan Akta Perlindungan Data Peribadi 2010. Jika terdapat perbezaan, kedua-dua versi bertujuan membawa maksud yang sama; hubungi kami jika sesuatu kurang jelas.

## Siapa kami

CarbonOS dibangunkan oleh Lim Jun Yi, pembangun bebas di Malaysia ("kami" dalam dasar ini), yang bertanggungjawab ke atas data peribadi anda dalam CarbonOS. Hubungi: carbonos.support@gmail.com. Jika undang-undang memerlukan pegawai perlindungan data, pegawai tersebut ialah Lim Jun Yi, melalui e-mel yang sama.

## Apa yang kekal di telefon anda

Apa yang anda log disimpan di peranti anda, dalam pangkalan data aplikasi dan dalam folder fail Markdown milik anda ("vault" anda):

- Makanan dan minuman, khasiatnya, nota dan pembetulan anda
- Foto makanan (sebelum dan selepas)
- Senaman dan timbang berat badan
- Profil anda untuk sasaran (jantina, tahun lahir, tinggi, berat, tahap aktiviti, matlamat) dan sasaran anda
- Perbualan anda dengan Carbon, pelan makan dan ulasan mingguan
- Bilangan kad kongsi yang telah anda gunakan bulan ini, dan kapsyen yang anda siarkan baru-baru ini (supaya yang seterusnya berbeza)
- Langkah dan tenaga aktif daripada Apple Health atau Health Connect, jika anda menyambungkannya (dipaparkan, tidak disimpan)
- Pilihan dan tanda kecil: unit anda, sama ada haptik (getaran) dihidupkan, mod Ramadan, mesej sambutan dan pencapaian yang telah anda lihat, pilihan peringatan, eksperimen mingguan anda, dan makanan yang diisi sebagai anggaran selepas jurang hari tanpa log (anggaran ditandakan dan tidak sekali-kali dikira dalam statistik anda)

Melainkan anda menghidupkan Sandaran, kami tidak dapat melihat, membuat sandaran atau memulihkan data ini. Sandaran telefon anda sendiri (iCloud atau Google) mungkin termasuk pangkalan data aplikasi, tertakluk kepada terma penyedia tersebut; ia tidak termasuk data Apple Health atau Health Connect, kerana CarbonOS tidak menyimpannya.

## Apa yang sampai ke pelayan kami

| Apa | Mengapa | Asas undang-undang | Tempoh simpanan |
| --- | --- | --- | --- |
| Alamat e-mel dan kata laluan (disimpan dalam bentuk hash), atau, jika anda menggunakan Sign in with Apple, pengecam akaun Apple anda dan e-mel yang Apple berikan kepada kami (mungkin alamat geganti peribadi) | Log masuk, dan e-mel kod angka jika anda menetapkan semula kata laluan | Kontrak | Sehingga anda memadam akaun |
| Pelan anda (Percuma atau Pro) dan tarikh pembaharuan | Membuka Pro | Kontrak | Sehingga anda memadam akaun |
| Bilangan imbasan, mesej dan kapsyen yang digunakan setiap hari dan minggu, serta bilangan permintaan dalam sejam atau sehari yang lalu | Had penggunaan saksama | Kontrak | Sehingga anda memadam akaun (kaunter jangka pendek dibersihkan selepas kira-kira 3 hari) |
| Bentuk alamat rangkaian anda yang telah dikelirukan secara sehala (di-hash), disimpan kali pertama akaun menggunakan AI Carbon, dan sama ada alamat e-mel itu e-mel pakai buang (e-mel itu sendiri tidak disimpan untuk ini) | Menghalang pendaftaran secara besar-besaran dan penyalahgunaan peringkat percuma | Kepentingan sah | Nilai yang dikelirukan itu dibersihkan selepas 30 hari; ia tidak boleh dipulihkan menjadi alamat anda |
| Salinan log anda (hanya jika Sandaran dihidupkan; tanpa foto, tanpa data aplikasi kesihatan) | Memulihkan di telefon baharu | Persetujuan anda | Sehingga anda mematikan Sandaran atau memadam akaun |
| Permintaan untuk kapsyen kad kongsi: bilangan dan nama pendek, tidak sekali-kali apa yang anda taip (lihat "Kad kongsi" di bawah) | Menulis kapsyen, dan had harian | Persetujuan anda | Tidak disimpan; hanya kiraan sementara dalam memori untuk had harian |
| Nombor versi aplikasi dan ID permintaan rawak sekali guna (tidak dipautkan kepada anda atau peranti anda; percubaan semula mesej yang sama menggunakan semula ID itu) bersama setiap permintaan | Meminta versi yang sangat lama supaya mengemas kini, dan membezakan percubaan semula daripada mesej kedua | Kepentingan sah | Tidak disimpan oleh kami selain dalam log operasi di bawah |
| Log operasi: masa, alamat IP, ciri yang digunakan, masa respons dan saiz; tidak sekali-kali apa yang anda katakan | Keselamatan dan menjalankan perkhidmatan | Kepentingan sah | Sehingga 30 hari |

## Apabila anda bertanya kepada Carbon

Jawapan Carbon dihasilkan oleh model AI. Aplikasi meminta kebenaran anda sebelum menghantar apa-apa kepada AI, dan anda boleh menariknya balik pada bila-bila masa di Tetapan → Privasi. Log secara manual dan imbasan kod bar berfungsi tanpanya.

Permintaan kepada Carbon mengandungi apa yang anda taip atau foto makanan anda, serta konteks yang diperlukan untuk menjawab: makanan, senaman dan berat badan hari itu, jumlah harian terkini, sasaran anda, makanan yang kerap anda log, dan perbualan terkini hari itu. Ia dihantar ke pelayan kami dan kepada penyedia AI kami, yang menghasilkan jawapan.

- Imbasan foto juga membawa dua petunjuk lemah untuk membezakan makanan yang serupa: tetapan wilayah telefon anda (kod negara dua huruf seperti MY, daripada tetapan bahasa dan wilayahnya) dan nama makanan yang paling kerap anda log. Ia hanya dihantar bersama imbasan dan hanya digunakan untuk imbasan itu.
- Pelayan kami tidak menyimpan permintaan atau jawapan. Ia menyemaknya: lihat "Semakan keselamatan" di bawah.
- Foto dikecilkan di telefon anda kepada JPEG paling besar 1024 piksel sebelum meninggalkannya. Pelayan kami hanya menerima foto JPEG, PNG atau WebP sehingga 4 MB dan 4096 piksel sebelah, dan tidak menyimpannya.
- Penyedia AI kami ialah BytePlus ModelArk, yang bertindak sebagai pemproses data kami. [Terma pemprosesan datanya](https://docs.byteplus.com/en/docs/ModelArk/BytePlus_ModelArk_Data_Processing) menyatakan bahawa ia mengendalikan data pelanggan hanya mengikut arahan kami dan tidak menggunakannya untuk latihan model sendiri tanpa kebenaran kami, yang tidak kami berikan. Tempoh ia mengendalikan sesuatu permintaan semasa menjawab ditetapkan oleh terma tersebut. Terma itu juga membenarkan BytePlus menyimpan, untuk tujuan keselamatan kandungan, permintaan yang ditanda oleh penapis keselamatannya, bagi tempoh terhad yang ditetapkannya.
- Data Apple Health dan Health Connect, e-mel anda, fail vault anda dan foto yang tidak anda imbas tidak sekali-kali dihantar kepada AI.

Apa yang anda log boleh mendedahkan maklumat kesihatan. Kami menganggapnya sebagai data peribadi sensitif dan menghantarnya kepada AI hanya dengan kebenaran nyata anda.

## Semakan keselamatan

Sesetengah mesej, contohnya tentang mencederakan diri, gangguan makan, diet melampau, kecemasan perubatan, atau seseorang yang mengatakan mereka di bawah 18 tahun, dikenali oleh pelayan kami melalui semakan corak ringkas sebelum sebarang AI digunakan. Ia dijawab dengan mesej tetap yang prihatin dan tiada apa dihantar kepada penyedia AI. Di Malaysia, mesej itu menyebut 999 dan Befrienders KL (03-7627 2929); di tempat lain ia mengarahkan anda kepada nombor kecemasan tempatan atau talian krisis. Jawapan AI Carbon juga disemak secara automatik, dan jawapan yang memberi nasihat yang tidak pernah kami beri (seperti diet kebuluran, pencahar, detoks, steroid atau melangkau makan untuk kurus) dibuang dan tidak dipaparkan. Semakan ini automatik tanpa semakan manusia. Ia boleh terlepas sesuatu, dan Carbon bukan doktor.

## Sandaran (pilihan, dimatikan secara lalai)

Sandaran dimatikan sehingga anda menghidupkannya di Tetapan, dan ia milik akaun yang menghidupkannya: akaun lain pada telefon yang sama tidak sekali-kali mempunyai datanya disalin kepada anda. Apabila dihidupkan, salinan makanan, mesej sembang, senaman, timbangan berat, makanan kod bar yang disimpan, sasaran, butiran badan (jantina, tahun lahir, tinggi, berat, aktiviti, matlamat), unit dan pilihan kecil yang disenaraikan di atas disimpan dalam akaun CarbonOS anda. Tidak sekali-kali disalin: foto, apa-apa daripada Apple Health atau Health Connect, kebenaran AI anda, dan kebenaran telefon anda. Ia tidak disulitkan hujung ke hujung (lihat "Cara kami melindunginya"). Sandaran dihadkan kepada kira-kira 8 MB: jika lebih besar, mesej sembang yang paling lama ditinggalkan dahulu, dan aplikasi memberitahu anda berapa banyak. Mematikan Sandaran memadam salinan di pelayan kami. Log keluar atau memadam akaun juga mematikannya di telefon itu. Memulihkan menggantikan log di telefon anda dengan sandaran.

## Kad kongsi

Anda boleh menukar minggu anda, sehari, satu angkat berat, satu rentetan log atau ringkasan lain menjadi gambar untuk disiarkan atau dihantar. Gambar itu dilukis di telefon anda daripada log anda sendiri dan diserahkan kepada helaian kongsi telefon anda. CarbonOS tidak memuat naiknya atau menyimpan salinan: ia hanya pergi ke mana anda pilih untuk menghantarnya, dan selepas itu aplikasi atau orang itu mengendalikannya mengikut terma mereka sendiri. Kad boleh menunjukkan perkara daripada log anda, seperti nama makanan dan senaman, bilangan, waktu dalam sehari dan rentetan log. Ia tidak sekali-kali menunjukkan berat badan anda, imej badan, kalori berbanding sasaran, atau foto anda. Semak kad sebelum menyiarkannya: sesiapa yang anda kongsikan dapat melihat semua yang ada padanya.

Kad bermula dengan kapsyen yang ditulis dalam aplikasi. Hanya jika anda menekan "Write a new caption" dan anda telah membenarkan AI, aplikasi menghantar ringkasan pendek kad kepada pelayan kami: tajuk, hari dalam minggu, bilangan (contohnya hari yang dilog, makanan, senaman, set, rentetan log), sehingga beberapa nama makanan, senaman dan otot, serta kapsyen yang baru dipaparkan kepada anda supaya yang baharu berbeza. Bukan foto anda, mesej anda, berat badan anda, kalori anda atau sebarang data aplikasi kesihatan. Ia dikendalikan seperti permintaan kepada Carbon: pelayan kami tidak menyimpannya, penyedia AI kami (BytePlus ModelArk) menulis kapsyen mengikut arahan kami, dan kami mengehadkan bilangan kapsyen yang boleh anda minta setiap hari. Jika anda belum membenarkan AI, atau anda tiada talian, kapsyen datang daripada baris yang ditulis dalam aplikasi dan tiada apa dihantar.

## Imbasan kod bar

Apabila anda mengimbas kod bar, aplikasi hanya menghantar nombor kod bar, terus dari telefon anda, kepada [Open Food Facts](https://world.openfoodfacts.org), pangkalan data makanan terbuka yang dikendalikan oleh badan bukan untung Perancis. Ia melihat nombor tersebut dan alamat IP telefon anda, seperti mana-mana laman web, dan tiada apa-apa tentang akaun anda. Data khasiat © penyumbang Open Food Facts, di bawah Open Database Licence.

## Apple Health dan Health Connect

Jika anda menyambungkannya, CarbonOS hanya membaca langkah dan tenaga aktif anda, untuk menunjukkan berapa banyak anda bergerak setiap hari. Data ini kekal di telefon anda. Ia tidak sekali-kali disimpan oleh CarbonOS, dihantar ke pelayan kami atau AI, dimasukkan dalam sandaran, digunakan untuk pengiklanan atau pemasaran, atau dikongsi dengan sesiapa. Putuskan sambungan pada bila-bila masa di Tetapan, dan buang akses dalam aplikasi Health atau Health Connect.

## Peringatan

Peringatan dikira dan dijadualkan oleh telefon anda berdasarkan log anda sendiri, jadi tiada pelayan push atau token peranti terlibat dan tiada apa-apa tentangnya dihantar kepada kami. Ia boleh menyebut makanan yang kerap anda log, rentetan log anda, hari dalam minggu, atau (pada hari-hari pertama, atau jika anda sudah lama tidak menggunakannya) petua ringkas atau peringatan lembut. Jika anda tiada untuk seketika, anda menerima paling banyak tiga peringatan dan selepas itu tiada sehingga anda kembali. Peringatan tidak sekali-kali memaparkan berat badan atau angka kalori anda, dan balasan yang anda taip dalam peringatan kekal di telefon anda sehingga anda menghantarnya. Matikan setiap jenis di Tetapan → Peringatan, atau semuanya dalam tetapan telefon anda.

## Siapa yang memproses data

Syarikat-syarikat ini mengendalikan data bagi pihak kami, di bawah terma yang mengehadkan mereka kepada menyediakan CarbonOS:

| Syarikat | Apa yang dikendalikan | Lokasi |
| --- | --- | --- |
| Supabase | Akaun, pelan, bilangan penggunaan, sandaran, pengecam log masuk dan Sign in with Apple, serta e-mel log masuk anda | Singapura |
| BytePlus ModelArk | Setiap permintaan kepada Carbon semasa ia dijawab | Pusat data BytePlus, termasuk Malaysia dan Indonesia |
| Fly.io | Pelayan kami, yang menyalurkan permintaan | Singapura |
| RevenueCat | Status langganan, dipautkan kepada id akaun anda | Amerika Syarikat |
| Apple dan Google | Pembayaran untuk Pro dan Sign in with Apple, di bawah dasar privasi mereka sendiri | Lokasi mereka sendiri |

Jika kami menukar penyedia AI, kami mengemas kini jadual ini terlebih dahulu, dan meminta kebenaran anda semula jika apa yang dihantar berubah.

Data anda mungkin diproses di luar Malaysia. Kami memindahkannya hanya ke negara yang mempunyai undang-undang yang sebahagian besarnya serupa dengan Akta Perlindungan Data Peribadi Malaysia, atau di bawah kontrak yang melindunginya pada tahap yang sama, dan bagi pengguna di EU atau UK, di bawah Klausa Kontrak Standard Suruhanjaya Eropah.

## Cara kami melindunginya

- Semua data dihantar secara tersulit (HTTPS). Token log masuk anda disimpan dalam Keychain iPhone atau Keystore Android.
- Sandaran anda disulitkan semasa disimpan dan dilindungi oleh peraturan akses supaya pengguna lain tidak dapat membacanya. Ia tidak disulitkan hujung ke hujung, jadi kami secara teknikal boleh mengaksesnya; kami tidak berbuat demikian, kecuali untuk menjalankan perkhidmatan atau jika undang-undang memerlukan.
- Akses ke pelayan dihadkan kepada apa yang diperlukan untuk menjalankan perkhidmatan.
- Jika pelanggaran data berkemungkinan menyebabkan kemudaratan yang ketara, kami memaklumkan Pesuruhjaya Perlindungan Data Peribadi dalam tempoh 72 jam dan memaklumkan anda tanpa kelewatan yang tidak wajar.

## Pilihan dan hak anda

- **Akses dan salinan:** Tetapan → Eksport log saya memberi anda semua yang ada di telefon anda sebagai fail biasa. E-mel kami untuk mendapatkan apa yang disimpan di pelayan kami, dalam format mudah alih.
- **Pembetulan:** edit apa-apa dalam aplikasi, atau minta kami membetulkan data akaun.
- **Padam akaun anda:** Tetapan → Padam akaun serta-merta membuang akaun, pelan, bilangan penggunaan dan sandaran anda dari pelayan kami; log operasi luput dalam tempoh 30 hari. Selepas itu kami juga cuba, sedaya upaya, membatalkan token Sign in with Apple yang kami pegang untuk anda (aplikasi meminta kod sekali guna yang baharu daripada Apple untuk ini dan tidak menyimpannya) dan memadam rekod pelanggan RevenueCat anda. Jika salah satu tidak dapat dihubungi pada ketika itu, e-mel kami dan kami akan menyelesaikannya. Apa yang ada di telefon anda kekal sehingga anda memadam aplikasi. Memadam akaun tidak membatalkan langganan Pro: batalkannya dalam tetapan App Store atau Google Play anda.
- **Tarik balik persetujuan:** matikan AI Carbon, Sandaran (ini memadam salinan), akses Kesihatan atau Peringatan di Tetapan. Ini tidak menjejaskan apa yang telah diproses sebelumnya.
- **Aduan:** kepada [Pesuruhjaya Perlindungan Data Peribadi Malaysia](https://www.pdp.gov.my) atau pihak berkuasa perlindungan data di tempat anda tinggal.

Kami menjawab permintaan dalam tempoh 21 hari. E-mel carbonos.support@gmail.com.

## Dewasa, kesihatan dan keselamatan

CarbonOS adalah untuk orang dewasa berumur 18 tahun ke atas; kami tidak sengaja mengumpul data daripada sesiapa yang lebih muda, dan memadamnya jika kami mengetahuinya. Jika anda memberitahu Carbon dalam mesej bahawa anda di bawah 18 tahun, ia tidak akan memberi panduan berat badan, kalori atau diet. Sasaran peribadi hanya ditetapkan untuk orang dewasa: aplikasi meminta tahun lahir anda dan tidak menetapkan sasaran jika ia mungkin bermaksud di bawah 18 tahun. CarbonOS ialah alat penjejakan dan bimbingan, bukan nasihat perubatan: angka kalori, nutrien dan pembakaran adalah anggaran, terutamanya daripada foto. Berbincang dengan doktor atau pakar diet sebelum mengubah diet anda jika anda hamil, mempunyai keadaan perubatan, atau mempunyai sejarah gangguan pemakanan. Aplikasi tidak sekali-kali menetapkan sasaran penurunan berat badan untuk sesiapa yang kurang berat badan, mengekalkan kalori di atas paras minimum yang selamat, dan mengehadkan penurunan kepada 1% berat badan seminggu.

## Perubahan

Kami akan memaklumkan anda dalam aplikasi sebelum perubahan penting berkuat kuasa. Tarikh di bahagian atas menunjukkan versi semasa.
