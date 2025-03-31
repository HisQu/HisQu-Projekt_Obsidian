---
cssclasses: dashboard
---




# Literatur
- Neue Literatur: `$=dv.list(dv.pages('"Literatur"').sort(f=>f.file.mtime.ts,"desc").limit(3).file.link)`
- PDFs: `$=dv.list(dv.pages('"PDFs"').sort(f=>f.file.mtime.ts,"desc").limit(3).file.link)`
# PDFs


# Vault Info

- 🗄️ Zuletzt bearbeitet:  `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(7).file.link)`
- 🔖 Tagged: Favorit `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(7).file.link)`
- 〽️ Stats
    - File Count: `$=dv.pages().length`
    - Personal recipes: `$=dv.pages('"Family/Recipes"').length`**