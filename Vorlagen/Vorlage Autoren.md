---
tags:
  - "#Autoren"
aliases:
  - <% tp.file.title %>
  - <% tp.file.title %>s
  - <% tp.file.title.split(" ").pop() %>
  - <% tp.file.title.split(" ").pop() %>s
Autor: <% tp.file.title %>
---
```dataview
list from ""
where contains(file.outlinks, [[<% tp.file.title %>]])
```


# <% tp.file.title %>

## 📚 weiter Angaben

- Siehe auch: `[[...]]`
- Methodische Nähe zu: `[[...]]`
- Wird zitiert in: `[[...]]`

## ✍️ Bearbeitungsvermerk

- Notizen erstellt von: `@...`
- Letzte Bearbeitung: <% tp.date.now("YYYY-MM-DD") %>


<%*
let authorFolder = "Literatur/Autoren"
let fileName = tp.file.title
await tp.file.move(authorFolder + "/" + fileName)
%>