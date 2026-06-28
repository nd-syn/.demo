# IT LIFE SOLUTION — Flagship Demo Website

A production-grade, static, light-themed demo website for **IT Life Solution** — Kolkata's PC shop for parts, builds, repairs, and laptops.

## ✨ Highlights

- **4 fully designed pages**: Home (Landing + Main), Shop, Services, About, Contact
- **Light theme** with flagship-grade UI/UX — Inter + Space Grotesk + JetBrains Mono fonts
- **Lucide Icons** for crisp, scalable vector icons throughout
- **Responsive** across mobile / tablet / desktop
- **Pure HTML/CSS/JS** — zero build step, zero dependencies
- **Static** — drop-in ready for GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.
- **Working contact form** with friendly success state (UI demo — no backend)
- **Embedded Google Map** with the shop's exact address
- **Smooth scroll-reveal animations**, animated stat counters, animated marquee, animated hero PC case fans
- **Genuine product UI** with categories, badges, pricing, tabs — designed to convince the shop owner instantly

## 📁 Structure

```
.
├── index.html              # Landing + main page (hero, services, builds, testimonials, CTA)
├── pages/
│   ├── about.html          # Story, values, journey, team, FAQ
│   ├── contact.html        # Form, info card, hours, map, FAQ
│   ├── services.html       # 9 detailed services + 3 build packages
│   └── shop.html           # Categories + bestsellers with tabs
├── assets/
│   ├── css/styles.css      # Full flagship design system (light theme)
│   └── js/site.js          # Interactions: menu, tabs, counters, reveal, form
└── README.md
```

## 🚀 Deploy on GitHub Pages

1. Push this folder to a new GitHub repository.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", choose **Deploy from a branch**.
4. Select `main` branch and `/ (root)` folder, then **Save**.
5. After ~1 minute, the site will be live at `https://<your-username>.github.io/<repo-name>/`.

## 🛍️ Customising for the Real Shop

- **Replace placeholder prices** with real numbers in the product cards.
- **Swap the WhatsApp link** `https://wa.me/916289898238` to the shop's actual WhatsApp number.
- **Wire the contact form** to a service like [Formspree](https://formspree.io/), [Getform](https://getform.io/) or a Google Form by changing the `data-contact-form` handler in `assets/js/site.js`.
- **Replace the map embed** with a Google Maps embed of the actual pinned location (already pre-pointed to the shop's address).
- **Add real photos** of the shop, team and builds to the `assets/img` folder.

## 📞 Contact (in the demo)

- **Shop Name:** IT Life Solution
- **Phone:** 06289898238
- **Address:** Ground Floor, 23, Chittaranjan Ave, Esplanade, Chowringhee North, Bow Barracks, Kolkata, West Bengal 700072

---

_Crafted as a sales-ready demo for client pitch. Light theme, production-grade layout, mobile-first._
