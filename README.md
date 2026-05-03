# Milner-and-Paul-Legal-Practitioner
# Milner & Paul Legal Practitioners

Official website for **Milner & Paul Legal Practitioners** — a full-service law firm based in Lusaka, Zambia.

Live site built with pure HTML, CSS, and JavaScript. No frameworks. No dependencies. Upload and deploy anywhere.

---

## 🌐 Live Preview

> 
--[-](https://apexscale-studio.github.io/Milner-and-Paul-Legal-Practitioners/)

## 📁 Project Structure

```
milner-and-paul/
│
├── index.html          # Main HTML — all page structure and content
│
├── css/
│   └── style.css       # All styling, layout, animations, responsive design
│
├── js/
│   └── main.js         # All JavaScript — navigation, WhatsApp, call modal, timer
│
└── images/
    ├── logo.png
    ├── Charles-Banda.jpg
    ├── david-mwansa.jpg
    ├── emmanuel-phiri.jpg
    ├── grace-mutale.jpg
    ├── patricia-banda.jpg
    ├── chisomo-tembo.jpg
    ├── naledi-zulu.jpg
    ├── legal-consultation.jpg
    ├── scales-gavel.jpg
    ├── courtroom.jpg
    ├── family-law.jpg
    ├── medical-negligence.jpg
    ├── corporate-law.jpg
    └── document-signing.jpg
```

---

## ✨ Features

- **WhatsApp-first contact** — every CTA opens a pre-filled WhatsApp message directly to the firm
- **8 Practice Areas** — Case Analysis, Case Studies, Commercial Law, Commercial Transactions, Corporate Advisory & Litigation, Court Litigation, Dispute Resolution, Notaries Public
- **Meet the Team** — 7 lawyer profiles with photos, titles, specialities, and individual WhatsApp enquiry buttons
- **Why Us section** — side-by-side comparison vs other firms with 6 reason cards
- **Urgency trigger** — live countdown timer + free consultation slot counter
- **Call modal** — tap-to-call popup that works in all browsers including sandboxed WebViews
- **Google Maps** — exact office pin at Ntemwa House, Sianjalika Road, Lusaka
- **Fully responsive** — mobile, tablet, and desktop
- **Smooth scroll navigation** — JavaScript-powered, works in all environments
- **Scroll animations** — elements animate in as the user scrolls
- **Active nav highlighting** — current section highlighted automatically
- **Zero dependencies** — no npm, no frameworks, no build step required

---

## 🚀 Deployment

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder `/`
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Netlify (Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Click **Add new site → Deploy manually**
3. Drag and drop the project folder
4. Done — live in seconds

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import the GitHub repo
3. No configuration needed — deploys automatically

### cPanel / Traditional Hosting
1. Upload all files into `public_html`
2. Maintain the folder structure exactly as shown above
3. Access via your domain

---

## ✏️ How to Update Content

### Change phone number
Search for `+260775690659` in `index.html` and `main.js` and replace with the new number.

### Change WhatsApp number
Search for `wa.me/260775690659` in `main.js` and replace with the new number (no `+` sign).

### Update a lawyer's name or speciality
Open `index.html` and find the **Meet the Team** section. Each lawyer card looks like this:

```html
<div class="team-name">Name Here</div>
<div class="team-title">Title Here</div>
<div class="team-spec">Speciality Here</div>
```

### Update office address
Search for `Ntemwa House` in `index.html` — appears in the Location and Contact sections.

### Add or remove a practice area
Find the `practice-grid` div in `index.html`. Each service card follows this structure:

```html
<div class="practice-card anim-el" onclick="waEnquire('Service Name')">
  <img src="images/your-image.jpg" alt="Service Name" class="practice-card-img">
  <div class="practice-num">01</div>
  <div class="practice-title">Service Name</div>
  <div class="practice-desc">Description here.</div>
  <button class="practice-wa-btn">💬 Enquire on WhatsApp</button>
</div>
```

### Swap a team photo
Replace the image file in the `images/` folder with the same filename, or update the `src` attribute in the relevant team card in `index.html`.

---

## 📞 Contact Details

| | |
|---|---|
| **Phone** | +260 775 690 659 |
| **WhatsApp** | +260 775 690 659 |
| **Office** | Ntemwa House, Stand No. 2993, Sianjalika Road, Off Mwapona Rd, Lusaka 10101, Zambia |
| **Hours** | Mon–Fri 08:00–17:30 · Sat 09:00–13:00 |

---

## 🛠 Built With

- HTML5
- CSS3 (custom properties, grid, flexbox, animations)
- Vanilla JavaScript (ES5 compatible)
- Google Fonts (Playfair Display, Cormorant Garamond, Montserrat)
- Google Maps Embed API

---

## 📄 License

This website was built for **Milner & Paul Legal Practitioners**. All rights reserved. Not for redistribution or reuse without written permission.

---

*Built by [TOMMY LUNGU/ APEXSCALE-STUDIO] — Zambian Web Developer*
*For web development enquiries, reach out on WhatsApp: [+260775690659]*
