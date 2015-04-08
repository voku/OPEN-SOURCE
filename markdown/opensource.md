# Freie Software ⊆ Open Source Software

<div class="width_img_wrapper_60">
  ![Werkzeuge](images/tumblr_mjx41iyPVX1r6ar5jo1_500.jpg)
</div>

---

## To understand the concept, you should think of “free” as in “free speech,” not as in “free beer”.

TODO

---
<!-- .slide: data-background="images/backgrounds/shutterstock_200991887_B.jpg" data-state="inverted" -->

# Lizenzen

<div class="width_img_wrapper_70">
  ![Open Source](images/softwaremodels.png)
</div>
---

| Starkes Copyleft    | Schwaches Copyleft  | kein Copyleft     |
|---------------------|---------------------|-------------------|
| GPL                 | LGPL, MPL           | BSD, Apache, MIT  |

<strong>GPL:</strong> keine Einbindung in proprietären Code möglich

<strong>LGPL:</strong> Linken von Code mit proprietärer Software möglich

<strong>BSD:</strong> darf auch in proprietäre Software verwendet werden

---

# Geschäftsmodelle (Beispiele)

- Quellcode der Programmiersprache veröffentlichen und entsprechende Tools (z.B.: IDE) verkaufen

- Open Source Software weiterentwickeln und diese später als proprietärer Software verkaufen

- Hardware mit Open Source Software verkaufen

---

- proprietärer Software verkaufen, wobei Teile der Software Open Source sind

- technischen Support verkaufen

- Features (Werbung) gegen Zahlung in Open Source Software integrieren

- eine Open Source und eine "Enterprise" Version anbieten

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

# Wo veröffentliche ich Open Source Software?

---
<!-- .slide: data-background="images/reactions/tumblr_inline_mmrb6wlC0g1qz4rgp.gif" data-state="inverted faded" -->

# Welche Open Source Software Standards gibt es?

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

<h3 class="fragment">
  - Open Source <span class="highlight">Lizenz</span> für Software angeben (z.B.: LICENSE.txt)
</h3>

<h3 class="fragment">
  - <span class="highlight">Quellcode Organisatzion</span> (z.B. "src/", "tests/", "lib/")
</h3>

<h3 class="fragment">
  - <span class="highlight">Dokumentation</span> für Entwickler und Anwender
</h3>

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

<h3 class="fragment">
  - Plattform für Fragen und <span class="highlight">Kommunikation</span>
</h3>

<h3 class="fragment">
  - <span class="highlight">Versionsnummern</span> korrekt verwenden
</h3>

<h3 class="fragment">
  - <span class="highlight">Abhängigkeitsmanagement</span> für verwendete Bibliotheken nutzen
</h3>

---
<!-- .slide: data-background="images/backgrounds/terminal.jpg" data-state="inverted faded grayscaled" -->

<h3 class="fragment">
  - <span class="highlight">Testabdeckung</span> und automatische Tests bei jeder Änderung
</h3>

<h3 class="fragment">
  - <span class="highlight">Issue-Tracking-System</span> zur Verwaltung von Bugs verwenden
</h3>

---
<!-- .slide: data-background="images/reactions/hM9lqGh.gif" data-state="inverted faded grayscaled" -->

# Wie veröffentliche ich Open Source Software?

---
## Beispiel: <span class="highlight">npm</span>

### Installation von node.js, z.B.:
    sudo apt-get install nodejs

### Konfiguriere npm
    npm set init.author.name "Lars Moelleken"
    npm set init.author.email "lars@moelleken.org"
    npm set init.author.url "http://moelleken.org"

### npm User erstellen (~/.npmrc)
    npm adduser

---
## Beispiel: <span class="highlight">npm</span>

### interaktiv eine "package.json"-Datei erstellen
    npm init

### Abhänigkeiten & Tests hinzufügen
    npm install mocha --save-dev
    npm install chai --save-dev

### Veröffentliche dein Paket
    npm publish

---
## Beispiel: <span class="highlight">bower</span>

### Installation von node.js, z.B.:
    sudo apt-get install nodejs

### Installation von <span class="highlight">bower</span>
    npm install -g bower

---

### interaktiv eine "bower.json"-Datei erstellen
    bower init

### Veröffentliche dein Paket
    bower register <my-package-name> <git-endpoint>

---
## Beispiel: <span class="highlight">composer</span>

### Installation von composer, z.B.:
    curl -sS https://getcomposer.org/installer | php

### interaktiv eine "composer.json"-Datei erstellen
    composer init

### Veröffentliche dein Paket
    https://packagist.org/packages/submit

