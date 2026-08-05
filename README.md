# SolaimanLipi Font CDN



[![License: OFL 1.1](https://img.shields.io/badge/License-OFL%201.1-blue.svg)](https://scripts.sil.org/OFL)

[![jsDelivr](https://data.jsdelivr.com/v1/package/gh/qnabangla/font-solaimanlipi/badge)](https://www.jsdelivr.com/package/gh/qnabangla/font-solaimanlipi)



This repository provides a fast and reliable **jsDelivr CDN** for the **SolaimanLipi** web font.



> **Disclaimer**

>

> I do **not** own this font. **SolaimanLipi** is a free and open-source Bangla font. This repository simply hosts the web font files (WOFF2, WOFF, TTF, EOT, and SVG) and provides an easy-to-use CDN for developers to embed the font into websites and web applications.



---



# 📖 About the Font



**SolaimanLipi** is one of the most popular Unicode Bangla fonts designed by **Solaiman Karim** in **2003**. It was originally developed as part of the **Ekushey Project** and later maintained by **Altruists International**.



The font fully supports the Bengali Unicode block (**U+0980–U+09FF**) and is widely used in websites, blogs, digital publishing, government documents, and educational platforms.



## Preview



> আমি বাংলায় মাতি উল্লাসে,  

> করি বাংলায় হাহাকার।  

> আমি সব দেখে শুনে ক্ষেপে গিয়ে—  

> করি বাংলায় চিৎকার।



---



# 🚀 How to Use



## Option 1 — CSS `@import`



Add the following line to your CSS file.



```css

@import url("https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/font.css");

```



---



## Option 2 — HTML `<link>` (Recommended)



Include the following inside the `<head>` section.



```html

<!-- Preload Font -->

<link

    rel="preload"

    href="https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2"

    as="font"

    type="font/woff2"

    crossorigin

>



<!-- Load CSS -->

<link

    rel="stylesheet"

    href="https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/font.css"

>

```



---



## Option 3 — CSS `@font-face`



```css

@font-face {

    font-family: "SolaimanLipi";

    src:

        url("https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2") format("woff2"),

        url("https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff") format("woff"),

        url("https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.ttf") format("truetype");

    font-style: normal;

    font-weight: 400;

    font-display: swap;

}

```



---



## Apply the Font



```css

body {

    font-family: "SolaimanLipi", sans-serif;

}

```



Example:



```html

<h1>বাংলা শিরোনাম</h1>



<p>

বাংলা ভাষা পৃথিবীর অন্যতম সমৃদ্ধ ভাষা।

</p>

```



---



# 📁 Repository Structure



```

.

├── SolaimanLipi.woff2

├── SolaimanLipi.woff

├── SolaimanLipi.ttf

├── SolaimanLipi.eot

├── SolaimanLipi.svg

├── font.css

├── LICENSE

└── README.md

```



---



# ℹ️ Font Information



| Property | Value |
|----------|-------|
| Font Name | SolaimanLipi |
| Style | Regular |
| Version | 2.002 |
| Release Date | February 19, 2021 |
| Designer | Solaiman Karim |
| Developer | Al Mamun Hossen |
| Unicode Support | Bengali (U+0980–U+09FF) |
| License | SIL Open Font License 1.1 |

---

# ✨ Features
- ✅ WOFF2
- ✅ WOFF
- ✅ TrueType (TTF)
- ✅ Embedded OpenType (EOT)
- ✅ SVG Font
- ✅ Unicode compliant
- ✅ Lightweight CDN delivery
- ✅ Fast loading via jsDelivr
- ✅ `font-display: swap`
- ✅ Works in all modern browsers
---



# 🌐 CDN URL



WOFF2



```

https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff2

```



WOFF



```

https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.woff

```



TTF



```

https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.ttf

```



EOT



```

https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.eot

```



SVG



```

https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/SolaimanLipi.svg

```



CSS



```

https://cdn.jsdelivr.net/gh/qnabangla/font-solaimanlipi@main/font.css

```



---



# 💡 Browser Support



- Google Chrome

- Mozilla Firefox

- Microsoft Edge

- Safari

- Opera

- Brave

- Vivaldi

- Android Browser

- iOS Safari



---



# ❤️ Acknowledgements



Special thanks to:



- **Solaiman Karim** for designing the original SolaimanLipi font.

- **Altruists International** for maintaining and distributing the font.

- **jsDelivr** for providing the free global CDN.



---



# 📄 License



This Font Software is licensed under the **SIL Open Font License, Version 1.1 (OFL-1.1)**.



You are free to use, modify, and redistribute the font under the terms of the license.



https://openfontlicense.org/



---



# ⚠️ Disclaimer



This repository is **not affiliated with** or officially maintained by the original font author.

It only provides CDN-hosted web font files to simplify integration into websites and web applications.

All rights belong to their respective owners.



---

# ⭐ Support

If you find this repository useful, consider giving it a **⭐ Star** on GitHub.



It helps other developers discover the project.
