# Lucrare de Laborator Nr.1 — Tehnologii Web

**Student:** Ciobanu Stanislav, gr. CR-221fr  
**Conducător:** lect.univ. Rusu Viorel  
**Instituție:** UTM — Facultatea Calculatoare, Informatică și Microelectronică  
**An:** 2024

---

## Tema

> **Conceperea unei aplicații Web. Crearea conținutului Web utilizând HTML și CSS**

---

## Descriere

Lucrarea are două părți principale:

1. **Instalarea unui server web local** — compararea pachetelor (XAMPP, WAMP, EasyPHP, AMPPS, AppServ), alegerea și instalarea **XAMPP**, configurarea virtual host-urilor, testarea cu pagini HTML/CSS simple.

2. **Dezvoltarea unui site static** — site-ul salonului auto fictiv **AutoPrim SRL** cu 5 pagini HTML interconectate, un fișier CSS comun, meniuri derulante, blocuri dinamice, tabele și formulare.

---

## Structura proiectului

```
autoprim/
├── style.css                  # Fișier CSS comun pentru toate paginile
├── index.html                 # Pagina principală
├── despre.html                # Pagina "Despre noi"
├── masini_noi.html            # Pagina "Asortiment → Mașini noi"
├── masini_second_hand.html    # Pagina "Asortiment → Mașini second-hand"
├── filiale.html               # Pagina "Filiale"
└── contacte.html              # Pagina "Contacte"

exemplu/
├── index.html                 # Pagina de test a serverului web
└── style.css                  # Stilul paginii de test
```

---

## Modelul funcțional al site-ului

```
Acasă
├── Acasă
├── Despre noi
├── Asortiment
│   ├── Mașini noi
│   └── Mașini second-hand
├── Filiale
└── Contacte
```

---

## Tehnologii utilizate

| Tehnologie | Versiune / Detalii |
|---|---|
| HTML | HTML5 |
| CSS | CSS3 + SVG (validat W3C) |
| Server web | Apache (via XAMPP 8.2.12) |
| Browser | Microsoft Edge |
| Editor | Notepad |
| Image hosting | imgbb.com (CDN) |
| Maps | Google Maps embed |

---

## Capturi de ecran

### Pagina de copertă a raportului

![Copertă](screenshots/page_1.png)

---

### Panoul de control XAMPP — server pornit

![XAMPP Control Panel](screenshots/page_15.png)

---

### Pagina de test a serverului (`exemplu/index.html`)

![Pagina exemplu](screenshots/page_18.png)

---

### Pagina principală — AutoPrim SRL (`index.html`)

![Pagina principală](screenshots/page_45.png)

---

### Pagina "Despre noi" (`despre.html`)

![Despre noi](screenshots/page_50.png)

---

### Pagina "Mașini Noi" (`masini_noi.html`)

![Mașini Noi](screenshots/page_61.png)

---

### Pagina "Filialele noastre" (`filiale.html`)

![Filiale](screenshots/page_81.png)

---

## Caracteristici HTML/CSS demonstrate

- Structura HTML5 semantică: `<header>`, `<nav>`, `<footer>`, `<section>`
- Meniu de navigare cu **submeniu derulant** (CSS `:hover`)
- **Tabele** cu `border`, `colspan`, `rowspan`, `caption`, `bgcolor`
- **Formulare** cu `input[type="email|tel|date|color|submit"]`
- **Canvas HTML5** cu JavaScript (desene, text, umbre, gradient)
- **Audio HTML5** cu atributele `autoplay` și `loop`
- **Liste** ordonate și neordonate (`<ol type="A">`, `<ul type="circle">`)
- Formatare text: `<b>`, `<i>`, `<u>`, `<em>`, `<strong>`, `<cite>`, `<code>`, `<pre>`, `<sup>`
- Entități HTML: `&copy;`, `&nbsp;`, `&lt;`, `&gt;`, `&amp;`
- Ancore interne (`<a name="...">`) și link-uri externe
- CSS extern cu selectori simpli, multipli, descendenți, de atribut și pseudo-clase
- Clase CSS pentru blocuri dinamice cu înălțime fixă
- Imagini externe prin CDN (imgbb.com)
- Hărți Google Maps embed (`<iframe>`)
- Validat cu **W3C CSS Validator** (CSS3 + SVG — fără erori)
- Validat cu **W3C Markup Validation Service** (HTML5 — fără erori)

---

## Rulare locală

1. Instalați [XAMPP](https://www.apachefriends.org/) și porniți modulul **Apache**.
2. Copiați folderul `autoprim/` în `C:\xampp\htdocs\`.
3. Accesați în browser: `http://localhost/autoprim/`

---

## Concluzie

Lucrarea a permis acumularea de experiență practică cu instalarea unui server web local (XAMPP), crearea și validarea paginilor HTML5/CSS3, utilizarea virtual host-urilor Apache și implementarea unui site static multi-pagină cu navigare funcțională.

---

*© 2024 Ciobanu Stanislav. Toate drepturile rezervate.*
