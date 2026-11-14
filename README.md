# 🐟 Fauna & Seafood World — Global Dual-Visual & Audio Encyclopedia

An interactive, zero-dependency educational web application covering **225 human-edible animal, avian, freshwater, marine, shellfish, and global culinary species**. Designed for students, culinary learners, and nutrition enthusiasts, every card pairs two unique real-world photographs side by side: the **Living Animal / Whole Species** on the left and its **Edible Flesh / Meat Cut / Yolk** on the right.

🌐 **Live Website:** [https://sameer0166.github.io/fauna-world/](https://sameer0166.github.io/fauna-world/)  
🌱 **Companion Plant Encyclopedia:** [Botanica World (220 Edible Plants)](https://sameer0166.github.io/botanica-world/)

---

## ✨ Key Features

* **Side-by-Side Dual Visual Learning (450 Unique Images):** Every card displays both the living organism (or intact shell) and its culinary cut, fillet, or interior yolk with strict URL deduplication so no image repeats across the catalog.
* **225 Global Species Across 6 Major Categories:**
  * **Eggs & Roe (20):** Chicken, Duck, Quail, Turkey, Goose, Muscovy Duck, Guinea Fowl, Pheasant, Partridge, Ostrich, Emu, Rhea, Century Egg, Salted Duck Egg, Tea Egg, Ikura, Sturgeon Caviar, Tobiko, Masago, and Bottarga.
  * **Poultry & Game Birds (26):** Broiler, Country Chicken (Desi Murgh), Kadaknath, Silkie, Chicken Cuts, Capon, Domestic/Pekin/Muscovy/Mallard Ducks, Goose, Teal, Turkey, Quails, Guinea Fowl, Squab, Pheasant, Partridge, Grouse, Woodcock, Ostrich, Emu, and Rhea.
  * **Red Meat, Game & Offal (38):** Goat (Chevon & Boer), Lamb & Mutton Cuts, Fat-Tailed Sheep, Beef Cuts, Wagyu, Veal, Water Buffalo (Carabeef), Himalayan Yak, Bison, Pork Cuts & Cured Hams, Rabbit, Hare, Venison, Elk, Wild Boar, Reindeer, Kangaroo, Camel, and Nutrient-Dense Offal (Liver, Marrow, Kidney, Tripe, Tongue, Gizzard).
  * **Freshwater & Marine Fish (78):** 16 South Asian river fish (Rohu, Catla, Mrigal, Hilsa, Pabda, Magur, Singhi, Murrel/Korameenu, Karimeen, Koi, Mahseer, etc.), 16 global freshwater fish (Tilapia, Rainbow Trout, Basa, Carps, Catfish, Unagi, Zander, Pike, Perch, Arctic Char, Sturgeon, Bass, Walleye), 22 oily marine fish (Salmons, Mackerels, Surmai, Sardines, Tunas, Anchovy, Herring, Swordfish, Milkfish, Cobia, Pompano, Mullet), and 24 white marine/reef fish (Pomfrets, Bhetki, Branzino, Sea Bream, Snappers, Cods, Pollock, Haddock, Whiting, Hake, Mahi-Mahi, Halibut, Turbot, Dover Sole, Plaice, Groupers, Monkfish, John Dory, Croaker, Bombay Duck).
  * **Seafood & Shellfish (53):** 12 shrimps, prawns & crayfish, 14 crabs & lobsters, 15 bivalves (mussels, oysters, clams, scallops, cockles), and 12 cephalopods & marine invertebrates (squids, octopuses, cuttlefishes, abalone, conch, periwinkle, sea urchin, sea cucumber).
  * **Global Specialty & FAO Delicacies (10):** Escargot, Giant African Land Snail, Frog Legs, Alligator, Softshell Turtle, Silkworm Pupae (Beondegi/Eri), Chapulines, Roasted Crickets, Mopane Worms, and Sago Grubs.
* **Slow & Fast Audio Pronunciation:** Built-in Web Speech API pronunciation buttons (`🐢 Slow` and `⚡ Fast`) plus letter-by-letter spelling cue cards.
* **Multilingual & Nutritional Depth:** Includes English, Hindi, Spanish, and scientific binomial names, habitats, major producing regions, culinary uses, and key nutrition superpowers (Omega-3 EPA/DHA, Heme Iron, Zinc, Vitamin B12, Choline, Collagen).
* **Interactive Study Tools:**
  * **Student Mode:** Simplifies descriptions for younger learners.
  * **Memory Hide:** Blurs species names for self-testing.
  * **Revision List & Mastery Tracking:** Bookmark tricky species (`★`) and track mastered cards locally in the browser.
  * **Print Study Sheet:** Clean print stylesheet for offline classroom worksheets.
* **6-Mode Interactive Quiz Arena & Certificate:** Test visual recognition, audio spelling, kitchen uses, nutrition superpowers, and geography, unlocking a printable **Certificate of Zoological & Culinary Mastery** at 70% or higher.

---

## 🛠️ Tech Stack

* **Frontend:** Pure HTML5, CSS3 (CSS Grid, Custom Properties, Print Media Queries), and Vanilla ES6+ JavaScript (single-file architecture, zero build tools required).
* **Audio Engine:** Native browser `window.speechSynthesis` API.
* **Visual Data:** Wikipedia REST API & Wikimedia Commons Media API with intersection-observer lazy loading and offline SVG zoological fallback diagrams.

---

## 🚀 Running Locally

No installation or package manager is required:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Sameer0166/fauna-world.git](https://github.com/Sameer0166/fauna-world.git)
