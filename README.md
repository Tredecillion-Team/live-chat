## live-chat

Aplikasi untuk berbicara dengan AI menggunakan suara. Aplikasi menggunakan Backend Google AI Studio.

## Prasyarat

Pastikan Anda telah menginstal **Node.js versi 20** dan **GIT**.  
Anda dapat mengunduhnya melalui tautan berikut:  
[Node.js v20.9.0](https://nodejs.org/id/blog/release/v20.9.0)

[GIT](https://git-scm.com/downloads)

## Instalasi

Ubah **API KEY** pada file **.env.local** berikut:

```bash
GEMINI_API_KEY=YOUR_API_KEY
```

Setelah Node.js dan GIT terinstal, jalankan perintah berikut di terminal pada folder yang telah ditentukan:

```bash
git clone https://github.com/Tredecillion-Team/live-chat.git
cd live-chat
npm init -y
npm install vite dotenv --save-dev
```

## Menjalankan Aplikasi

Untuk menjalankan aplikasi, gunakan perintah berikut:

```bash
npm run dev
```
