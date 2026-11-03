# Rapih Privacy Policy

Effective date: 3 November 2026

Rapih is a file manager for macOS made by **PT Sopwer Teknologi Indonesia** ("Sopwer", "we"). This policy explains what Rapih does with data. Questions or requests: **hi@sopwer.net**.

## In short

- Rapih works on your Mac. Your files and file names stay on your Mac or on the servers you connect it to. **We never receive your files or file names.**
- There is no account and no sign-in.
- Once a day Rapih sends an anonymous usage ping (described below). You can turn it off.
- Optional features (AI with your own API key, servers, updates) talk to the services you choose, directly from your Mac.
- We do not sell data, show ads, or track you across apps or websites.

## Data that stays on your Mac

To work, Rapih keeps on your Mac: your settings, a journal of file operations (so you can undo them), cached thumbnails, saved connections, and the Quarantine (items you set aside, kept for 30 days in a hidden `.rapih-quarantine` folder, then moved to the Trash). This data is stored in Rapih's folder in your user Library and is not sent anywhere. Passwords, keys and API keys are stored in the macOS Keychain. Removing Rapih and its Library folder removes this data.

**Full Disk Access** is an optional macOS permission that lets Rapih show protected folders. It does not send anything anywhere.

## Anonymous usage statistics

To count how many people install and use Rapih, once a day Rapih sends one small event to **Google Analytics 4** (Google LLC) containing only:

- a random ID created for this installation (not linked to you, your Mac or your Apple account),
- the Rapih version, the macOS version, the chip type (Apple silicon or Intel) and the app language,
- a session ID and a fixed engagement time that Google Analytics needs to count an active user.

It never contains file names, paths, file contents, what you do in the app, or AI data, and it asks Google not to use it for personalized ads. Like any internet request, the connection reveals your IP address to Google. We use the results only as totals. Google's processing is described in Google's privacy policy.

The ping is on by default and is explained in the welcome guide. **Turn it off at any time in Settings › General › "Send anonymous usage statistics"**; the next ping is then not sent.

## Updates

If automatic update checks are on (Settings › Updates), Rapih downloads a small file once a day from **GitHub** (GitHub, Inc.) to see whether a new version exists, and downloads the update only when you choose to install it. No identifier is sent; GitHub sees the request and your IP address. Updates are signed, and Rapih refuses an update whose signature does not match.

## Optional features and the services you choose

