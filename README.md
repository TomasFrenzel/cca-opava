# Webové stránky pro Český červený kříž Opava

Tento projekt představuje vývoj webových stránek pro místní pobočku Českého červeného kříže v Opavě. Web bude sloužit k prezentaci činnosti organizace, sdílení aktualit, fotogalerií a poskytne jednoduchou administraci obsahu.

## 🔧 Použité technologie

- **HTML, CSS, JavaScript** – základní struktura a interaktivita webu
- **PHP** – backendová logika, zpracování formulářů, napojení na databázi
- **MySQL** – databáze pro ukládání článků a fotek
- **Admin panel** – zabezpečené rozhraní pro správu obsahu (články, galerie)

## 🧭 Struktura webu

- **`index.php`** – úvodní stránka s novinkami a základními informacemi
- **`onas.php`** – stránka „O nás“ s informacemi o činnosti a historii CČK Opava
- **`galerie.php`** – fotogalerie z akcí
- **`clanky.php`** – seznam a detail článků
- **`kontakt.php`** – kontaktní údaje a formulář
- **`admin/`** – administrační sekce (přihlášení, správa článků a obrázků)

## ✍️ Funkce admin panelu

- Přihlášení pro správce
- Přidávání, úprava a mazání článků
- Nahrávání a správa fotek v galerii

## 📂 Databáze

Projekt používá MySQL databázi se základními tabulkami:

- `clanky` – nadpis, obsah, datum, autor
- `galerie` – název, obrázek, popis
- `uzivatele` – přihlašovací údaje admina

## 🔐 Bezpečnost

- Základní autentizace pro admin sekci
- Ochrana proti SQL injection (použití připravených dotazů)
- Validace vstupů z formulářů

## 🗓️ Stav projektu

Práce na webu je v aktivním vývoji. V dalších fázích bude doplněna optimalizace pro mobilní zařízení a případně jazykové mutace.

---

## 📬 Kontakt

Pro více informací nebo spolupráci mě můžete kontaktovat na tomasagel71@gmail.com.

