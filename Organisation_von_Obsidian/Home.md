---
cssclasses:
  - dashboard

banner: "![[BannerHisQu.png]]"
banner_y: 0.452
---




# Literatur
- Neue Literatur: `$=dv.list(dv.pages('"Literatur"').sort(f=>f.file.mtime.ts,"desc").limit(3).file.link)`
- PDFs: `$=dv.list(dv.pages('"PDFs"').sort(f=>f.file.mtime.ts,"desc").limit(3).file.link)`
# Protokolle


# Vault Info

- 🗄️ Zuletzt bearbeitet:  `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(7).file.link)`
- 🔖 Tagged: Favorit `$=dv.list(dv.pages('#Favorit').sort(f=>f.file.name,"desc").limit(7).file.link)`
- 〽️ Stats
    - File Count: `$=dv.pages().length`
    - Anzahl der Literaturtitel: `$=dv.pages('"Literatur"').length`**
- Kurzanleitung
	- [[Organisation_von_Obsidian/Allgemeine_Einführung]]
	- [[Shortcuts]]
# Links
- [Forschungsdateninfrastruktur Historische Quellen · GitHub](https://github.com/HisQu)
---


