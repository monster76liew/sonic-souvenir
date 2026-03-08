# 🎵 Sonic Souvenir

> *Your Place · Your Feeling · Your Song*

Turn any photo into a personalised song — AI maps the colours, mood and memory of your moment into a unique melody and lyrics. No two songs are ever the same.

Built at **ASB She Builds Hackathon · Women's Day 2026 🇲🇾**

---

## ✨ What It Does

1. **📸 Upload a photo** — anywhere on earth. Eiffel Tower, Petronas Towers, your grandma's backyard, a hawker centre.
2. **💭 Choose your feeling** — joyful, nostalgic, peaceful, adventurous... or all of them at once.
3. **✍️ Add your memory** — one line about what this place means to you.
4. **🎵 Get your song** — a unique song title, full lyrics, colour palette, and a melody composed just for this moment.

---

## 🧠 How It Works

```
Your Photo
    ↓
Claude Vision API  →  analyses colours, mood, scene
    ↓
Colour-to-Music Algorithm
  Warm reds/oranges   →  major keys, high energy
  Cool blues/greens   →  minor keys, contemplative
  Golden/amber        →  nostalgic, acoustic
  High contrast       →  dynamic rhythm
  Soft/muted tones    →  gentle, ambient
    ↓
Song Title · Lyrics · Vibe Description · Colour Strip
    ↓
Lyria by Google  →  real AI-composed instrumental music
    ↓
Your Sonic Souvenir 🎵
```

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Pure HTML · CSS · Vanilla JS |
| AI Vision + Lyrics | Claude Sonnet (Anthropic) |
| Music Generation | Lyria 002 (Google DeepMind via Vertex AI) |
| Audio Fallback | Web Audio API (browser-native synthesis) |
| Hosting | GitHub Pages |

---

## 🌟 Features

- **🎨 Colour-to-music mapping** — the photo's palette directly shapes the key, tempo and genre
- **💭 Human in the loop** — your feelings and memories are woven into the lyrics
- **📖 Memory Timeline** — save every souvenir, replay anytime
- **👥 Collab mode** — same place, different feelings, one blended song *(coming v2)*
- **📤 Share** — WhatsApp, Email, native share sheet
- **🎭 Demo mode** — try the full experience instantly, no account needed

---

## 🚀 Try It

👉 **[sonic-souvenir on GitHub Pages](https://yourusername.github.io/sonic-souvenir)**

No sign-up. No account. Just upload a photo and get your song.

---

## 💡 The Business Model

| Tier | Duration | Price |
|------|----------|-------|
| Spark | 30 seconds | Free |
| Memory | 60 seconds | RM 3 |
| Story | 2 minutes | RM 8 |
| Anthem | Full song | RM 18 |
| Traveller | Unlimited | RM 29/mo |

**Platform plays:**
- 🏨 White-label for hotels, tourism boards, airports
- 🔌 REST API for travel apps to embed photo-to-song
- 📍 QR codes at landmarks — scan, create, share

---

## 🏗 Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/sonic-souvenir.git

# 2. Open index.html in your browser
# That's it — no build step, no dependencies!
```

To enable real AI generation, add your API keys to the constants at the top of the script in `index.html`:

```javascript
const ANTHROPIC_KEY = 'sk-ant-...';   // console.anthropic.com
const GCP_TOKEN     = 'ya29-...';     // gcloud auth print-access-token
const GCP_PROJECT   = 'your-project'; // gcloud config get-value project
```

---

## 🗺 Roadmap

- [x] Photo upload + Claude Vision analysis
- [x] Colour-to-music algorithm
- [x] Lyrics generation with personal memory weaving
- [x] Web Audio synthesiser fallback
- [x] Lyria music integration
- [x] Memory Timeline
- [x] Share via WhatsApp / Email / Native
- [x] Demo mode (no API key needed)
- [ ] Backend proxy (hide API keys server-side)
- [ ] Real user accounts + persistent timeline
- [ ] Collab mode real-time sync
- [ ] App Store (iOS + Android via Capacitor.js)
- [ ] API marketplace listing (RapidAPI, AWS)
- [ ] QR code landmark partnerships

---

## 👩‍💻 Built By

Made with love (and a lot of coffee ☕) at **ASB She Builds Hackathon, Women's Day 2026**.

*From zero to working product in one afternoon — that's the She Builds spirit.*

---

## 🙏 Powered By

- [Claude AI](https://anthropic.com) — vision analysis + lyrics
- [Lyria by Google DeepMind](https://deepmind.google) — AI music generation
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) — browser-native audio synthesis
- [Google Fonts](https://fonts.google.com) — Lora + Karla

---

*✦ Your memories, forever.*
