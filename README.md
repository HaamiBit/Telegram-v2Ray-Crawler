# Telegram V2Ray Crawler

📡 This Python script crawls the last 50 messages from Telegram channels and extracts up to 10 recent VLESS proxy links per channel. It saves the result in a `sub.txt` file on Google Drive, which can then be used with a Cloudflare Worker to serve as a V2Ray subscription link.

## ✨ Features

- Telegram scraping with Telethon
- Extract VLESS links (can be extended for vmess, trojan, etc.)
- Save to Google Drive
- Optional: Auto-run with Google Apps Script
- Serve via Cloudflare Worker (Base64-encoded)

## 🚀 How to Use

1. Clone or download the notebook
2. Add your `api_id`, `api_hash`, and `phone number`
3. Run it on [Google Colab](https://colab.research.google.com)
4. Find `sub.txt` in your Google Drive
5. Serve it via Cloudflare Worker

## 📦 Requirements

- Telethon
- Google Colab
- Google Drive

## 📬 Telegram Channels to Crawl

- [@meli_proxyy](https://t.me/meli_proxyy)
- [@mtmvpn](https://t.me/mtmvpn)

---

> Developed by HaamiBit 🧠
