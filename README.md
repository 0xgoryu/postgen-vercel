# postgen_id

Generate konten Twitter/X dari Google Trends Indonesia, powered by OpenRouter.

## Deploy ke Vercel

### Cara 1 — Drag & Drop (paling gampang)
1. Buka [vercel.com/new](https://vercel.com/new)
2. Pilih "Deploy from template" → drag folder ini
3. Done ✓

### Cara 2 — GitHub
1. Push folder ini ke repo GitHub baru
2. Buka vercel.com → Import Git Repository
3. Pilih repo → Deploy

### Cara 3 — Vercel CLI
```bash
npm i -g vercel
cd postgen-vercel
vercel
```

## Setup API Key
Setelah deploy, buka site → klik ⚙ → masukkan OpenRouter API key kamu.
Key disimpan di localStorage (browser lokal, tidak ke server).

## Fitur
- 🟠 Reddit Indonesia — fetch hot posts r/indonesia & r/investasiid
- 🔍 Perplexity Sonar — real-time web search via OpenRouter
- Auto-fallback 7 model free di OpenRouter
- Filter topik: Crypto, AI/Tech, Ekonomi, Viral
- Panjang: Pendek / Sedang / Panjang / Auto
