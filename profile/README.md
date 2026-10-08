<a href="https://studio.klxm.de"><img src="https://raw.githubusercontent.com/KLXM-Opensource/.github/main/profile/assets/banner.jpg" alt="KLXM Studio – Websites. Inhalte. Ein System." width="100%"></a>

<p align="center">
  <a href="https://github.com/KLXM-Opensource/studio/blob/main/LICENSE"><img src="https://img.shields.io/badge/Lizenz-MIT-2F3F63" alt="Lizenz: MIT"></a>
  <img src="https://img.shields.io/badge/PHP-8.4%2B-2F3F63?logo=php&logoColor=white" alt="PHP 8.4+">
  <img src="https://img.shields.io/badge/WCAG-2.2%20AA-2F3F63" alt="Ziel: WCAG 2.2 AA">
  <img src="https://img.shields.io/badge/cookiefrei-ab%20Werk-2F3F63" alt="cookiefrei ab Werk">
</p>

<p align="center">
  <b>Web mit System.</b> Schlankes Open-Source-CMS für Websites, Inhalte und Daten – von
  <a href="https://klxm.de">KLXM Crossmedia</a> aus Moers.<br>
  <a href="https://studio.klxm.de">studio.klxm.de</a> ·
  <a href="https://github.com/KLXM-Opensource/studio">Quellcode</a> ·
  <a href="https://studio.klxm.de/tutorials">Tutorials</a> ·
  <a href="#english">English</a>
</p>

---

**KLXM Studio** ist ein Multi-Site-CMS ohne Framework für PHP 8.4+. Statt Themes gibt es **Kits**: Ein Kit ist das ganze
Fundament eines Projekts – Design, Blöcke, Datenstrukturen, Einstellungen und Startinhalte. Bearbeitet wird direkt auf der
Website, Daten und Formulare entstehen ohne Code, und KI ist an Bord – auf Wunsch komplett lokal.

<table>
  <tr>
    <td width="50%"><img src="https://raw.githubusercontent.com/KLXM-Opensource/.github/main/profile/assets/screens/bearbeiten.jpg" alt="Bearbeiten direkt auf der Website"><br><sub><b>Bearbeiten auf der Website</b> – Blöcke, Entwurf, Veröffentlichen, Versionen</sub></td>
    <td width="50%"><img src="https://raw.githubusercontent.com/KLXM-Opensource/.github/main/profile/assets/screens/daten.jpg" alt="Datentabellen ohne Code"><br><sub><b>Daten ohne Code</b> – Tabellen, Detailseiten, Formulare, Kalender</sub></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/KLXM-Opensource/.github/main/profile/assets/screens/mediathek.jpg" alt="Mediathek"><br><sub><b>Mediathek</b> – zerstörungsfreie Bildbearbeitung, Zuschnitte, Untertitel</sub></td>
    <td><img src="https://raw.githubusercontent.com/KLXM-Opensource/.github/main/profile/assets/screens/netzwerk.jpg" alt="Netzwerk-Übersicht"><br><sub><b>Multi-Site & Netzwerk</b> – viele Websites aus einer Installation</sub></td>
  </tr>
</table>

### Was drinsteckt

- **Kits** für unterschiedliche Branchen und Stile – mit Design-Editor, Darstellungsvarianten und Startinhalten
- **Blockeditor auf der Website** mit Entwürfen, Freigabe und Versionen; Layout-Raster per Maus verstellbar
- **Datentabellen & Formulare** ohne Code – Detailseiten, Kalender mit iCal, verschlüsselte Anfragen im Postfach-Stil
- **Suche** mit Tippfehlertoleranz, optional semantisch – und auf Wunsch mit **KI-Antwort samt Quellen** über den Treffern
- **KLXM AI** – Schreiben, Übersetzen, SEO, Alt-Texte, Besucher-Chat; mit Ollama lokal, EU-Anbietern oder OpenAI-kompatibel
- **Mitteilungen** per Web Push, **Passkeys** und Zwei-Faktor, **REST-API** (OpenAPI 3.1) und **MCP-Server**
- **Barrierearm und datenschutzfreundlich** – Ziel WCAG 2.2 AA, cookiefrei, strenge Content-Security-Policy

### Repositories

| | Repository | Was |
|---|---|---|
| 🧱 | **[studio](https://github.com/KLXM-Opensource/studio)** | das CMS – Core, mitgelieferte Kits, Dokumentation |
| 🎞️ | [studio-motion](https://github.com/KLXM-Opensource/studio-motion) | Erweiterung: Animationen per Drag & Drop gestalten (SVG + CSS) |
| 🔐 | [studio-members](https://github.com/KLXM-Opensource/studio-members) | Erweiterung: Mitgliederbereich mit Passkey-Anmeldung, geschützten Seiten und Medien |
| 🏠 | [studio-kit-immobilien](https://github.com/KLXM-Opensource/studio-kit-immobilien) | Kit für Makler und Hausverwaltung (OpenImmo-konform) |

Erweiterungen und Kits sind eigene Composer-Pakete (`klxm-studio-extension`).

### Schnellstart

```bash
git clone https://github.com/KLXM-Opensource/studio.git klxm-studio && cd klxm-studio
composer install
php -S localhost:8000 -t public public/index.php
```

Danach `http://localhost:8000/admin/setup` öffnen. Server-Installation, Plesk und Betrieb: [README](https://github.com/KLXM-Opensource/studio#readme)
und Entwicklerhandbuch in der Verwaltung.

> **Status:** Das erste Release 1.0 ist in Vorbereitung. KLXM Studio läuft bereits produktiv – u. a. auf
> [studio.klxm.de](https://studio.klxm.de).

**Lizenz:** [MIT](https://github.com/KLXM-Opensource/studio/blob/main/LICENSE) ·
**Mitmachen:** [CONTRIBUTING.md](https://github.com/KLXM-Opensource/studio/blob/main/CONTRIBUTING.md) ·
**Sicherheit:** Lücken bitte vertraulich melden – [SECURITY.md](https://github.com/KLXM-Opensource/studio/blob/main/SECURITY.md)

---

<a id="english"></a>

### English

**KLXM Studio** is a framework-free multi-site CMS for PHP 8.4+, built by KLXM Crossmedia in Moers, Germany. Instead of
themes it uses **kits** – a complete project foundation of design, blocks, data structures, settings and starter content.

- **On-page block editing** with drafts, approval and revisions
- **Data tables & forms** without code – detail pages, iCal calendars, encrypted inboxes
- **Search** with typo tolerance, optional semantic search and an **AI answer with sources** above the results
- **KLXM AI** for writing, translation, SEO, alt texts and a visitor chat – local with Ollama, EU providers or OpenAI-compatible
- **Multi-site & network**, Web Push, passkeys, REST API (OpenAPI 3.1) and an **MCP server**
- **Accessible and privacy-friendly** – targeting WCAG 2.2 AA, cookie-free, strict Content Security Policy

Extensions: [Motion](https://github.com/KLXM-Opensource/studio-motion) (animations) ·
[Members](https://github.com/KLXM-Opensource/studio-members) (member areas) · Kit: [Immobilien](https://github.com/KLXM-Opensource/studio-kit-immobilien) (real estate).
The first release 1.0 is being prepared. **License:** MIT.

---

<p align="center"><sub>Made in Moers by <a href="https://klxm.de">KLXM Crossmedia</a> · Agentur seit 2001</sub></p>
