# Dico.Informatique

**🔗 Live demo: [sarah-assous.github.io/Dico-Informatique](https://sarah-assous.github.io/Dico-Informatique/)**

An interactive **glossary of computer science and tech vocabulary, in French, English and Hebrew**: 278 terms in 15 themes, from programming languages and databases to cloud, cybersecurity, AI and job-search vocabulary.

I created it as a personal project to help people entering the Israeli tech industry (including me!) understand the words they hear in job interviews and at work, in their own language. Each term comes with a simple definition, a real-life example and, when useful, a tip for interviews.

## ✨ Features
- **Three languages: French, English and Hebrew**, with a full right-to-left (RTL) layout in Hebrew. On the first visit, the user picks their language on a welcome screen; the choice is remembered for the next visit, can be changed at any time with the FR / EN / HE buttons, and can also be set in the link (`?lang=en`, `?lang=he`, `?lang=fr`)
- **Instant search** while typing, accent-insensitive (`donnees` finds `données`)
- **Highlighting** of the searched words in the results
- **Smart sorting**: terms whose name matches the search appear first
- **Theme filters** (web, languages, databases, cloud & DevOps, networks, cybersecurity, AI…)
- **Light and dark mode**, following the system setting
- Responsive design, works on mobile

## 🛠️ Built with
- **HTML5**, **CSS3** (custom properties, flexbox, sticky header, media queries)
- **Vanilla JavaScript** (no framework): DOM rendering, event handling, text normalization with `String.normalize`, filtering and sorting
- Internationalization (i18n) with a single data object per language and dynamic `lang` / `dir` attributes
- CSS logical properties so the same stylesheet works left-to-right and right-to-left
- Hosted with **GitHub Pages**

The page is a single `index.html` file, with the glossary data for each language stored as JavaScript objects.

> This project was built with the help of AI tools, which I used to speed up development and to help translate and review the definitions.

## ▶️ Run locally
Just open `index.html` in any web browser.

---

👩‍💻 **Sarah Assous** – Computer Science student
[LinkedIn](https://www.linkedin.com/in/sarah-assous)
