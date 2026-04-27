---
layout: default
title: Aktualności
---

<span style="color:red"> ! Strona i adres są tymczasowe służą jedynie do testu kanału RSS !</span>

### 📡 RSS
RSS to standard rozpowszechniania informacji do prezentowania nowości ze stron internetowych na bieżąco \
[- Ustawienia Thunderbird](https://support.mozilla.org/pl/kb/subskrybowanie-kanalow-informacyjnych-blogow) \
[- Ustawienia Outlook](https://www.youtube.com/watch?v=UzIvnwqwUco)

Subskrybuj RSS
<div markdown="span" style="margin-bottom: 2px; margin-top: 2px; overflow: hidden; color: #31708f; background-color: #d9edf7; border-color: #bce8f1; padding: 5px; border: 1px solid transparent; border-radius: 4px;">❕ <b>https://mcjkulik.github.io/NP_NewsletterPage_alpha/feed.xml</b> </div>👉 <button onclick="navigator.clipboard.writeText('https://mcjkulik.github.io/NP_NewsletterPage_alpha/feed.xml')">📋 Kopiuj link</button>


## Najnowsze publikacje
---

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}
