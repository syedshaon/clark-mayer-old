# 🌐 Clark Moyer Static Website (Plain HTML Version)

This repository contains a fully static version of the **Clark Moyer** website --- built using **only HTML, CSS, and JavaScript**, with no build tools or frameworks.

It's a simplified version of the previous Vite-powered site, ideal for easy deployment and hosting on **GitHub Pages**, **Netlify**, or any static web server.

---

## 🚀 Features

- 100% static -- no Vite or bundlers required

- Uses plain HTML, CSS, and JavaScript

- Optimized for fast loading and SEO

- Fully responsive layout

- Clean, readable code structure

- All shared components (header, footer, etc.) are manually included in each page

---

## ⚙️ How to Use

1.  **Clone this repository**

    `git clone https://github.com/syedshaon/clark-moyer-static.git`

2.  **Open `index.html` in your browser**\
    No setup or build steps required.

3.  **To deploy on GitHub Pages:**

    - Go to your repo's settings → Pages

    - Select the `main` branch and `/ (root)` folder

    - Click **Save**

    - Your site will be live at `https://yourusername.github.io/repo-name/`

---

## 🌍 Setting Up a Custom Domain

1.  Purchase or use your existing domain.

2.  Add a `CNAME` file in the root of this repo with your domain name:

    `www.clarkemoyer.com`

3.  In your domain DNS settings, create a CNAME record pointing to:

    `yourusername.github.io`

---

## 🗺️ Updating the Sitemap

After adding a new domain or page:

1.  Go to [xml-sitemaps.com](https://www.xml-sitemaps.com/)

2.  Generate a new sitemap using your **current domain** (e.g., <https://www.clarkemoyer.com>)

3.  Download the XML file and replace the existing `sitemap.xml` in this repo.

---

## 💬 Notes

- This version is ideal if you want a lightweight, easily maintainable site.

- If you ever want to use templating or partials again, you can switch back to the [Vite version](https://github.com/syedshaon/clark-mayer) of the project.

---

## 👨‍💻 Author

**Developed by [Syed Shaon](https://github.com/syedshaon)**\
If you need help customizing, deploying, or adding new features, feel free to reach out.
