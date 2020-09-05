# NodeServerMan 
Aplikasi sederhana dan ngawur untuk mengelola server node js.

## Persyaratan
- Harus sudah instal `forever` (bisa diperoleh dengan `npm install -g forever` atau baca lebih lengkap di [forever - npm](https://www.npmjs.com/package/forever))
- Harus ada JRE/JDK
- File dari dist (`NodeServerMan.jar`) harus diletakkan di root proyek node.js dan dalam `package.json` sudah ada script `start` yang isinya `forever start [entrypoint.js]`

## Fitur
- Mulai server
- Tampilkan dafatar server yang berjalan
- Restart server
- Hentikan server
- Hentikan semua server yang berjalan

**PS.:**
- Belum bisa refresh otomatis setelah stop

*Saran pengembangan, silakan ajukan PR*
