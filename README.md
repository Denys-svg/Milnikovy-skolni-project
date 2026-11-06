# Cestou po svém — školní projekt

Statický cestovatelský magazín vytvořený v HTML5 a CSS. Obsahuje tři propojené stránky: domovskou, článek a informace o projektu.

## Odkazy

- Repozitář GitHub/GitLab: https://github.com/Denys-svg/Milnikovy-skolni-project
- Živá verze na školním serveru: https://stratide25.llmp.spse-net.cz/milnikovy.html
- Wireframe domovské stránky: [wireframe.pdf](wireframe.pdf)

## Soubory

- `milnikovy.html` — domovská stránka
- `detail.html` — článek, galerie a slovníček
- `kontakt.html` — informace, kontakt a mapa
- `milnikovy.css` — barvy, rozložení a mobilní vzhled
- `images/kompas.svg` — vektorové logo
- `wireframe.pdf` — wireframe domovské stránky

## Checklist zadání

- [x] **Téma: tematický magazín.** Představení projektu: `milnikovy.html`, řádky 35–45.
- [x] **Tři vzájemně navigovatelné stránky.** Hlavní navigace: `milnikovy.html:19–31`, `detail.html:19–31`, `kontakt.html:19–31`. Odkazy v patičce: `milnikovy.html:139–168`, `detail.html:194–223`, `kontakt.html:98–127`.
- [x] **Domovská stránka s náhledy.** Hlavní článek: `milnikovy.html:50–70`; další karty: `milnikovy.html:87–121`.
- [x] **První náhled vede na detail, ostatní jsou placeholdery.** Prokliky na `detail.html`: `milnikovy.html:50–70`; ostatní karty „Brzy na webu“: `milnikovy.html:93`, `106`, `119`.
- [x] **Dlouhý, členěný detail článku.** `detail.html:51–141`.
- [x] **Kontextový `<aside>`.** Rychlý přehled a slovníček: `detail.html:143–191`.
- [x] **Informace a kontaktní údaje.** `kontakt.html:34–70`.
- [x] **Autor a smyšlené IČO v patičce.** `milnikovy.html:145`, `detail.html:200`, `kontakt.html:104`.
- [x] **Sémantické prvky** `<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`. Příklady: `milnikovy.html:16–139`, `detail.html:16–194`, `kontakt.html:16–98`.
- [x] **Povinné `<hgroup>` a `<time>`.** `milnikovy.html:39,62`; `detail.html:40,49`; `kontakt.html:39`.
- [x] **Doplňkové `<address>`, `<abbr>`, `<mark>`, `<data>`, `<dfn>`.** `kontakt.html:62`; `detail.html:86,150–154`; `milnikovy.html:145`, `detail.html:200`.
- [x] **Vložené `<iframe>`.** Video: `detail.html:131`; mapa: `kontakt.html:80`.
- [x] **SVG grafika.** `images/kompas.svg`; logo se používá v hlavičce stránek, např. `milnikovy.html:17`.
- [x] **Rastrové fotografie ve WebP.** Parametr `fm=webp`: `milnikovy.html:54,88,101,114`; `detail.html:53,72,89,103,117`.
- [x] **Pět obrázků detailu s `srcset` a více rozlišeními.** `detail.html:53,72,89,103,117` (každý obrázek nabízí několik šířek).
- [x] **Wireframe jedné stránky.** Domovská stránka: `wireframe.pdf`.
- [x] **Odkaz na repozitář a živou verzi.** https://github.com/Denys-svg/Milnikovy-skolni-project
