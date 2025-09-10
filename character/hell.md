---
title: Demons
permalink: /character/demons/
---

# Demons

All demons in Hell possess the potential to wield **dark magic** and assume a **beast form**. However, not every demon can access or endure these powers—some never awaken their magic; others cannot withstand the transformation.

---

## Hell (Quick Overview)

Hell, home of demons, darkness, and the Devil, is divided into **nine layers**:

1. **Human Layer** – Human souls are isolated for endless torment; highly coveted by demons.
2. **The Arena** – Humans and weak creatures are forced to fight. Survivors are sent onward, destroyed, or conscripted to torture humans in Layer 1.
3. **Domain of Creatures** – The largest layer, connecting Hells across universes; home to most demons, the Devil’s castles, and Hell’s heart. A Demon God guards a portal at the center.
4. **The Smallest Layer** – Resource-rich and mostly peaceful; nature/water demons are born here. Ruled by seven Demon Kings; contains a hidden portal to Heaven. Humans sent here serve the kings.
5. **The Cursed Arsenal** – *Asmodeus’s Trash Heap.* Discarded weapons absorb blood and dark magic, becoming cursed; every ~500,000 years demonic spiders scatter ~500 of them into Layer 3, causing carnage—unless Asmodeus intervenes.
6. **The Prison** – Eternal prison of the Flesh Demon King.
7. **Threshold of Death** – Entrance to the Death Realms.
8. **Abyss Realm** – Void and shadow; feared even by demons.
9. **The Chaos Seal** – The Chaos God is bound here.

➡ For the full write-up (details, notes, and anchors), see **[Hell: The Nine Layers](/character/hell/)**.

---

## Index of Demons
{% assign demon_pages = site.pages | where_exp: "p", "p.url contains '/character/demons/'" | sort: "title" %}
<ul>
{% for p in demon_pages %}
  {% if p.url != "/character/demons/" %}
    <li><a href="{{ p.url }}">{{ p.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
