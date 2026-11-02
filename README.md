# Orbit Breaker — Gamepad Lab & Starfighter

Orbit Breaker adalah aplikasi browser yang menggabungkan permainan tempur luar angkasa 3D dan laboratorium pengujian gamepad. Antarmukanya menggunakan Bahasa Indonesia. Repository ini memuat file HTML yang diberikan oleh Zimuru Tempest.

## Fitur yang tersedia dalam kode

- **Mode tempur:** pesawat 3D, tembakan, manuver elak, kemampuan Tempest Nova, skor dan empat pilihan tingkat kesulitan.
- **Lab tester gamepad 360°:** visualisasi controller 3D, matriks 17 tombol, tampilan analog, pemeriksaan circularity dan stick drift.
- **Pilihan input:** Gamepad API, keyboard, mouse, dan kontrol sentuh yang tersedia pada antarmuka. Pemetaan perangkat dan fitur getaran bergantung pada browser dan hardware.
- **Skor terbaik lokal:** aplikasi mencoba menyimpan skor terbaik menggunakan localStorage pada browser yang digunakan.

## Menjalankan

Unduh repository, lalu buka `Gamepad.html` di browser modern yang mendukung WebGL dan JavaScript. Koneksi internet diperlukan untuk memuat Tailwind CSS, Three.js, Google Fonts, dan Phosphor Icons dari layanan eksternal. Untuk pengujian Gamepad API, dukungan dan izin browser dapat berbeda; localhost atau HTTPS mungkin diperlukan sesuai browser.

Pilih **Mulai Mode Tempur** atau **Lab Tester Gamepad 360°**. Untuk controller, hubungkan perangkat dan tekan salah satu tombol agar browser mendeteksinya.

## Kontrol

Petunjuk lengkap tersedia di dalam aplikasi. Kode memetakan **Space** untuk menembak, **R** atau **Z** untuk manuver, **F** atau **U** untuk kemampuan ultimate, dan **Escape** atau **P** untuk menjeda mode tempur. Gerak dapat memakai keyboard atau gamepad. Kesesuaian pemetaan gamepad berbeda antar perangkat.

## Status pengujian dan batasan

Pemeriksaan sintaks JavaScript melalui Node.js berhasil. Pengujian interaktif pada browser dan controller fisik belum terverifikasi; dukungan perangkat tidak dijamin. Gamepad, WebGL, audio, penyimpanan browser, dan dependensi CDN dapat dipengaruhi pengaturan browser, perangkat, atau koneksi. Data skor disimpan lokal apabila penyimpanan tersedia; tidak ada jaminan data bertahan jika penyimpanan browser dibersihkan.

## Kredit dan hak penggunaan

File menyertakan kredit **Zimuru Tempest** dan permintaan untuk tidak mendistribusikan tanpa kredit. Belum ada lisensi open-source yang dinyatakan untuk kode proyek; hubungi pemilik untuk izin penggunaan atau distribusi lebih lanjut. Tailwind CSS, Three.js, Google Fonts dan Phosphor Icons adalah dependensi pihak ketiga dengan ketentuan masing-masing.

README ini disusun dengan bantuan OpenAI Codex berdasarkan pemeriksaan kode; asal atau proses pembuatan file asli belum diverifikasi.

---

**English summary:** A browser-based 3D space shooter and gamepad tester. It includes controller visualization, button and analog diagnostics, and local high-score storage. Interactive browser and physical-controller behavior has not yet been verified.
