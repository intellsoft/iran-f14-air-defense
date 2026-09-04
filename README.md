<div align="center">

# 🛩️ F-14 TOMCAT | Iran Air Defense Simulator
## شبیه‌ساز دفاع هوایی ایران — F-14 تامکت

### 🌐 Official Website | وب‌سایت رسمی: [intellsoft.ir](https://intellsoft.ir)

[![Version](https://img.shields.io/badge/version-1.2-green.svg)](https://intellsoft.ir)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://intellsoft.ir)
[![No-Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://intellsoft.ir)

**یک بازی شبیه‌ساز نبرد هوایی سه‌بعدی، کاملاً نوشته‌شده با Vanilla JavaScript و Canvas — بدون هیچ کتابخانه‌ای!**
*A 3D air-combat flight simulator written entirely in Vanilla JavaScript + Canvas 2D — zero dependencies!*

</div>

---

<div dir="rtl">

## 🇮 درباره بازی

شما خلبان جنگندهٔ **F-14A تامکت** نیروی هوایی ارتش جمهوری اسلامی ایران هستید. وظیفهٔ شما دفاع از حریم هوایی کشور در برابر موج‌های حملهٔ پهپادهای انتحاری، جنگنده‌های متخاصم، موشک‌های کروز و خلبان‌های تک‌خال دشمن است.

### ✨ ویژگی‌ها
- 🗺️ **زمین سه‌بعدی رویه‌ای** (بیابان‌ها و کوه‌های ایران) با رندر نرم‌افزاری روی Canvas
- ✈️ **مدل سه‌بعدی F-14** با دم دوقلو، دو موتور و بال‌های پس‌گرا
- 🎯 ** ماموریت دفاعی**: آموزش، تهران، خلیج فارس، اصفهان و عملیات سپر ایران
- 🏙️ **دفاع از شهرها** — اگر ۳ شهر سقوط کند، ماموریت شکست می‌خورد
- 🚀 **موشک AIM-54 فینیکس و AIM-7 اسپارو** + توپ ۲۰mm
- 📡 **رادار تاکتیکی، HUD کامل، قفل موشک و هشدار RWR**
- 🔊 **صدای رویه‌ای موتور، شلیک و انفجار** با Web Audio API
- 💾 **ذخیره‌سازی خودکار** + خروجی/ورودی فایل JSON
- ⚙️ تنظیمات کیفیت گرافیک، حساسیت کنترل و صدا

### 🕹️ کنترل‌ها
| کلید | عملکرد |
|------|--------|
| `↑ / ↓` | پیچ (دماغه بالا/پایین) |
| `← / →` | غلتش |
| `A / D` | سکان |
| `W / S` | رانش (تریل) |
| `Space` | توپ ۲۰mm |
| `E` | موشک فینیکس |
| `B` | موشک اسپارو |
| `F` | شراره ضد موشک |
| `X` | ترمز هوایی |
| `C` | تغییر دوربین |
| `Esc` | توقف |

</div>

---

## 🇬🇧 About The Game

You are the pilot of an **F-14A Tomcat** of the Islamic Republic of Iran Air Force (IRIAF). Your mission: defend the homeland's airspace against waves of suicide drones, hostile fighters, cruise missiles and enemy aces — before they reach Iranian cities.

### ✨ Features
- 🗺️ **Procedural 3D terrain** (Iranian deserts & mountains) — software-rendered on Canvas 2D
- ✈️ **3D F-14 model** with twin tails, twin engines & swept wings
- 🎯 **5 defense missions**: Training, Tehran Shield, Persian Gulf, Isfahan Shield, Operation Iran Shield
- 🏙️ **City-defense mechanic** — lose 3 cities and the mission fails
- 🚀 **AIM-54 Phoenix & AIM-7 Sparrow** missiles + 20mm cannon
- 📡 **Tactical radar, full HUD, missile lock & RWR warnings**
- 🔊 **Procedural audio** (engine, guns, explosions) via Web Audio API
- 💾 **Auto-save** + JSON export/import
- ⚙️ Graphics quality, control sensitivity & volume settings

### 🕹️ Controls
| Key | Action |
|-----|--------|
| `↑ / ↓` | Pitch |
| `← / →` | Roll |
| `A / D` | Yaw (rudder) |
| `W / S` | Throttle |
| `Space` | 20mm Cannon |
| `E` | AIM-54 Phoenix |
| `B` | AIM-7 Sparrow |
| `F` | Flares |
| `X` | Airbrake |
| `C` | Camera switch |
| `Esc` | Pause |

---

## 🚀 How to Run | نحوه اجرا

No build step, no dependencies. Just open the file:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/iran-f14-air-defense.git
cd iran-f14-air-defense

# Option 1: open directly
# just double-click index.html

# Option 2: serve locally
npx serve .
# or
python -m http.server 8000
```

Then visit `http://localhost:8000`

---

## 🌍 Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set **Source** to `Deploy from a branch` → `main` / `root`
4. Your game will be live at:
   ```
   https://YOUR_USERNAME.github.io/iran-f14-air-defense/
   ```

---

## 📁 Project Structure

```
iran-f14-air-defense/
├── index.html      # The entire game (engine + assets + UI) — single file!
├── README.md       # This file
├── LICENSE         # MIT
└── screenshots/    # (optional) game screenshots
```

---

## 🛠️ Tech Stack

- **Vanilla JavaScript (ES6)** — game engine, physics, AI
- **Canvas 2D** — custom 3D software renderer (projection, clipping, painter's sort)
- **Web Audio API** — procedural sound synthesis
- **CSS3** — RTL Persian military-style UI
- **localStorage** — save system

> No frameworks. No WebGL. No external assets. 100% self-contained in one HTML file.

---

## 🌐 Website | وب‌سایت

<div align="center">

### Developed by **IntellSoft**
### [https://intellsoft.ir](https://intellsoft.ir)

</div>

---

## 📄 License

MIT License — free to use, modify and distribute. See [LICENSE](LICENSE).

---

<div align="center">

**اگر این پروژه را دوست داشتید، یک ⭐ بدهید!**
*If you like this project, give it a ⭐!*

Made with ❤️ in Iran 🇮🇷 — [intellsoft.ir](https://intellsoft.ir)

</div>
YOUR_USERNAME` را با نام کاربری گیت‌هاب خود جایگزین کنید
4. از **Settings → Pages** انتشار را فعال کنید تا بازی آنلاین شود
5. لینک سایت خودتان (`https://intellsoft.ir`) از قبل در بخش‌های مختلف README (هدر، وب‌سایت و فوتر) قرار داده شده است ✅
