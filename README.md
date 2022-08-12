# NodeServerMan 
Aplikasi sederhana dan ngawur untuk mengelola server node js.

![Capture](https://user-images.githubusercontent.com/13059007/184268882-7a078e2f-bcda-4a82-b494-15d4f7473319.PNG)

## Persyaratan
- Harus sudah instal `forever` (bisa diperoleh dengan `npm install -g forever` atau baca lebih lengkap di [forever - npm](https://www.npmjs.com/package/forever))
- Harus ada JRE/JDK
- File dari dist (`NodeServerMan.jar`) harus diletakkan di root proyek node.js dan dalam `package.json` sudah ada script `start` yang isinya `forever start [entrypoint.js]`

## Fitur
- Mulai server
- Restart server
- Hentikan server

## Petunjuk
Untuk mempermudah development, ganti nama folder project netbeans menyamai dengan nama folder project node.js. Misal project node.js adalah `logbook`, maka ganti nama folder `nodeserverman` menjadi `logbook`.

**PS.:**
- Metode penampilan data masih aneh menggunakan `split` teks hasil dari perintah di cmd (itulah kenapa aplikasi ini ngawur)

*Saran pengembangan, silakan ajukan PR*
