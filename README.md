# Video contoh · Prompt Claude Code untuk Video Edukasi

Repo ini berisi aset gratis untuk ebook **Prompt Claude Code untuk Video Edukasi**.
Tidak ada kode aplikasi di sini: hanya hasil jadi dan data mentahnya, supaya pembaca
bisa membandingkan hasil kerja sendiri dengan contoh nyata.

## Isi

| Berkas | Keterangan |
|---|---|
| `video/satu-pembayaran-satu-efek.mp4` | Video jadi, 1080x1920, 30 fps, 3:05, narasi Bahasa Indonesia |
| `stills/f181.png` ... | Enam frame diam dari scene berbeda untuk melihat detail ilustrasi |
| `contoh/script.json` | Naskah 24 scene: label, narasi, baris teks, jenis visual, mood, sfx |
| `contoh/theme.json` | Art direction project: palet, font, posisi header, warna subtitle |
| `contoh/timeline.json` | Hasil generate: `start` dan `duration` tiap scene dari audio narasi |
| `ebook/Prompt Claude Code untuk Video Edukasi.pdf` | Ebook 55 halaman, isinya prompt |

## Cara pakai

1. Tonton `video/satu-pembayaran-satu-efek.mp4` sekali tanpa jeda, lalu sekali lagi
   sambil berhenti di tiap scene. Catat berapa lama satu scene bertahan.
2. Buka `contoh/script.json` dan cocokkan scene dengan yang barusan dilihat. Nama
   `id` di JSON sama dengan urutan scene di video.
3. Buka `contoh/timeline.json`. Perhatikan bahwa `duration` tiap scene berasal dari
   durasi audio narasinya, bukan dari teks.
4. Pakai `contoh/script.json` sebagai bahan prompt: suruh Claude Code meniru
   strukturnya untuk topik Anda sendiri, tanpa menyalin kalimatnya.
5. Pakai `contoh/theme.json` sebagai titik awal art direction project sendiri, lalu
   ganti seluruh warnanya. Dua video berpalet sama akan terlihat seperti satu seri.

## Lisensi

Video, naskah, dan data di repo ini boleh dipakai untuk belajar dan dijadikan contoh
di materi sendiri. Sebutkan sumbernya: `github.com/abdasis/remotion-edu-contoh`.
Ilustrasi dibuat sendiri dengan Manim; musik dibuat prosedural, bukan lagu berhak cipta.
