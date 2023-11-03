---
layout: posts
title: Notizen zum Veröffentlichen neuer Posts
description: "Introduction to what Jekyll is about and how it works"
date: 2023-11-03 16:39:00 +0100
categories: [Blog]
tags: [tipps]     # TAG names should always be lowercase
---
 
Die folgenden Notizen sind eine Kleine Erinnerung für mich.

### Punkt 1: Schreiben eines neuen Posts im Folder _posts

#### Template

~~~
---
title: TITLE
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     # TAG names should always be lowercase
---
~~~

### Punkt 2: diverse Auszeichnungen für Posts

- _italics_
- **bold**
- `code()` 

> Blockquote
>> Nested Blockquote

A link to [Jekyll Now](https://github.com/barryclark/jekyll-now/).

~~~
- _italics_
- **bold**
- `code()` 

> Blockquote
>> Nested Blockquote

A link to [Jekyll Now](https://github.com/barryclark/jekyll-now/).
~~~

### Punkt 3: Drei Befehle zum Veröffentlichen der Posts

~~~
1. git add .
2. git commit -m "Blabla"
3. git push origin main
~~~

Danach GitHub-Seite refreshen. Bei 'Actions' sieht man den Prozess der Aktualisierung. 

### Punkt 4: Fehler

Fehler 1: http-Links statt https-Links, erledigt

Fehler 2: Kategorien werden online nicht gebaut, **warum?**

Fehler 3: Inhaltsverzeichnis wird nicht erstellt, **warum?**

### Punkt 5: Nützliche Links 

[Youtube-Video](https://www.youtube.com/watch?v=m1RYsmOMPLs)

[Chirpy](https://chirpy.cotes.page/posts/write-a-new-post/)