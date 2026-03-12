# 📚 Book Picker v2.0
**By AJ404Bit**

Book Picker is a sleek, modern Windows desktop application designed to help you manage your personal reading list. Say goodbye to decision fatigue—this app lets you build a cozy digital library, track your reading progress, and let fate (and a randomizer) pick your next book. ☕🍂

## ✨ What's New in Version 2.0
Version 2.0 is a massive rewrite from the ground up, transitioning from a text-based console menu to a premium graphical interface.

* **Apple Glass Aesthetic:** A complete UI overhaul featuring a modern glassmorphism design, custom integrated title bars, pill-shaped buttons, and soft drop shadows. 
* **Google Books API Integration:** Live, accurate search results. Add books by title and instantly view the top 5 matches with high-quality cover art previews before confirming.
* **Visual Library Grid:** View your collection as a digital bookshelf. Books are displayed on clean, rounded cards with their official cover art.
* **Native Windows Installer:** Packaged as a standalone `.exe` with a custom icon and professional publisher branding.

## 🚀 Features
* **Smart Search:** Search for any book, select the correct edition from a dropdown menu, and visually confirm the cover art.
* **Status Tracking:** Easily categorize your books as *To Read*, *Reading*, or *Finished* via the library grid dropdowns.
* **"Pick Random" Engine:** Can't decide what to read? The app filters your library for "To Read" books and randomly selects one for you, complete with a cozy pop-up.
* **Error-Proof Removal:** Delete books safely using a populated dropdown menu—no exact typing required.
* **Local JSON Storage:** Your library is securely saved locally to a `books.json` file in your Documents folder using Gson, ensuring it is fast, offline, and completely private.

## 🛠️ Tech Stack
* **Language:** Java
* **UI Framework:** Java Swing + [FlatLaf](https://www.formdev.com/flatlaf/) (IntelliJ Theme with heavy custom styling)
* **Data Parsing:** Google Gson
* **Networking:** Java `HttpClient` & Google Books API
* **Deployment:** `jpackage` (WiX Toolset)

## 📦 Installation
1. Go to the [Releases](#) tab on this repository.
2. Download the latest `BookPicker-2.0.exe` installer.
3. Run the installer to add Book Picker to your Windows Start menu and Desktop. 
*(Note: Installs directly to the local User AppData, requiring no Administrator privileges).*
