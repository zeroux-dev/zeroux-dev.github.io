<!--
  zeroux-dev.github.io — personal site of ZERO (Sobhan)
  Author: ZERO (Sobhan) · https://github.com/zeroux-dev · Telegram @fesqhli
-->

<p align="center">
  <a href="https://zeroux-dev.github.io/"><img src="./assets/banner.svg" alt="ZERO — Sobhan · UI/UX Designer & Web Developer" width="100%"></a>
</p>

<h1 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" width="42" alt="👋">
  zeroux-dev.github.io
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Sparkles.png" width="42" alt="✨">
</h1>

<p align="center">
  <a href="https://zeroux-dev.github.io/"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2400&pause=800&color=FF5B24&center=true&vCenter=true&multiline=false&width=720&height=46&lines=Hi%2C+I'm+ZERO+%E2%80%94+Sobhan+%F0%9F%91%8B;I+design+interfaces+%26+build+the+web;3D+lines+that+move+with+your+scroll;FA+%2F+EN+%C2%B7+4+themes+%C2%B7+zero+dependencies;Click+to+open+the+live+site+%E2%86%97" alt="Typing intro"></a>
</p>

<p align="center">
  <img src="./assets/wave.gif" width="78%" alt="sound wave">
</p>

<p align="center">
  <a href="https://zeroux-dev.github.io/"><img src="https://img.shields.io/badge/%F0%9F%9F%A2_LIVE-zeroux--dev.github.io-ff5b24?style=for-the-badge&labelColor=0d0d0c" alt="Live site"></a>
  <a href="https://zeroux-dev.github.io/?lang=fa"><img src="https://img.shields.io/badge/%D9%86%D8%B3%D8%AE%D9%87-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-ecebe4?style=for-the-badge&labelColor=0d0d0c" alt="Persian version"></a>
  <a href="https://t.me/fesqhli"><img src="https://img.shields.io/badge/Telegram-@fesqhli-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0d0d0c" alt="Telegram"></a>
  <a href="https://github.com/zeroux-dev"><img src="https://img.shields.io/github/followers/zeroux-dev?style=for-the-badge&logo=github&label=Follow&color=ecebe4&labelColor=0d0d0c" alt="Follow"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-single_file-ecebe4?style=flat-square&logo=html5&logoColor=E34F26&labelColor=0d0d0c">
  <img src="https://img.shields.io/badge/JS-vanilla-ecebe4?style=flat-square&logo=javascript&logoColor=F7DF1E&labelColor=0d0d0c">
  <img src="https://img.shields.io/badge/Canvas-3D_lines-ecebe4?style=flat-square&labelColor=0d0d0c">
  <img src="https://img.shields.io/badge/i18n-FA_%2F_EN-ecebe4?style=flat-square&labelColor=0d0d0c">
  <img src="https://img.shields.io/badge/deps-0-3ddc84?style=flat-square&labelColor=0d0d0c">
  <img src="https://img.shields.io/github/last-commit/zeroux-dev/zeroux-dev.github.io?style=flat-square&color=ff5b24&labelColor=0d0d0c&label=updated">
  <img src="https://komarev.com/ghpvc/?username=zeroux-dev-site&label=views&color=ff5b24&style=flat-square" alt="views">
</p>

<p align="center">
  <a href="https://zeroux-dev.github.io/"><img src="./assets/preview.gif" alt="Live preview: loader, 3D lines moving with scroll, theme switch, FA/EN" width="92%"></a>
  <br><sub>▶ loader → headline reveal → 3D lines react to scroll → background switch → Persian (RTL)</sub>
</p>

<p align="center"><img src="./assets/terminal.svg" width="80%" alt="Animated terminal"></p>

<img src="./assets/divider.svg" width="100%">

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/High%20Voltage.png" width="30" alt="⚡"> What's inside

