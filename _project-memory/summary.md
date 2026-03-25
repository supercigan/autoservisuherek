# Autoservis UHEREK — Project Memory

**Projekt:** Autoservis UHEREK — jednostránkový web
**Datum zahájení:** 2026-03-25
**Pracovní složka:** C:\Users\karel\weby\autoservisuherek
**GitHub:** https://github.com/supercigan/autoservisuherek

---

## Co je hotovo

- [x] Analýza původního webu (https://autoservisuherek.cz/)
- [x] Přečteny všechny DNA soubory předchozích projektů
- [x] Navržena unikátní paleta a typografie (odlišná od všech DNA)
- [x] Vytvořen index.html — kompletní jednostránkový web
- [x] GitHub push → supercigan/autoservisuherek (2026-03-25)
- [x] Opravy po screenshot review (2026-03-25)

### Design brief
- **Vizuální archetype:** "Workshop Precision" — teplý průmyslový styl, profesionální řemeslník
- **Paleta:** Gunmetal (#1C2728) + Warm Orange (#E5601A) — zcela nová kombinace
- **Fonty:** Rajdhani (nadpisy) + Source Sans 3 (tělo) — nepoužito v žádném předchozím projektu
- **Hero:** Diagonální oranžový CSS stripe + info panel vpravo (tel, email, adresa, hodiny)

---

## Reálné informace z původního webu

- **Název:** Autoservis UHEREK
- **Majitel:** Luboš Uherek
- **Telefon:** +420 777 203 666
- **Email:** info@autoservisuherek.cz
- **Adresa:** Pivovarská 273, 686 01 Uherské Hradiště - Jarošov
- **Otevírací doba:** Po–Pá 8:00–17:00
- **IČ:** 02701481 / **DIČ:** CZ8404014619

### Služby (6 + DPF):
1. Autoservis — záruční/pozáruční servis, STK, diagnostika VW/ŠKODA
2. Klimaservis — plnění, servis, dezinfekce klimatizací
3. Pojištění aut — nehodový servis, zapůjčení auta, vyřízení pojišťovny
4. Pneuservis — přezutí, vyvážení, opravy, uskladnění pneu
5. Autopůjčovna — krátkodobý i dlouhodobý pronájem
6. Výměna autoskel — opravy, výměny, praskliny
7. DPF filtry — spolupráce s dpf-premium.cz (samostatná callout sekce)

---

## Struktura webu (sekce)

1. NAV — fixed, transparent → gunmetal při scrollu, hamburger na mobilu
2. HERO — tmavý gunmetal, diagonální CSS stripe, bold H1, 2 CTAs, info panel vpravo
3. SLUŽBY — 6 karet v gridu 3×2, orange top-border na hover
4. DPF CALLOUT — tmavá sekce, ghost "DPF" text, odkaz na dpf-premium.cz
5. PROČ MY — 3 karty s čísly 01–03, bílé pozadí
6. O NÁS — split layout: text + tagy vlevo / kontaktní box s hodinami vpravo
7. KONTAKT — split: intro + kontakty vlevo / formulář vpravo
8. FOOTER — 3 sloupce: logo+popis | navigace | kontakt

---

## Opravy po screenshot review

| Problém | Řešení |
|---|---|
| Logo ikona — slunce/hvězda | → klíč (Feather "tool" wrench SVG) |
| Klimaservis — hodiny | → sněhová vločka (AC) |
| Autopůjčovna — monitory | → klíček od auta |
| Výměna autoskel — lékárnička | → obdélník + blesk (prasklé sklo) |
| Modrý text v kartách | → `--text-mid` z `#4A5558` na `#696560` (teplá šedá) |
| Browser auto-linkování textu | → `format-detection` meta + `color !important` |
| 3. "Proč my" karta neviditelná | → IntersectionObserver threshold 0.12 → 0.05 |
| Příliš velký gap nad kartami | → `margin-bottom` section-head 56px → 32px |
| Nav logo SVG nebyl nahrazen | → odlišná indentace, replace_all ho minul — opraveno manuálně |

---

## Co se řeší

- Formulář: lokální simulace (bez Formspree — klient musí doplnit Formspree ID)
- Vercel: napojit na repo supercigan/autoservisuherek

---

## Důležitá rozhodnutí

- **Paleta:** Gunmetal + Orange — záměrně odlišná od navy/amber, carbon/red, dark/teal
- **Rajdhani:** geometrický kondenzovaný font — automotive charakter bez agresivity Bebas Neue
- **Diagonální stripe:** hero dekorace CSS only — jiný přístup než canvas/grid/glow
- **Žádné stats v hero** — dle CLAUDE.md standardu
- **Nav + footer logo** mají různou indentaci v HTML — při replace_all dávat pozor

---

## Příští kroky

- [x] GitHub push → supercigan/autoservisuherek (2026-03-25)
- [x] Opravy ikon a spacingu (2026-03-25)
- [ ] Vercel deploy (napojit repo na Vercel)
- [ ] DNA soubor do C:\Users\karel\DNA-projekty\DNA-autoservisuherek.md
