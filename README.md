# 🎵 TTDL5 — TikTok Downloader v5  
**Asikin aja 🗿**

TTDL5 adalah TikTok Downloader simple + cepat yang bisa download video TikTok (tanpa watermark) langsung dari browser.  
Backend pakai Node.js + Express, frontend pakai TailwindCSS only.

Live demo: **https://www.nuevextdl.my.id**  
Repo: **https://github.com/ShinWolf-Subject/ttdl5**

---

## 🚀 Features
- Download video TikTok (MP4)
- Tanpa watermark (kalau source support)
- UI simpel + responsif
- Full open-source
- Deploy-ready untuk Vercel
- Otomatis menyimpan file ke folder `/downloads`

---

## 📁 Struktur Proyek
```
ttdl5/               # Root
├─ downloads/        # Untuk menyimpan dan download video
│   └─ (Video)      # Hasil download/Download function
├─ public/           # Folder interface
│   ├─ index.html   # File fe utama
│   └─ script.js    # Logika Front
├─ .gitignore        # Ignored Sensitive Files/Folders
├─ package.json      # Script & Dependencies
├─ README.md         # README - Guide & Notes
├─ server-two.js     # Server utama
└─ vercel.json       # Wajib buat deploy ke Vercel
```

---

## 🛠 Tech Stack
- **Node.js**
- **Express**
- **TailwindCSS (CDN)**
- **Vercel (Deploy)**

---

## ▶️ Cara Menjalankan Lokal

```bash
git clone https://github.com/ShinWolf-Subject/ttdl5.git
cd ttdl5
npm install

# Produksi
npm start

# Development
npm run Dev
```

Server default jalan di:

```
http://localhost:3000
```

---

## 🌐 Deploy ke Vercel

1. Push repo ke GitHub  
2. Import repo-nya ke Vercel  
3. Pastikan project root benar (pakai `server-two.js`)
4. Deploy  
5. DONE 😎🔥

---

## 📜 Lisensi
MIT — bebas dipake, bebas dikembangin, yang penting **asikin aja 🗿**

## Made by me im i'am ore boku watashi aku my gua NineTwelve ☠️
