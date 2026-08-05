# SolaimanLipi Font CDN

[![License: OFL 1.1](https://img.shields.io/badge/License-OFL%201.1-blue.svg)](https://scripts.sil.org/OFL)

This repository provides a fast, reliable [jsDelivr](https://www.jsdelivr.com/) CDN link for the **SolaimanLipi** web font. 

> **Disclaimer:** I do not own this font. SolaimanLipi is a free, open-source font. This repository was created simply to host the web font files (WOFF2, WOFF, TTF, EOT, SVG) and provide a direct CDN link for developers to easily embed it into their web projects.

---

## 📖 About the Font

**SolaimanLipi** is a widely used, Unicode-compliant Bangla font designed by **Solaiman Karim** in 2003. It was developed as part of the [Ekushey project](https://ekushey.org/) and is redistributed by Altruists International. The font supports the complete Bengali Unicode range (U+0980-U+09FF).

### Preview
> আমি বাংলায় মাতি উল্লাসে,  
> করি বাংলায় হাহাকার  
> আমি সব দেখে শুনে ক্ষেপে গিয়ে-  
> করি বাংলায় চিৎকার।

---

## 🚀 How to Use (CDN)

You can easily embed this font into your website using the direct GitHub CDN raw link provided by jsDelivr. 

### 1. Embed via HTML `<link>` (Recommended for Preloading)
Add the following code inside the `<head>` tag of your HTML document to preload and load the font efficiently:

```html
<!--[ Solaimanlipi fonts ]-->
<link as='font' crossorigin='anonymous' href='[https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2](https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2)' rel='preload' type='font/woff2'/>

<link as='style' href='[https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2](https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2)' onload='this.onload=null; this.rel="stylesheet"; document.body.classList.add("fontLoaded")' rel='preload'/>
