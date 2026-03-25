# Autoservis UHEREK — Project Memory

**Projekt:** Autoservis UHEREK — jednostránkový web
**Datum zahájení:** 2026-03-25
**Pracovní složka:** C:\Users\karel\weby\autoservisuherek

---

## Co je hotovo

- [x] Analýza původního webu (https://autoservisuherek.cz/)
- [x] Přečteny všechny DNA soubory předchozích projektů
- [x] Navržena unikátní paleta a typografie (odlišná od všech DNA)
- [x] Vytvořen index.html — kompletní jednostránkový web

### Design brief
- **Vizuální archetype:** "Workshop Precision" — teplý průmyslový styl, profesiální řemeslník
- **Paleta:** Gunmetal (#1E2728) + Warm Orange (#E55A1A) — zcela nová kombinace
- **Fonty:** Rajdhani (nadpisy) + Source Sans 3 (tělo) — nepoužito v žádném předchozím projektu
- **Hero:** Diagonální oranžový stripe akcent (pure CSS, ne canvas/grid/glow)

---

## Reálné informace z původního webu

- **Název:** Autoservis UHEREK
- **Majitel:** Luboš Uherek
- **Telefon:** +420 777 203 666
- **Email:** info@autoservisuherek.cz
- **Adresa:** Pivovarská 273, 686 01 Uherské Hradiště - Jarošov
- **Otevírací doba:** Po–Pá 8:00–17:00
- **IČ:** 02701481
- **DIČ:** CZ8404014619

### Služby (6):
1. Autoservis — záruční/pozáruční servis, STK, diagnostika VW/ŠKODA
2. Klimaservis — plnění, servis, dezinfekce klimatizací
3. Pojištění aut — nehodový servis, zapůjčení auta, vyřízení pojišťovny
4. Pneuservis — přezutí, vyvážení, opravy, uskladnění pneu
5. Autopůjčovna — krátkodobý i dlouhodobý pronájem
6. Výměna autoskel — opravy, výměny, praskliny
7. DPF filtry — spolupráce s dpf-premium.cz

---

## Struktura webu (sekce)

1. NAV — fixed, transparent → gunmetal při scrollu
2. HERO — tmavý gunmetal, diagonální pruh, bold H1, 2 CTAs
3. SLUŽBY — 6 karet v gridu
4. DPF CALLOUT — zvýrazněná sekce pro partnerství s DPF Premium
5. O NÁS — text + kontaktní info panel
6. HODINY & KONTAKT — otevírací doba + adresa/mapa
7. FORMULÁŘ — kontaktní formulář
8. FOOTER

---

## Co se řeší

- GitHub push (čeká na dokončení index.html)
- Formulář: lokální simulace (bez Formspree — nutno doplnit ID)

---

## Důležitá rozhodnutí

- **Paleta:** Gunmetal + Orange — záměrně odlišná od navy/amber, carbon/red, dark/teal
- **Rajdhani:** geometrický kondenzovaný font — automotive charakter bez agresivity Bebas Neue
- **Diagonální stripe:** hero dekorace jako CSS clip-path — jiný přístup než canvas/grid/glow
- **Žádné stats v hero** — dle CLAUDE.md standardu

---

## Příští kroky

- [ ] GitHub push (vytvořit repo supercigan/autoservisuherek)
- [ ] Vercel deploy
- [ ] DNA soubor do C:\Users\karel\DNA-projekty\