| | |
|---|---|
| **Scroll-driven 3D lines** | A wave field projected in 3D on `<canvas>`. Scrolling tilts the camera and pulls the lines toward you; the mouse adds a little yaw. |
| **FA / EN switch** | In the header *and* footer. Real RTL layout, remembers your choice, supports `?lang=fa` links. |
| **One-button backgrounds** | **Ink**, **Paper**, **Blueprint**, **Moss** — revealed with a circular View Transition from the button. |
| **Motion** | Counter loader, word-by-word headline, clip-reveal portrait, magnetic buttons, cursor-following project preview, marquee, accordion. |
| **Accessible** | Respects `prefers-reduced-motion`, semantic landmarks, keyboard friendly, readable contrast in every theme. |
| **SEO** | Bilingual title/description, Open Graph, `Person` JSON-LD, canonical, `sitemap.xml`, `robots.txt`, Search Console verified. |
| **Zero dependencies** | One `index.html` (~49 KB). No framework, no build step. |

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="30" alt="💻"> How the 3D lines work

<table>
  <tr>
    <td width="46%"><img src="./assets/cat-calculating.gif" alt="Calculating…" width="100%"></td>
    <td>
      <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=1800&pause=600&color=8B8A83&vCenter=true&width=380&height=26&lines=projecting+38+rows+x+110+points...;camera.pitch+%3D+0.18+%2B+scroll+*+0.9;fill+below+%E2%86%92+hidden-line+removal;60+fps+%E2%9C%94" alt="calculating">
      <br><br>
      Every frame, <b>38 lines × 110 points</b> of a sine-noise terrain are rotated and projected with a tiny perspective camera — no WebGL, no library.
      <br><br>
      Scroll = camera <b>pitch</b> & forward travel · Mouse = <b>yaw</b> · Every 9th line takes the accent colour of the active theme.
    </td>
  </tr>
</table>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Artist%20Palette.png" width="30" alt="🎨"> Four backgrounds, one button

<p align="center"><img src="./assets/themes.jpg" alt="Ink, Paper, Blueprint and Moss themes" width="100%"></p>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Mobile%20Phone.png" width="30" alt="📱"> Screens

<table>
  <tr>
    <td width="50%"><img src="./assets/hero-fa.jpg" alt="Persian RTL version"><p align="center"><sub>Persian · RTL</sub></p></td>
    <td width="50%"><img src="./assets/work.jpg" alt="Work list with hover preview"><p align="center"><sub>Work · preview follows the cursor</sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/services.jpg" alt="Services accordion"><p align="center"><sub>Services · accordion</sub></p></td>
    <td width="50%"><img src="./assets/contact.jpg" alt="Contact section"><p align="center"><sub>Contact</sub></p></td>
  </tr>
</table>

<p align="center"><img src="./assets/mobile.jpg" alt="Mobile, English and Persian" width="70%"><br><sub>Mobile · EN / FA</sub></p>

<p align="center"><img src="./assets/wave.gif" width="60%" alt="wave"></p>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="30" alt="🛠"> Structure

```
zeroux-dev.github.io/
├── index.html      ← the whole site: HTML + CSS + JS + FA/EN texts
├── sitemap.xml     ← pages for Google
├── robots.txt
├── README.md
└── assets/         ← images used only by this README
```

Run locally: open `index.html`, or `python -m http.server` → `http://localhost:8000`.

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="30" alt="🚀"> Add a new project (English)

1. Open **`index.html`** on GitHub → ✏️ Edit.
2. <kbd>Ctrl</kbd>+<kbd>F</kbd> → `class="work"`.
3. Copy one full line starting with `<a class="item rv"` and paste it right below.
4. Change in your copy:

   ```html
   <a class="item rv" href="LINK-TO-PROJECT" target="_blank" rel="noopener"
      data-img="LINK-TO-A-SCREENSHOT.jpg">
     <span class="n mono mut">07 — TYPE · STACK</span>
     <h3>Project Name</h3>
     <span class="meta mut" data-i="w7">Short English description</span>
     …keep the rest (<span class="go">…</span><span class="thumb"></span>) as it is…
   </a>
   ```
5. Translations: search `'w6':` — it appears in `en:{…}` and `fa:{…}`. Add `'w7':'English text',` and `'w7':'متن فارسی',`.
6. **Commit changes** → the site updates in ~1 minute.

> [!TIP]
> For `data-img`, put a screenshot in the project's repo and use its raw link:
> `https://raw.githubusercontent.com/zeroux-dev/REPO/main/screenshots/home.jpg` (1600×1000 JPG, under 300 KB).

