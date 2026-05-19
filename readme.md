# 🩸 Pre-Diabetic Food Guide

A free, UK-based Progressive Web App (PWA) that helps pre-diabetic adults make better food choices based on their current blood sugar reading.

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PWA](https://img.shields.io/badge/PWA-ready-brightgreen)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20android%20%7C%20iOS-lightgrey)

---

## 🌐 Live App

👉 [Open the App](https://diabetic-food-guide.netlify.app)

---

## 📱 What It Does

Enter your blood sugar reading in mmol/L and the app instantly:

- **Identifies your zone** — Low / Normal / Raised / High
- **Gives personalised food advice** — what to eat right now for your level
- **Searches a database of 200+ UK foods** — each rated Safe, Caution, or Avoid based on your reading
- **Shows GI values** — Glycaemic Index for every food with portion sizes and carb counts
- **Highlights the best foods to eat right now** — sorted by safest first

---

## ✨ Features

- 🔬 **GI Food Database** — 200+ common UK foods across 13 categories
- 📋 **Personalised Food Advice** — meal ideas for breakfast, lunch, dinner and snacks
- 🟢 🟡 🔴 **Colour-coded ratings** — Safe / Caution / Avoid per food based on your reading
- 🔍 **Search & filter** — by food name, category, GI level, or status
- 📊 **Stats dashboard** — see how many foods are safe vs avoid at your current level
- ⚠️ **Full medical disclaimer** — UK MDR 2002 compliant
- 📜 **One-off user agreement** — must be accepted before using the app
- 📱 **PWA ready** — installs on Android and iPhone like a native app
- 🔒 **Privacy first** — no data collected, no sign up, works offline
- 🇬🇧 **UK focused** — mmol/L units, UK supermarket foods, UK emergency guidance

---

## 🍽️ Food Categories

| Category | Examples |
|---|---|
| Bread & Bakery | Rye bread, sourdough, oatcakes |
| Cereals & Grains | Porridge, quinoa, barley |
| Rice & Pasta | Basmati rice, wholemeal spaghetti |
| Fruit | Berries, apples, bananas |
| Vegetables | Broccoli, sweet potato, carrots |
| Dairy | Greek yoghurt, milk, cheese |
| Meat & Fish | Chicken, salmon, eggs |
| Legumes | Lentils, chickpeas, hummus |
| Snacks | Nuts, dark chocolate, oatcakes |
| Drinks | Tea, coffee, water, juices |
| Sauces & Condiments | Olive oil, mustard, pesto |
| Ready Meals | Common UK supermarket meals |
| Sweets & Desserts | Dark chocolate, sugar-free jelly |

---

## 🩸 Blood Sugar Zones

| Zone | Reading | Advice |
|---|---|---|
| 🔵 Low | Below 4.0 mmol/L | Fast-acting carbs needed immediately |
| 🟢 Normal | 4.0 – 5.9 mmol/L | Balanced low-GI meals to maintain |
| 🟠 Raised | 6.0 – 7.9 mmol/L | Low-GI foods, smaller portions |
| 🔴 High | 8.0+ mmol/L | Avoid carbs, contact GP if persistent |

---

## 📲 Install as an App

**Android (Chrome):**
1. Open the app in Chrome
2. Tap the 3-dot menu
3. Tap **Add to Home Screen**
4. Tap **Install**

**iPhone (Safari):**
1. Open the app in Safari
2. Tap the **Share** button
3. Tap **Add to Home Screen**
4. Tap **Add**

---

## 🚀 Getting Started (Developers)

### Prerequisites
- A web browser
- A text editor (VS Code recommended)
- A Netlify account (free)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/diabetic-food-guide.git

# Navigate to the folder
cd diabetic-food-guide
```

### Files

```
diabetic-food-guide/
│
├── index.html          # Main app — all HTML, CSS and JS
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline support)
├── icon-192.png        # App icon 192x192
├── icon-512.png        # App icon 512x512
└── README.md           # This file
```

### Deploy to Netlify

1. Fork this repository
2. Log into [netlify.com](https://netlify.com)
3. Click **Add new site → Import from Git**
4. Connect your GitHub account
5. Select this repository
6. Click **Deploy site**
7. Live in 30 seconds ✅

---

## ⚠️ Medical Disclaimer

This application is intended for **general informational and educational purposes only**. It does not constitute medical advice, diagnosis, or treatment.

This app is **not a regulated medical device** under the UK Medical Devices Regulations 2002 and is not approved or endorsed by the NHS or MHRA.

**Never adjust prescribed medication — including insulin — based on this app.**

Always consult your GP, diabetes nurse, or registered dietitian before making changes to your diet or diabetes management plan.

In a medical emergency call **999**.

Full disclaimer is displayed within the app and must be accepted before use.

---

## 📊 Analytics

This app uses **Google Analytics (GA4)** to track anonymous usage data including:
- Number of visitors
- Device type
- Country of origin
- Session duration

No personal or medical data is collected. See our privacy policy within the app.

---

## 🗺️ Roadmap

- [ ] Blood sugar log / diary
- [ ] Weekly meal planner
- [ ] Barcode scanner for packaged foods
- [ ] Push notifications for meal reminders
- [ ] Google Play Store submission
- [ ] Apple App Store submission
- [ ] Premium subscription features
- [ ] NHS partnership integration

---

## 🤝 Contributing

Contributions are welcome! If you'd like to:
- Add foods to the database
- Improve the GI values
- Fix a bug
- Suggest a feature

Please open an issue or submit a pull request.

---

## 📄 Licence

This project is licensed under the **MIT Licence** — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Built With

- Vanilla HTML, CSS & JavaScript — no frameworks
- Google Analytics GA4
- Netlify (hosting)
- PWA (Progressive Web App) technology

---

## 📬 Contact

Have feedback or want to partner with us?

- 🌐 Website: [your-website.co.uk](https://your-website.co.uk)
- 📧 Email: your@email.com

---

*Made with ❤️ in the UK — helping pre-diabetics make better food choices every day*
