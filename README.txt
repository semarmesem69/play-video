VANCE TWEET — ONE VIDEO PER POST

Website ini dibuat untuk model:
SATU LINK POSTINGAN = SATU VIDEO.

Cloudflare cukup deploy SEKALI.
Setiap postingan baru hanya membuat URL berbeda dengan mengganti parameter.

FORMAT:
https://ALAMAT-WEBSITE-KAMU/?video=LINK_VIDEO&title=JUDUL

Contoh:
https://ALAMAT-WEBSITE-KAMU/?video=https%3A%2F%2Fcontoh.com%2Fvideo1.mp4&title=Video%201

Bisa juga memakai thumbnail dan deskripsi:
https://ALAMAT-WEBSITE-KAMU/?video=LINK&title=Judul&thumb=LINK_THUMB&desc=Deskripsi

PARAMETER:
video = link langsung file video (contoh .mp4)
title = judul postingan
thumb = link gambar thumbnail (opsional)
desc = deskripsi (opsional)
date = tanggal (opsional)

PENTING:
- Link video harus dapat diputar langsung oleh browser.
- Jangan gunakan link halaman YouTube/Google Drive biasa sebagai video.
- Encoding URL diperlukan jika link/parameter memiliki karakter seperti spasi, &, ?, #.
- Nama website tetap Vance Tweet.
- Social Bar dan Popunder Adsterra sudah dipasang di template.
- Jangan memasukkan kode rahasia/API key ke HTML.

CONTOH CARA MUDAH:
Jika alamat website:
https://vancemp4.susancole2711.workers.dev/

Postingan 1:
...?video=LINK_VIDEO_1&title=Video%20Satu

Postingan 2:
...?video=LINK_VIDEO_2&title=Video%20Dua

Keduanya memakai website yang sama, tetapi halaman masing-masing hanya menampilkan satu video.
