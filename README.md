# SPITZ Official Website

This repository contains the official static landing page for **SPITZ** — representing leading European brands in professional hand tools, combining engineering precision, innovation, and uncompromising quality.

---

## 📄 Overview

The website is a single-page static site built with **HTML5** and **CSS3**, designed for deployment via **GitHub Pages**.  
It features a minimal and responsive layout, optimized for fast loading and clear presentation of the brand identity.

---

## 🧱 Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # Core styling and layout
├── assets/             # Static assets (logo, favicon, world map)
│   ├── spitz-logo-red.png
│   ├── spitz-favicon-red.png
│   └── spitz-world-map-red.png
└── README.md           # Documentation (this file)
```

---

## 🎨 Design Specifications

- **Primary Color:** `#E4312A`  
- **Typography:** Montserrat (Bold for titles, Regular for text)  
- **Layout:** Centered logo, clean white header and footer  
- **Background:** Subtle world map graphic with 10% opacity  
- **Call to Action:** Rectangular red button linking to the company’s contact email

---

## ⚙️ Deployment (GitHub Pages)

1. Push the contents of this repository to your GitHub account.  
2. Go to **Settings → Pages**.  
3. Under “Build and deployment”, select:
   - **Source:** Deploy from branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`  
4. Save changes — your site will be available at:  
   `https://<username>.github.io/<repository-name>/`

---

## 🌐 Custom Domain (Optional)

To connect a custom domain:
1. Create a file named `CNAME` in the root directory.  
2. Add your domain inside, e.g.:
   ```
   www.spitz-tools.com
   ```
3. Update your DNS records as follows:
   - **A records** → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`  
   - **CNAME** → `<username>.github.io`

GitHub Pages will automatically issue an HTTPS certificate once propagation is complete.

---

## 📧 Contact

For partnership inquiries or distribution opportunities, contact:  
**📩 contact@example.com**

© 2025 SPITZ — European Engineering Excellence. All rights reserved.
