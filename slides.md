---
theme: penguin
colorSchema: 'auto'
# some information about the slides, markdown enabled
info: |
  ## Geschichtsreferat Stellvertreterkriege
# persist drawings in exports and build
drawings:
  persist: false

layout: intro
logoHeader: '/logo.png'
twitter: 'Marten, Moritz, Luca und Dietrich'
eventLogo: '/pixel.png'
---

# Stellvertreterkriege

Wie die Großen es im Kalten Krieg schafften, doch irgendwie Krieg gegeneinander zu führen


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Agenda

1. Allgemeines
2. Afghanistan
3. Nicaragua
4. El Salvador

---
layout: new-section
---

# Allgemeines

---
layout: presenter
presenterImage: 'https://upload.wikimedia.org/wikipedia/commons/e/e2/RIAN_archive_21225_On_watch.jpg'
---

# Konflikte im Kalten Krieg

- Lorem
- Ipsum


<!--Hier allgemeine Informationen-->

---
layout: text-image
media: '/map/map.svg'
---
# Konfliktgebiete

- Hier
- noch
- mehr
- Stichpunkte

---


<v-click>
 <img alt="Afghanistan auf der Weltkarte" src="/map/map-afghanistan.png" class="map-zoom" />
</v-click>
<!--Switch zu Afghanistan via map-->

<style>
  /* Styling der Kartenanimation */
  .map-zoom {
    animation: zoom-in 3s ease-in;
    animation-fill-mode: forwards;
  }
  @keyframes zoom-in {
  0% {
    transform: scale(1, 1);
  }
  20% {
    transform: scale(1, 1);
  }
  50% {
    transform: scale(1.4, 1.4) translate(-4%, 5%);
  }
  100% {
    transform: scale(1.8, 1.8) translate(-8%, 10%);
  }
}
</style>
---
layout: new-section
---

# Afghanistan 🇦🇫

---
layout: new-section
---

# Nicaragua 🇳🇮

---
layout: new-section
---

# El Salvador 🇸🇻


---

# Quellen

- Weltkarte: [SVG-Datei](https://commons.wikimedia.org/wiki/File:AASM_operators.svg) (bearbeitet: [hier](/map/map.svg))