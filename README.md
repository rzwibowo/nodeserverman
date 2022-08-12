# nodeserverman

petunjuk_
untuk mempermudah development, ganti nama folder project netbeans menyamai dengan nama folder project node.js
misal project node.js adalah logbook
maka ganti nama folder nodeserverman menjadi logbook
# NodeServerMan 
Aplikasi sederhana dan ngawur untuk mengelola server node js.

![NodeServerMan preview](https://i.ibb.co/DbJBLrG/anydesk00000.png)

## Persyaratan
- Harus sudah instal `forever` (bisa diperoleh dengan `npm install -g forever` atau baca lebih lengkap di [forever - npm](https://www.npmjs.com/package/forever))
- Harus ada JRE/JDK
- File dari dist (`NodeServerMan.jar`) harus diletakkan di root proyek node.js dan dalam `package.json` sudah ada script `start` yang isinya `forever start [entrypoint.js]`

## Fitur
- Mulai server
- Tampilkan daftar server yang berjalan
- Restart server
- Hentikan server
- Hentikan semua server yang berjalan

**PS.:**
- Belum bisa refresh otomatis setelah stop
- Ada karakter aneh di data script location
- Metode penampilan data masih aneh menggunakan `split` teks hasil dari perintah di cmd (itulah kenapa aplikasi ini ngawur)

*Saran pengembangan, silakan ajukan PR*
