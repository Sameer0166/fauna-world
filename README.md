<div align="center">

# 🐟 Fauna & Seafood World
### 225-Species Dual Visual & Audio Encyclopedia

[![Live Demo](https://img.shields.io/badge/Live_Demo-Launch_App-0d7377?style=for-the-badge&logo=githubpages&logoColor=white)](https://sameer0166.github.io/fauna-world/)
[![Companion App](https://img.shields.io/badge/Companion_App-Botanica_World-166534?style=for-the-badge&logo=leaflet&logoColor=white)](https://sameer0166.github.io/botanica-world/)
[![Zero Dependencies](https://img.shields.io/badge/Stack-HTML5_%7C_CSS3_%7C_Vanilla_JS-0f2942?style=for-the-badge)](#tech-stack)

An interactive visual and audio encyclopedia cataloging **225 global edible animal, poultry, fish, and seafood species** through **450 paired real-world photographs**, multilingual regional names, audio pronunciation, printable study sheets, and a certificate-awarding quiz arena.

</div>

---

## 📖 Overview

Students often struggle to connect a living organism in nature with its culinary form in kitchens and markets. **Fauna & Seafood World** solves this by placing **two paired visuals side by side** on every card—the **Living Animal / Whole Species** on the left and its **Edible Flesh / Meat Cut / Yolk** on the right—backed by nutrition highlights, spelling breakdowns, and interactive self-testing tools.

---

## 🗂️ Encyclopedia Coverage (225 Species)

| Category | Count | What's Inside |
| :--- | :---: | :--- |
| 🥚 **Eggs & Roe** | **20** | Domestic poultry eggs, ratite eggs, preserved delicacies, and marine caviar/roe |
| 🍗 **Poultry & Birds** | **26** | Chicken breeds & cuts, waterfowl, upland game birds, and lean ratite steaks |
| 🥩 **Red Meat, Game & Offal** | **38** | Goat, sheep, cattle, swine, regional game meats, and nutrient-dense offal |
| 🐟 **Freshwater & Marine Fish** | **78** | South Asian river carp/catfish, global freshwater fish, oily pelagic fish, and reef species |
| 🦐 **Seafood & Shellfish** | **53** | Shrimp, prawns, crabs, lobsters, oysters, mussels, clams, squid, and octopus |
| 🌍 **Global Specialties** | **10** | Traditional land snails, amphibians, reptiles, and FAO-recognized edible insects |

---

## ✨ Core Features

### 🖼️ Dual Visual System (450 Paired Images)
- **Side-by-Side Comparison:** View the living creature or whole shell next to its fillet, cut, or interior yolk.
- **Instant Visual Toggle:** Switch between **Real Dual Photos** (fetched lazily with URL deduplication) and **Zoological & Cut SVG Diagrams**.

### 🎧 Interactive Study & Memory Aids
- **Slow & Fast Audio Pronunciation:** Built-in Web Speech synthesis (`🐢 Slow` / `⚡ Fast`) on every card and modal.
- **Student Mode:** Simplifies scientific taxonomy and technical culinary terms into student-friendly summaries.
- **Memory Hide:** Blurs species names across the grid so learners can practice active-recall flashcards on hover.
- **Spelling & Cue Cards:** Click any card to inspect letter-by-letter spelling tiles, English/Hindi/Spanish names, native habitats, and nutrition superpowers.
- **Progress Tracking:** Bookmark items to a **Revision List** and mark **Mastered Cards** persistently via `localStorage`.

### 🎯 6-Mode Quiz Arena & Certificate Export
- **6 Challenge Modes:** *Animal & Cut Detective*, *Listen & Spell*, *Kitchen & World Uses*, *Nutrition Superpower*, *Habitat Geography*, and *Grand Champion Mix*.
- **Instant Credential Generation:** Scoring **70% or higher** generates a custom `1200×850` HTML5 Canvas certificate with **1-click PNG download** and **landscape PDF/print export**.

### 🖨️ Offline Printable Study Sheets
- Dedicated `@media print` stylesheet formats the active filter view into a clean **2-column PDF study guide** with page-break protection and zero UI clutter.

---

## 🛠️ Tech Stack

- **Core:** Semantic HTML5, Modern CSS3 (CSS Grid, Flexbox, `@media print`), Vanilla ES6+ JavaScript
- **Browser & Data APIs:** Wikipedia REST API, Wikimedia Commons MediaWiki API, Web Speech Synthesis API, HTML5 Canvas API, `IntersectionObserver`, and `localStorage`
- **Deployment:** Static single-file architecture hosted on GitHub Pages (zero build tools or external dependencies)

---

## 👨‍💻 Author

**Mohd Sameer Pasha**  
- GitHub: [@Sameer0166](https://github.com/Sameer0166)  
- LinkedIn: [Mohd Sameer Pasha](https://www.linkedin.com/in/mohd-sameer-pasha-987785363)