<div dir="rtl">

## آموزش اضافه کردن پروژه (فارسی)

1. در گیت‌هاب فایل **`index.html`** را باز کن و روی مداد ✏️ بزن.
2. با <kbd>Ctrl</kbd>+<kbd>F</kbd> عبارت `class="work"` را پیدا کن.
3. یکی از خط‌هایی که با `<a class="item rv"` شروع می‌شود را کامل کپی کن و زیرش بچسبان.
4. در خط جدید این‌ها را عوض کن:
   - `href` ← لینک سایت یا دموی پروژه
   - `data-img` ← لینک عکس پروژه (با بردن موس روی پروژه نمایش داده می‌شود)
   - `07 — …` ← شماره و نوع پروژه
   - داخل `<h3>` ← اسم پروژه
   - `data-i="w7"` ← یک کلید جدید (w7، w8، …)
5. ترجمه‌ها: عبارت `'w6':` را جستجو کن؛ دو جا پیدا می‌شود (بخش `en` و بخش `fa`). کنار هرکدام اضافه کن: `'w7':'English text',` و `'w7':'متن فارسی',`
6. **Commit changes** را بزن؛ حدود ۱ دقیقه بعد سایت آپدیت می‌شود.

**عوض کردن متن‌ها:** همه‌ی متن‌های فارسی و انگلیسی داخل `index.html` در بخش `const T={ en:{…}, fa:{…} }` هستند. فقط متن داخل کوتیشن را عوض کن و کلیدها را دست نزن.

**عکس پروفایل:** از عکس پروفایل گیت‌هاب خوانده می‌شود؛ عکس گیت‌هاب را عوض کنی، سایت هم عوض می‌شود.

</div>

<img src="./assets/divider.svg" width="100%">

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Hot%20Beverage.png" width="30" alt="☕"> Status

<table>
  <tr>
    <td width="52%"><img src="./assets/cat-coffee.gif" alt="Everything is on fire, the site is fine" width="100%"></td>
    <td>
      <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2000&pause=700&color=3DDC84&vCenter=true&width=380&height=26&lines=%E2%9C%94+site%3A+online;%E2%9C%94+deploy%3A+GitHub+Pages;%E2%9C%94+coffee%3A+refilled;%E2%9A%A0+deadlines%3A+falling+from+the+sky" alt="status">
      <br><br>
      Client asks for a “small change” at 2 AM?<br>
      <b>Me, calmly shipping it.</b>
      <br><br>
      <a href="https://t.me/fesqhli"><img src="https://img.shields.io/badge/Start_a_project-@fesqhli-ff5b24?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0d0d0c" alt="Start a project"></a>
    </td>
  </tr>
</table>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Smiling%20Face%20with%20Sunglasses.png" width="30" alt="😎"> Author

<table>
  <tr>
    <td width="120"><img src="https://avatars.githubusercontent.com/zeroux-dev?s=200" width="110" alt="Sobhan (ZERO)"></td>
    <td>
      <b>ZERO — Sobhan</b><br>
      UI/UX · Web · WordPress · SEO · Telegram bots & mini apps · Python/Flask · Unity<br><br>
      <a href="https://zeroux-dev.github.io/">Website</a> ·
      <a href="https://t.me/fesqhli">Telegram @fesqhli</a> ·
      <a href="https://github.com/zeroux-dev">GitHub</a> ·
      <a href="https://github.com/zeroux-dev/flask-tech-blog">Flask project</a>
    </td>
    <td width="150" align="right"><a href="https://t.me/fesqhli"><img src="./assets/sticker.svg" width="130" alt="Open for work"></a></td>
  </tr>
</table>

<p align="center"><img src="./assets/wave.gif" width="100%" alt="wave"></p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1200&color=8B8A83&center=true&vCenter=true&width=520&height=24&lines=Designed+%26+coded+by+ZERO+%E2%80%94+thanks+for+scrolling+this+far" alt="outro">
</p>

<sub>© 2026 ZERO (Sobhan). Design and code of this site are not open for reuse — please don't copy it as your own portfolio. Want something like it? Message <a href="https://t.me/fesqhli">@fesqhli</a>.</sub>