- **AI with Apple's on-device model** (macOS 26): processing happens on your Mac.
- **AI with your own API key** (OpenAI, Anthropic, or an OpenAI-compatible server you enter): to suggest names or organize files, Rapih sends **file names, extension, size, modification date and, when macOS recorded it, the website a file was downloaded from (domain only)** — and **short text excerpts (up to 2 KB per file, including text recognized in PDFs and images on your Mac) only from folders you explicitly allow** — **directly from your Mac to that provider**, never to Sopwer. The provider's own terms and privacy policy apply. Rapih shows a preview before any change and never deletes your files.
- **Find similar** works only on your Mac (Apple's on-device frameworks); nothing is sent.
- **Servers and buckets** (SFTP, S3-compatible storage, Cloudflare Tunnel): Rapih connects only to the servers you add and transfers files between your Mac and them. Logging in through Cloudflare Access uses Cloudflare's `cloudflared` tool and browser login.

## Your choices and rights

You can turn off statistics and update checks, choose not to use AI or to use only on-device AI, and remove saved connections at any time. Because we do not hold information that identifies you, we usually cannot look up or link data to you; if you have a request about your personal data under Indonesia's Personal Data Protection Law (UU No. 27 of 2022) or other applicable law, contact **hi@sopwer.net** and we will help.

## Children

Rapih is a general-purpose tool and is not directed to children.

## Changes

If this policy changes, we will update it here and change the effective date. Important changes will be mentioned in the release notes.

---

# Kebijakan Privasi Rapih

Berlaku sejak: 3 November 2026

Rapih adalah file manager untuk macOS buatan **PT Sopwer Teknologi Indonesia** ("Sopwer", "kami"). Kebijakan ini menjelaskan apa yang dilakukan Rapih terhadap data. Pertanyaan atau permintaan: **hi@sopwer.net**.

## Ringkasnya

- Rapih bekerja di Mac Anda. Berkas dan nama berkas tetap di Mac Anda atau di server yang Anda sambungkan. **Kami tidak pernah menerima berkas maupun nama berkas Anda.**
- Tidak ada akun dan tidak perlu masuk (login).
- Sekali sehari Rapih mengirim ping statistik anonim (lihat di bawah). Anda bisa mematikannya.
- Fitur opsional (AI dengan API key Anda sendiri, server, pembaruan) terhubung langsung dari Mac Anda ke layanan yang Anda pilih.
- Kami tidak menjual data, tidak menampilkan iklan, dan tidak melacak Anda di app atau situs lain.

## Data yang tetap di Mac Anda

Agar bisa bekerja, Rapih menyimpan di Mac Anda: pengaturan, jurnal operasi berkas (agar bisa di-undo), cache thumbnail, koneksi tersimpan, dan Karantina (item yang Anda sisihkan, disimpan 30 hari di folder tersembunyi `.rapih-quarantine`, lalu dipindah ke Trash). Data ini ada di folder Rapih di Library pengguna Anda dan tidak dikirim ke mana pun. Kata sandi, kunci, dan API key disimpan di Keychain macOS. Menghapus Rapih beserta foldernya di Library akan menghapus data ini.

**Full Disk Access** adalah izin macOS opsional agar Rapih dapat menampilkan folder yang dilindungi. Izin ini tidak mengirim apa pun.

## Statistik pemakaian anonim

Untuk menghitung jumlah orang yang memasang dan memakai Rapih, sekali sehari Rapih mengirim satu event kecil ke **Google Analytics 4** (Google LLC) yang hanya berisi:

- ID acak yang dibuat untuk instalasi ini (tidak terkait dengan Anda, Mac Anda, atau akun Apple Anda),
- versi Rapih, versi macOS, jenis chip (Apple silicon atau Intel), dan bahasa app,
- ID sesi dan waktu keterlibatan tetap yang dibutuhkan Google Analytics untuk menghitung pengguna aktif.

Event ini tidak pernah berisi nama berkas, path, isi berkas, apa yang Anda lakukan di app, atau data AI, dan meminta Google tidak memakainya untuk iklan yang dipersonalisasi. Seperti permintaan internet lainnya, koneksi ini memperlihatkan alamat IP Anda kepada Google. Kami hanya memakai hasilnya sebagai angka total. Pemrosesan oleh Google dijelaskan dalam kebijakan privasi Google.

Ping ini aktif secara default dan dijelaskan di panduan awal. **Matikan kapan saja di Settings › General › "Send anonymous usage statistics"**; ping berikutnya tidak akan dikirim.

## Pembaruan

Bila cek pembaruan otomatis aktif (Settings › Updates), sekali sehari Rapih mengunduh berkas kecil dari **GitHub** (GitHub, Inc.) untuk melihat apakah ada versi baru, dan baru mengunduh pembaruan bila Anda memilih memasangnya. Tidak ada pengenal yang dikirim; GitHub melihat permintaan dan alamat IP Anda. Pembaruan bertanda tangan, dan Rapih menolak pembaruan yang tanda tangannya tidak cocok.

## Fitur opsional dan layanan pilihan Anda

- **AI dengan model Apple di perangkat** (macOS 26): pemrosesan terjadi di Mac Anda.
- **AI dengan API key Anda sendiri** (OpenAI, Anthropic, atau server kompatibel OpenAI yang Anda masukkan): untuk mengusulkan nama atau merapikan berkas, Rapih mengirim **nama berkas, ekstensi, ukuran, tanggal ubah, dan — bila dicatat macOS — situs asal unduhan (domainnya saja)** — serta **cuplikan teks pendek (maks. 2 KB per berkas, termasuk teks yang dikenali dari PDF dan gambar di Mac Anda) hanya dari folder yang Anda izinkan secara tegas** — **langsung dari Mac Anda ke penyedia tersebut**, tidak pernah ke Sopwer. Syarat dan kebijakan privasi penyedia berlaku. Rapih selalu menampilkan pratinjau sebelum perubahan dan tidak pernah menghapus berkas Anda.
- **Cari file mirip (Find similar)** hanya berjalan di Mac Anda (framework Apple di perangkat); tidak ada yang dikirim.
- **Server dan bucket** (SFTP, penyimpanan kompatibel S3, Cloudflare Tunnel): Rapih hanya terhubung ke server yang Anda tambahkan dan memindahkan berkas antara Mac Anda dan server tersebut. Login lewat Cloudflare Access memakai alat `cloudflared` milik Cloudflare dan login di browser.

## Pilihan dan hak Anda

Anda bisa mematikan statistik dan cek pembaruan, memilih tidak memakai AI atau hanya AI di perangkat, serta menghapus koneksi tersimpan kapan saja. Karena kami tidak menyimpan informasi yang mengidentifikasi Anda, biasanya kami tidak dapat mencari atau mengaitkan data dengan Anda; bila Anda memiliki permintaan terkait data pribadi berdasarkan UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi atau hukum lain yang berlaku, hubungi **hi@sopwer.net** dan kami akan membantu.

## Anak-anak

Rapih adalah alat umum dan tidak ditujukan untuk anak-anak.

## Perubahan

Bila kebijakan ini berubah, kami akan memperbaruinya di sini dan mengganti tanggal berlakunya. Perubahan penting akan disebutkan di catatan rilis.
