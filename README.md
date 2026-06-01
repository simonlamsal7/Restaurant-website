# Restaurant-website
A responsive website built with HTML, CSS, and JavaScript featuring online menu browsing, cart functionality, customer reviews, event services, and contact forms
# 🍛 Maila Dai Ko Mitho Biriyani — Restaurant Website

> **A fully responsive, professional restaurant website built with pure HTML, CSS & JavaScript.**  
> Features a dark luxury design, working cart system, menu filtering, and complete login/signup authentication.

---

## 🌐 Live Preview

> Open `index.html` in your browser to view the website locally.

---

## ✨ Features

### 🏠 Homepage (`index.html`)
- Animated **hero section** with background image and smooth fade-in
- **Statistics bar** — Years, Customers, Rating
- Scrolling **marquee ticker** bar
- **Services section** with hover animations (6 service cards)
- **Menu section** with category filter buttons (All / Biriyani / Chicken / Pizza)
- **Shopping cart** — floating cart button, add/remove items, live total, place order
- **Partners section** — Foodmandu, Pathao, eSewa, Khalti, Fonepay
- **Customer reviews** section with featured card
- **Contact section** with working form and validation
- **Footer** with quick links, social media, and sitemap

### 🔐 Authentication
- **Login page** (`login.html`) — validates email/password, checks saved accounts, redirects on success
- **Signup page** (`signup.html`) — full registration form with password strength meter, terms agreement, and account saving
- Customer data saved using **browser localStorage** — fully functional without a backend

### 🎨 Design Highlights
- Dark luxury theme with **gold (`#D4A017`) accents**
- **Playfair Display** (serif display font) + **Outfit** (clean body font)
- Smooth scroll-triggered **fade-in animations** on all cards
- Fully **mobile responsive** with hamburger navigation
- Custom **gold scrollbar**, toast notifications, and back-to-top button

---

## 📁 File Structure

```
maila-biriyani/
│
├── index.html          ← Main homepage
├── style.css           ← All styling (variables, layout, components)
├── script.js           ← Cart, filters, animations, contact form
├── login.html          ← Login page with validation
├── signup.html         ← Sign up page with strength meter
│
├── food.jpg            ← Hero background image
├── biriyani.jpg        ← Menu card image
├── chicken.jpg         ← Menu card image
├── pizza.jpg           ← Menu card image
├── green chicken.jpg
├── logo.png
├── delivery.jpg
├── catering.jpg
├── reservation.jpg
├── liquior.jpg
├── fruit1.jpg          ← Partners section background
│
├── foodmandu.png       ← Partner logos
├── pathao.png
├── esewa.png
├── khalti.png
└── fonepay.png
```

> ⚠️ **Note:** Make sure all images are placed in the **same folder** as the HTML files. If an image is missing, the site gracefully falls back to a placeholder.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/maila-biriyani-website.git
cd maila-biriyani-website
```

### 2. Add your images

Place all your image files (`.jpg`, `.png`) inside the project folder. Refer to the file structure above for the full list of expected image names.

### 3. Open in browser

Simply open `index.html` in any modern web browser:

```bash
# On Windows
start index.html

# On Mac
open index.html
```

No server, no installation, no dependencies needed. ✅

---

## 🛒 How the Cart Works

1. Click **"Add"** on any menu card — the item is added to your cart
2. A floating 🛒 button shows the item count
3. Click the cart button to open the panel — view items, quantities, and total
4. Click **"Place Order"** to submit — a confirmation toast appears
5. Cart resets after ordering

---

## 🔐 How Login & Signup Works

- When a user **signs up**, their details are saved in the browser's `localStorage`
- When they **log in**, the site checks saved accounts and validates credentials
- On success, the user is redirected to the homepage
- No backend or database required — perfect for a front-end only project

> 💡 To add real backend authentication later, connect Firebase Auth or a custom REST API.

---

## 🧰 Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content |
| CSS3 | Styling, animations, responsive layout |
| JavaScript (ES6) | Cart logic, filtering, form validation, localStorage |
| Google Fonts | Playfair Display + Outfit fonts |
| Font Awesome 6 | Icons throughout the site |

**No frameworks. No libraries. No build tools.** Pure vanilla web development.

---

## 📱 Responsive Design

| Device | Breakpoint | Layout |
|---|---|---|
| Desktop | 1024px+ | Full multi-column layout |
| Tablet | 768px–1024px | Adjusted grid, 2-column footer |
| Mobile | Below 768px | Single column, hamburger menu |

---

## 🎨 Color Palette

| Name | Hex | Usage |
|---|---|---|
| Gold | `#D4A017` | Buttons, accents, headings |
| Gold Light | `#F5C842` | Hover states |
| Dark Base | `#0D0D0D` | Page background |
| Card Background | `#181818` | Cards |
| Text Muted | `#A89880` | Secondary text |

---

## 🙌 Credits

Designed and developed by **Simon Lamsal**  
Restaurant: **Maila Dai Ko Mitho Biriyani**, Kathmandu, Nepal

[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=flat&logo=Facebook&logoColor=white)](https://www.facebook.com/simon.lamsal.58/)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=flat&logo=Instagram&logoColor=white)](https://www.instagram.com/sea_monnn7/)
[![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?style=flat&logo=TikTok&logoColor=white)](https://www.tiktok.com/@simonlamsal3)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-lamsal-b31285344)

---

## 📄 License

This project is open source.

---

> © 2026 Maila Dai Ko Mitho Biriyani | All Rights Reserved | Made with ❤️ in Kathmandu, Nepal
