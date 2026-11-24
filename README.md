# VPS murah mulai $2.99/bulan: paket Evoxt mana yang cukup, berapa total setahun, dan kenapa tidak ada node Indonesia? (tabel 11 paket + catatan biaya tersembunyi)

Evoxt menjual VPS murah mulai **$2.99/bulan** untuk VM-0.5: 1 core, 512 MB RAM, 5 GB storage, jatah transfer 250 GB per bulan. Paket yang paling masuk akal untuk sebagian besar pembaca justru satu tingkat di atasnya, **VM-1 $5.99/bulan** dengan RAM 2 GB dan storage 20 GB, karena 512 MB tidak cukup untuk panel kontrol, database, atau build proses yang jalan bersamaan.

Dua hal yang perlu Anda tahu sebelum klik: Evoxt menagih dalam USD lewat kartu kredit/debit, PayPal, atau Bitcoin (tidak ada QRIS atau transfer bank rupiah), dan tidak punya datacenter di Indonesia. Lokasi terdekat adalah Malaysia dan Tokyo. Sisanya di artikel ini: rincian semua paket yang tampil di halaman harga, arti sebenarnya dari harga "mulai", hitungan biaya tahun pertama dan kedua, serta batas yang jarang disebut di judul artikel mana pun.

> **Ringkasan cepat**
> - Coba-coba, bot ringan, satu proses kecil: VM-0.5, $2.99/bulan.
> - Panel + 1–2 website, bot dengan database: VM-1, $5.99/bulan (2 GB RAM).
> - Sering build atau jalan beberapa container sekaligus: VM-1.5, $6.95/bulan (2 core, RAM tetap 2 GB).
> - Database agak besar atau 3–4 situs: VM-2, $11.99/bulan (2 core, 4 GB).
> - Semua paket sudah termasuk backup mingguan offsite tanpa biaya tambahan.
>
> 👉 [Deploy VM-1 dan lihat harga untuk lokasi pilihan Anda](https://console.evoxt.com/deploy.php?aff=1168)

## Semua paket Evoxt yang tampil di halaman harga

Kesebelas paket di bawah adalah yang tercantum di halaman pricing Evoxt untuk tingkatan harga Standard. Evoxt memisahkan sebagian lokasi ke tingkatan Premium dan Premium Plus dengan harga serta jatah transfer yang berbeda, jadi angka final baru muncul saat Anda memilih lokasi di halaman deploy. Semua paket memakai satu harga bulanan yang sama di halaman itu, tanpa skema harga perkenalan terpisah.

| Paket | vCPU / RAM | Storage | Transfer/bulan | Harga/bulan | Deploy |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | 250 GB | $2.99 | [Deploy VM-0.5](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-0.75 | 1 core / 1 GB | 10 GB | 250 GB | $4.99 | [Deploy VM-0.75](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-1 | 1 core / 2 GB | 20 GB | 500 GB | $5.99 | [Deploy VM-1](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-1.5 | 2 core / 2 GB | 20 GB | 500 GB | $6.95 | [Deploy VM-1.5](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-2 | 2 core / 4 GB | 30 GB | 1.000 GB | $11.99 | [Deploy VM-2](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-3 | 4 core / 4 GB | 30 GB | 1.000 GB | $14.99 | [Deploy VM-3](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-4 | 4 core / 8 GB | 60 GB | 2.000 GB | $23.99 | [Deploy VM-4](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-6 | 8 core / 8 GB | 60 GB | 2.000 GB | $29.99 | [Deploy VM-6](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-8 | 8 core / 16 GB | 80 GB | 3.000 GB | $47.99 | [Deploy VM-8](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-12 | 16 core / 16 GB | 80 GB | 3.000 GB | $60.95 | [Deploy VM-12](https://console.evoxt.com/deploy.php?aff=1168) |
| VM-16 | 16 core / 32 GB | 100 GB | 5.000 GB | $95.99 | [Deploy VM-16](https://console.evoxt.com/deploy.php?aff=1168) |

Parameter lain yang berlaku di semua paket:

| Parameter | Detail |
| --- | --- |
| Backup | Mingguan, offsite, gratis |
| Resource tambahan | vCPU $3/bulan, RAM $2/GB/bulan, IP tambahan $3/bulan, transfer $3/TB (Standard) |
| IPv6 | Didukung |
| OS | Linux dan Windows (RDP) |
| Panel | Panel sendiri: monitoring, VNC, clone VM, sub-akun, REST API |
| Firewall | Firewall Layer 3, port bisa dibuka/tutup per VM |
| Pembayaran | Kartu kredit/debit, PayPal, Bitcoin |
| Penagihan | Bulanan sampai prabayar 3 tahun; saldo kredit bisa dipakai untuk invoice berikutnya |
| Lokasi | 18 datacenter di 4 benua menurut VPSBenchmarks; halaman harga mencantumkan AS, Inggris, Kanada, Jerman, Polandia, Amsterdam, Jepang (Tokyo), Malaysia, Australia |

## Harga "mulai" $2.99 itu sebenarnya dapat apa

Yang Anda dapat adalah 1 core, 512 MB RAM, dan 5 GB storage. Untuk patokan, panel kontrol populer saja butuh RAM lebih dari 1 GB, dan satu instalasi MySQL ditambah web server sudah menghabiskan sebagian besar 512 MB sebelum aplikasi Anda dijalankan. VM-0.5 masuk akal sebagai mesin untuk satu bot, satu tunnel, monitoring, atau uji konfigurasi; bukan untuk menjalankan toko online.

Bandingkan dengan harga "mulai" di pasar lokal. Rumahweb membuka VPS mulai **Rp 50.000/bulan** untuk paket XS dengan 512 MB RAM dan 10 GB SSD, sedangkan paket 1 GB-nya Rp 60.000. DomaiNesia menjual Cloud VPS Lite 1 GB/20 GB NVMe di **Rp 43.200/bulan** sebagai harga promo, dengan keterangan harga perpanjangan Rp 48.000/bulan. Herza Cloud menulis mulai Rp 37.500/bulan tanpa menyebut konfigurasi di judulnya. VPS Murah memakai model rakit komponen: Rp 2.500 per core, Rp 5.000 per GB RAM, Rp 1.500 per GB NVMe, dan IP dedicated Rp 30.000/bulan.

Artinya, $2.99 untuk 512 MB bukan kejutan besar dibanding pasar lokal. Yang Evoxt jual di harga itu adalah frekuensi CPU tinggi dan harga per GB RAM yang turun cepat di paket menengah: dari 512 MB ke 2 GB hanya naik $3.00, sementara di daftar lokal kenaikan 512 MB ke 1 GB saja sudah Rp 10.000. Halaman Evoxt mengiklankan frekuensi hingga 6.0 GHz; pernyataan yang dikutip VPSBenchmarks menyebut CPU dengan frekuensi minimum 3.5 GHz. VPSBenchmarks, yang membeli server sendiri dan mengujinya dengan Sysbench dan Geekbench, menempatkan Evoxt di jajaran atas penyedia VPS budget, dengan catatan bahwa ini bukan penyedia dengan SLA enterprise.

👉 [Buka halaman deploy Evoxt untuk melihat semua paket dan lokasi](https://bit.ly/EvoXt)

## Biaya tahun pertama dan tahun kedua

Karena halaman harga Evoxt mencantumkan satu harga bulanan tanpa skema harga perkenalan terpisah, hitungannya sederhana:

- VM-0.5: $2.99 × 12 = **$35.88** tahun pertama, angka yang sama di tahun kedua.
- VM-1: $5.99 × 12 = **$71.88** per tahun, atau $143.76 untuk dua tahun.
- VM-2: $11.99 × 12 = **$143.88** per tahun.

Di pasar lokal, ada contoh yang tidak sesederhana itu. DomaiNesia menulis Rp 43.200/bulan sebagai harga promo dan Rp 48.000/bulan sebagai harga perpanjangan. Selisih Rp 4.800 per bulan terdengar kecil, tapi jadi Rp 57.600 setahun yang tidak muncul di judul artikel mana pun. Jagoan Hosting memilih pendekatan sebaliknya dan menyatakan harganya saat perpanjangan sama dengan saat pembelian. Sebelum memesan di mana pun, cari kata "harga perpanjangan" di halaman checkout, bukan hanya di banner promo.

Evoxt juga mengizinkan prabayar bulanan sampai 3 tahun dan pengisian saldo kredit yang otomatis dipakai untuk invoice berikutnya. Kalau Anda ingin mengunci pengeluaran, prabayar lebih panjang mengurangi jumlah transaksi kartu, tetapi tetap cek apakah harga untuk lokasi pilihan Anda sama dengan harga Standard di tabel atas.

## Batas yang perlu Anda terima sebelum bayar

**Tidak ada datacenter Indonesia.** Pengunjung dari Jakarta akan dilayani dari Malaysia atau Tokyo. Sebagai patokan kasar, penyedia lokal melaporkan latency node mereka sendiri: Jakarta sekitar ±23 ms, Singapura sekitar ±24 ms. Evoxt tidak mempublikasikan angka latency per lokasi, jadi jangan berharap angka itu. Untuk blog dan aplikasi internal, selisih puluhan milidetik jarang terasa. Untuk toko online dengan mayoritas pembeli di Indonesia, server di Indonesia memberi TTFB lebih rendah, seperti yang juga ditekankan Rumahweb di halaman produknya.

**Pembayaran tanpa QRIS.** Metodenya kartu kredit/debit, PayPal, dan Bitcoin. Kartu berdenominasi rupiah akan dikonversi oleh penerbit kartu Anda, dan sebagian bank menambahkan biaya transaksi luar negeri. Kalau pembayaran utama Anda QRIS dari GoPay atau Dana, ini hambatan nyata, bukan detail kecil.

**Tidak ada proteksi DDoS di tabel fitur.** VPSBenchmarks mencatat Evoxt tanpa proteksi DDoS dan tanpa penagihan per jam. Penyedia lokal justru menjadikan anti-DDoS sebagai bahan jualan utama. Kalau server Anda pernah jadi sasaran serangan, ini pertimbangan yang menentukan.

**Server dikelola sendiri.** Anda memilih OS saat deploy, dan tidak ada paket pengelolaan yang tercantum di halaman harga. Bandingkan dengan biaya managed di pasar lokal: Rumahweb menjual Managed Service Rp 250.000/bulan di luar lisensi cPanel, lebih dari lima kali harga VPS termurahnya sendiri. Kalau Anda tidak ingin menyentuh SSH, anggarkan biaya itu atau pilih shared hosting.

**Transfer di-throttle, bukan ditagih.** Kelebihan pemakaian bandwidth tidak menimbulkan tagihan kejutan; kecepatannya yang diturunkan. Menurut VPSBenchmarks, jatah gratisnya 2 TB/bulan untuk instance 2 core 4 GB, dan transfer tambahan dijual $3/TB di tingkatan Standard.

👉 [Deploy VM-0.5 sebagai uji coba berisiko rendah](https://console.evoxt.com/deploy.php?aff=1168)

## Siapa yang sebenarnya tidak perlu VPS

Blog statis, landing page kampanye, atau website company profile satu halaman tidak butuh VPS. Shared hosting Rumahweb mulai Rp 15.000/bulan dan sudah termasuk panel, email, dan pemeliharaan server. VPS baru masuk hitungan ketika Anda butuh root, instalasi paket sendiri, cron yang tidak dibatasi, Docker, atau aplikasi yang tidak bisa jalan di shared hosting. Di titik itu Anda membayar dengan uang sekaligus waktu: patch keamanan, konfigurasi firewall, dan pemantauan jadi tugas Anda.

## Memilih paket berdasarkan kebutuhan

Aturan di bawah memakai harga dan konfigurasi Evoxt di tabel atas, bukan perkiraan.

- **Satu bot, satu tunnel, atau server uji:** VM-0.5, $2.99. Batas 5 GB storage cepat penuh kalau Anda menyimpan log.
- **Panel kontrol + 1–2 website, atau bot dengan database:** VM-1, $5.99. Ini paket dengan rasio harga per GB RAM terbaik di daftar.
- **Sering build, jalan beberapa container, atau cron bertumpuk:** VM-1.5, $6.95. Tambahan $0.96 untuk core kedua masuk akal kalau proses Anda sering antre.
- **Database 2–4 GB atau 3–4 situs kecil:** VM-2, $11.99 dengan 4 GB RAM dan 30 GB storage.
- **Banyak container, staging plus produksi di satu mesin:** VM-4, $23.99 dengan 8 GB RAM.
- **VM-8 ke atas:** mulai $47.99. Kalau kebutuhan Anda sudah sampai sini, label "vps murah" tidak lagi relevan dan Anda sebaiknya membandingkan dengan penyedia yang menyertakan SLA dan proteksi serangan.

Alternatif lain, resource bisa ditambah tanpa ganti paket: vCPU $3/bulan, RAM $2/GB/bulan, IP $3/bulan. Untuk kenaikan kecil, menambah RAM 1 GB di paket yang sama lebih murah daripada naik dari VM-1 ke VM-2 (selisih $6.00).

## FAQ

**Apakah harga bisa berubah saat perpanjangan?**
Halaman harga Evoxt mencantumkan satu harga bulanan dan tidak memisahkan harga perkenalan dari harga perpanjangan. Itu berbeda dari DomaiNesia yang menulis eksplisit Rp 43.200/bulan sebagai promo dan Rp 48.000/bulan untuk perpanjangan. Simpan tangkapan layar invoice pertama Anda sebagai pembanding.

**Bisa bayar pakai QRIS, GoPay, atau transfer bank Indonesia?**
Tidak. Metode yang tercantum adalah kartu kredit/debit, PayPal, dan Bitcoin.

**Ada server di Indonesia atau Singapura?**
Tidak ada di Indonesia. Lokasi Asia yang tercantum di halaman harga adalah Malaysia dan Jepang (Tokyo). Singapura tidak masuk daftar itu.

**Apakah bisa upgrade nanti?**
Bisa. Evoxt menyebut resource bisa ditambah satuan tanpa mengganti paket, dan paket bisa dinaikkan kapan saja dari panel.

**Backup termasuk atau bayar terpisah?**
Backup mingguan offsite sudah termasuk di semua paket tanpa biaya tambahan, dan bisa direstore sendiri lewat panel.

**Bisa install Windows?**
Bisa, Evoxt menyediakan opsi Windows termasuk akses RDP. Ini salah satu alasan orang memilih Evoxt di segmen harga ini, karena banyak penyedia menagih lisensi Windows terpisah.

**Apakah ini KVM dan apakah saya dapat root?**
Halaman harga tidak menyebut jenis virtualisasi secara eksplisit; ulasan pihak ketiga menyebut isolasi KVM per VM. Anda memilih OS sendiri saat deploy dan mengelola server sepenuhnya, jadi konfigurasi tingkat sistem ada di tangan Anda. Kalau KVM adalah syarat mutlak untuk aplikasi Anda, konfirmasi lewat tiket sebelum membayar.

## Penutup: pilih berdasarkan yang Anda jalankan, bukan harga termurah

Kalau Anda hanya butuh satu proses kecil yang selalu hidup, VM-0.5 $2.99 sudah cukup dan tidak ada gunanya membayar lebih. Kalau ada panel, database, atau lebih dari satu website, langsung ambil VM-1 $5.99; selisih $3.00 dari paket termurah adalah uang paling berguna yang bisa Anda belanjakan di daftar ini. Kalau bottleneck-nya CPU karena build atau container, VM-1.5 $6.95; kalau yang kurang RAM, VM-2 $11.99.

Tiga hal yang perlu dikonfirmasi sebelum checkout: harga untuk lokasi yang Anda pilih (bisa berbeda dari tabel Standard), kebijakan pembatalan dan refund yang tidak tercantum di halaman harga, dan apakah port 25 dibuka kalau Anda berencana mengirim email langsung dari server. Sisanya, backup mingguan dan penambahan resource satuan sudah jelas di halaman produk.

👉 [Pilih paket Evoxt dan mulai deploy dari panel](https://console.evoxt.com/deploy.php?aff=1168)
