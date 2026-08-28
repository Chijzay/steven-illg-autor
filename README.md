# Steven Illg · Portfolio

Persönliches Portfolio als Jekyll-Website, veröffentlicht via GitHub Pages.

Das Portfolio vereint zwei Bereiche: literarische Werke als **Autor** und technische Projekte als **IT-Experte**.

---

## Inhalt

### Autor

- **_So vergeht die Zeit_**

  Kurzgeschichten-Anthologie (2004–2014).

  Eine Sammlung von 21 Kurzgeschichten aus einem Jahrzehnt. Das Vorwort und ausgewählte Geschichten sind online lesbar.

- **_Was in uns bleibt_**

  Zwei Kurzromane (erscheint voraussichtlich im Spätsommer 2026).

### IT

- **Datenbankerstellung mit SQL**

  Ein Leitfaden zur Datenbankmodellierung und SQL-Abfragen, als PDF lesbar und herunterladbar.

---

## Website besuchen

Besuchbar unter **[chijzay.github.io/steven-illg-autor](https://chijzay.github.io/steven-illg-autor/)**.

---

### Fotografie

- **Galerie**



## Projektstruktur

```
.
├─ _layouts/
│  ├─ portfolio.html     # Startseite mit Tab-Navigation (Autor / IT)
│  ├─ book.html          # Universelles Layout für alle Buchseiten
│  └─ default.html       # Layout für Einzelgeschichten und sonstige Unterseiten
│
├─ assets/
│  ├─ img/
│  │  ├─ autor.jpg       # Profilfoto
│  │  ├─ cover.jpg       # Buchcover „So vergeht die Zeit"
│  │  └─ cover-db.jpg    # Cover „Datenbankerstellung mit SQL"
│  └─ pdf/
│     └─ db-sql.pdf      # SQL-Leitfaden als PDF
│
├─ stories/
│  ├─ index.md                    # Anthologie-Übersicht
│  ├─ vorwort.md
│  ├─ der-fiese-lehrer.md
│  ├─ der-ring.md
│  ├─ der-schatten-am-fenster.md
│  ├─ der-zahn-von-loewe.md
│  ├─ es-passierte-im-bus.md
│  ├─ jeder-waere-der-falsche.md
│  └─ mein-maedchen.md
│
├─ index.md              # Startseite (verweist auf portfolio-Layout)
├─ index-wiub.md         # Seite: „Was in uns bleibt"
├─ index-db-sql.md       # Seite: „Datenbankerstellung mit SQL"
├─ ba-thesis.md          # Weitere IT-Projektseite
├─ _config.yml           # Jekyll-Konfiguration
├─ CITATION.cff          # Zitierhinweise
├─ LICENSE               # © Steven Illg – alle Rechte vorbehalten
└─ README.md
```

---

## Hinweis zu Inhalten

Einzelne Kurzgeschichten können sensible Themen berühren (u. a. psychische Belastung).  
Bitte lies achtsam und pausiere, wenn es dir nicht guttut.

---

## Kontakt

Kontaktmöglichkeiten findest du auf meinem [GitHub-Profil](https://github.com/Chijzay).

---

## Lizenz und Rechte

© Steven Illg, 2004–2026 — **alle Rechte vorbehalten**.

Es wird **keine** Lizenz zur Vervielfältigung, Verbreitung, Bearbeitung oder sonstigen Weiterverwendung der Texte und Inhalte eingeräumt. Details siehe [`LICENSE`](./LICENSE).
