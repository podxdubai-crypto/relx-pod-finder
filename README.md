<div align="center">

# 🔍 RELX Pod Finder 🔍

### Find the right RELX pod for your device in seconds ⚡

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=620&lines=Pick+your+RELX+device;See+if+Pod+Pro+or+Pod+Pro+2+fits;Browse+compatible+pods+with+Dubai+prices)

[![Live Demo](https://img.shields.io/badge/Live_Demo-Open_Tool-00D4FF?style=for-the-badge&logo=netlify&logoColor=white)](https://relx-pod-compatibility.netlify.app)
[![Website](https://img.shields.io/badge/Store-podx.ae-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://podx.ae)
![HTML](https://img.shields.io/badge/Built_with-HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Netlify](https://img.shields.io/badge/Hosted_on-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

</div>

---

## 📖 About

**RELX Pod Finder** is a free, one-page RELX pod compatibility chart and pod finder built for [PodX](https://podx.ae), a Dubai-based retailer.

Choose your RELX device, see whether **RELX Pod Pro** and **Pod Pro 2** fit it, then browse every compatible pod in stock with Dubai prices.

👉 **Try it now:** [relx-pod-compatibility.netlify.app](https://relx-pod-compatibility.netlify.app)

---

## ✅ Compatibility at a Glance

| Device | RELX Pod Pro | RELX Pod Pro 2 |
|---|:---:|:---:|
| Infinity 2 | ✅ Fits | ✅ Fits |
| Infinity 2 Plus | ✅ Fits | ✅ Fits |
| Infinity | ✅ Fits | 🟢 Usually fits |
| Infinity Plus | ✅ Fits | 🟢 Usually fits |
| Essential | ✅ Fits | 🟢 Usually fits |
| Essential 2 | 🟡 Check your pack | 🟡 Check your pack |
| Artisan | ✅ Fits | ✅ Fits |
| Artisan Plus | ✅ Fits | 🟡 Check your pack |
| Classic | ❌ Doesn't fit | ❌ Doesn't fit |
| Creator / Creator Pro | ❌ Doesn't fit | ❌ Doesn't fit |
| ULTRA | 🟡 Check your pack | ❌ Doesn't fit |

🟢 **Usually fits:** some Pod Pro 2 packs are labeled for the Infinity 2 family only, so check that the pack lists your device.
🟡 **Check your pack:** not confirmed for this device. Check the pack, or [ask PodX on WhatsApp](https://wa.me/971541341884).

💡 On **Infinity 2** and **Infinity 2 Plus**, use **Pod Pro 2** to unlock the Eco, Smooth and Boost power modes.

👉 See the full interactive version, with every compatible pod and price, at [relx-pod-compatibility.netlify.app](https://relx-pod-compatibility.netlify.app).

---

## ✨ Features

- 📱 **Device picker:** choose your RELX device and get an instant compatibility verdict
- 🧩 **Compatibility chart:** see which pods fit which devices at a glance
- ⚖️ **Pod Pro vs Pod Pro 2:** a side-by-side comparison
- 💰 **Monthly cost calculator:** estimate what your pods cost per month
- 🛒 **Compatible pods in stock:** browse matching pods with Dubai prices
- ❓ **FAQ:** answers to common compatibility questions
- 🔌 **Embeddable chart:** drop the chart into any page with `?embed=chart`

---

## 🔌 Embed the Chart

Add the compatibility chart to your blog, forum or store page. It's free, and it updates itself whenever the chart changes:

```html
<iframe
  src="https://relx-pod-compatibility.netlify.app/?embed=chart"
  title="RELX pod compatibility chart"
  width="100%"
  height="820"
  loading="lazy"
  style="border:0;max-width:760px;"
></iframe>
<p>Source: <a href="https://relx-pod-compatibility.netlify.app/">RELX pod compatibility chart by PodX</a></p>
```

You can also copy this code from the **Add this chart to your site** box on the live page.

---

## 📁 Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles, and script |
| `robots.txt` | Crawl rules for search engines |
| `sitemap.xml` | Sitemap for search engines |
| `netlify.toml` | Netlify publish settings and headers |
| `favicon.svg` | Site icon |
| `.gitignore` | Files git should skip |

---

## 🛠️ Editing

All the data lives in the script at the top of `index.html`:

- **`CONFIG`**: prices, URLs, and the WhatsApp number
- **`DEVICES`**: devices and their compatibility verdicts

> ⚠️ The chart also appears as a static HTML table so search engines can read it without JavaScript. **Whenever you change a verdict in `DEVICES`, update that table too.**

After any content change, update `<lastmod>` in `sitemap.xml`.

---

## 💻 Run Locally

No build step and no dependencies. Serve the folder with any static server, for example:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). Add `?device=infinity-2` to open a device's result directly, or `?embed=chart` to see the embed view.

---

## 🚀 Deploy

The site is a static page hosted on Netlify, with no build command and `.` as the publish directory.

- **From GitHub:** once the repo is linked in Netlify (**Project configuration → Developer settings → Link repository**), every push to `main` goes live automatically.
- **From your computer:** run this in the repo folder:

```bash
netlify deploy --prod --dir .
```

---

## 🔎 SEO

- Canonical URL, Open Graph tags and JSON-LD structured data (`WebPage`, `WebApplication`, `FAQPage`)
- A static compatibility table and FAQ in the HTML, so crawlers can read them without JavaScript
- `robots.txt` and `sitemap.xml`, verified in Google Search Console

---

## 🌐 About PodX

[PodX](https://podx.ae) sells JUUL, RELX, and WAKA pods and devices from Business Bay, Dubai 🇦🇪

[![LinkedIn](https://img.shields.io/badge/LinkedIn-PodX-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/143870922/)
[![Mastodon](https://img.shields.io/badge/Mastodon-@podxdubai-6364FF?style=flat-square&logo=mastodon&logoColor=white)](https://mastodon.social/@podxdubai)
[![Medium](https://img.shields.io/badge/Medium-@podxdubai-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@podxdubai)
[![Linktree](https://img.shields.io/badge/Linktree-43E660?style=flat-square&logo=linktree&logoColor=white)](https://linktr.ee/podxdubai)

---

<div align="center">

⚠️ *For adult smokers and vapers only (18+). Nicotine is addictive.* ⚠️

<sub>RELX is a trademark of its owner. PodX is an independent store, and this chart is its own guide, not an official RELX document.</sub>

</div>
