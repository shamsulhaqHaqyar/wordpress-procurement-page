# Procurement Opportunities Page
> Fully branded procurement page for a live WordPress site, built with custom HTML/CSS and deployed via WPBakery.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![WPBakery](https://img.shields.io/badge/WPBakery-0073AA?style=flat-square&logo=wordpress&logoColor=white)

**Live:** [lapis-group.com/requests-for-prices](https://lapis-group.com/partner-with-us/) · **Status:** Production

---

## Overview

Built for a live organizational website to publish and manage procurement tender opportunities. The page allows qualified vendors to discover open Requests for Prices (RFPs), download TOR documents and price schedule templates, and submit offers via email — all in a clean, branded interface matching the organization's design system.

## Features

**Tender Cards**
- Four categorized tender cards (Media Buying, Creative Production, Printing, Event Management)
- Download buttons for TOR PDFs and Excel price schedules
- Service tags per category for quick scanning

**Hero Section**
- Branded hero with official color palette (`#00adee`)
- Submission deadline badge
- Fully responsive on desktop and mobile

**How to Submit Section**
- Step-by-step submission instructions
- One-click mailto CTA button

**Key Information Cards**
- Currency, partial offers policy, price validity, and deadline at a glance

## Tech Stack

**Frontend:** HTML5, CSS3  
**Fonts:** Montserrat (Google Fonts) — matched via Chrome DevTools  
**CMS:** WordPress (Salient/Nectar theme + WPBakery Page Builder)  
**Color Palette:** `#00adee` (official brand blue), extracted via Chrome DevTools  
**Deployment:** WPBakery Raw HTML block

## Challenges Solved

- Reverse-engineered exact brand font and colors using Chrome DevTools computed styles
- Resolved Salient/Nectar theme conflicts (transparent fixed header, injected page titles, breadcrumbs)
- Used page-specific CSS selectors (by post ID) to apply fixes without affecting other pages
- Handled WPBakery HTML sanitization by using Raw HTML block
- Fixed hero full-width stretch inside WordPress content container

## Deployment

- **Platform:** WordPress (Salient Theme + WPBakery)
- **Template:** Default template with per-page Nectar overrides
- **Additional CSS:** Scoped to page ID `7505` to avoid sitewide impact
- **Timeline:** Developed & Deployed March 2026

## Developer

**Shams Haqyar** — AI Engineer & Web Technologist

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/shams-haqyar-373020136/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/shamsulhaqHaqyar"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:shams.haqyar786@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://wa.me/93774189382"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="Footer" width="100%" />
</p>

---

**Note:** This is a showcase repository. Source code is proprietary and maintained privately.  
For custom implementations or consultations, connect via [LinkedIn](https://www.linkedin.com/in/shams-haqyar-373020136/).
