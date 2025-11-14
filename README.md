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
ttdl5/
├─ downloads/
│   └─ (hasil download .mp4)
├─ public/
│   ├─ index.html
│   └─ script.js
├─ .gitignore
├─ package.json
├─ README.md
├─ server-two.js
└─ vercel.json
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

## Made by me aku my gua NineTwelve ☠️
