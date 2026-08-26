# UNDANGAN DIGITAL ARSYA & YUDHA

Template ini sudah memiliki:
- Opening envelope
- Nama tamu otomatis dari URL (?to=Nama Tamu)
- Musik background (slot assets/music.mp3)
- Countdown ke 13 Maret 2026 16:00 WIB
- Animasi dekoratif
- Gallery 5 foto
- RSVP form
- Google Maps
- Tombol WhatsApp
- Wedding gift / rekening dengan tombol copy

## 1. Nama tamu otomatis
Contoh URL:
https://DOMAIN-KAMU.com/?to=Keluarga%20Budi%20Santoso

Di opening dan footer akan muncul "Keluarga Budi Santoso", dan nama RSVP otomatis terisi.

## 2. Foto
Masukkan foto ke folder assets dengan nama:
photo-1.jpg
photo-2.jpg
photo-3.jpg
photo-4.jpg
photo-5.jpg

## 3. Musik
Masukkan file MP3 ke:
assets/music.mp3

Browser biasanya memblokir autoplay. Musik mulai saat tombol "Open Invitation" ditekan.

## 4. Google Maps
Pada index.html, cari:
https://www.google.com/maps/search/?api=1&query=Bloof%20Cafe
Ganti dengan link Google Maps venue yang tepat.

## 5. WhatsApp
Cari:
https://wa.me/6281234567890
Ganti 6281234567890 dengan nomor WhatsApp yang akan menerima pesan.
Format nomor tanpa + dan tanpa spasi.

## 6. RSVP
Form sudah disiapkan, tetapi endpoint:
https://formspree.io/f/ISI_ID_FORM_KAMU
masih placeholder. Ganti dengan endpoint Formspree atau backend/form yang kamu pilih agar jawaban RSVP benar-benar tersimpan.

## 7. Rekening
Ganti NAMA BANK, nomor rekening, dan nama pemilik pada bagian "Wedding Gift".

## 8. Hosting
Upload seluruh isi folder ini ke hosting static seperti Netlify atau GitHub Pages. Setelah online, gunakan URL:
https://DOMAIN-KAMU.com/?to=Nama%20Tamu
untuk undangan personal.
