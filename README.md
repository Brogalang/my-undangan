# 💌 Template website undangan pernikahan sederhana

## 📦 Documentation

* Jalankan perintah `npm install`, lalu `npm run dev`, dan buka `http://localhost:8080`.
* Ubah isi file `index.html` sesuai keinginanmu.
* Untuk deployment, jalankan `npm run build:public`. Folder `public` adalah yang akan kamu upload.

> Undangan ini hanya menggunakan HTML, CSS, dan JavaScript biasa. NPM digunakan agar file JavaScript bisa langsung dieksekusi (bukan bertipe module lagi).

> Jika tetap ingin tanpa NPM, ubah `src="./dist/guest.js"` menjadi `src="./js/guest.js" type="module"` pada tag `<head>` di index dan dashboard.html, dengan risiko glitch tema di awal loading.

> Jika kamu punya pertanyaan, gunakan fitur `discussions` agar bisa dibaca juga oleh teman-teman lainnya.

> [!WARNING]  
> Gunakan versi 3.14.0, untuk versi 4 masih tahap pengembangan dan berpotensi teredapat bug 🐛

## ⚙️ Tech stack

- Bootstrap 5.3.7
- AOS 2.3.4
- Fontawesome 6.7.2
- Canvas Confetti 1.9.3
- Google Fonts
- Vanilla JS

Undangan is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
