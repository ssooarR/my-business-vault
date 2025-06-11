# 🧱 Modul 2: Projektstruktur & Setup

## ✅ Ziel
- Klare technische & inhaltliche Grundlage
- Minimierung von Chaos im Verlauf
- Wiederverwendbarkeit & Dokumentierbarkeit
- Zukunftssicherheit der WordPress-Installation

---

## 📦 Projektstruktur (Empfehlung)

### 🔧 Technischer Stack

| Bereich               | Tool / Empfehlung               | Bemerkung                                  |
|-----------------------|----------------------------------|---------------------------------------------|
| Hosting               | IONOS, All-Inkl, Raidboxes       | je nach Kundensituation                     |
| WP-Stack              | Bedrock oder klassisch mit Setup-Skript | optional mit Git-Verwaltung            |
| Deployment            | Manuell via Install Script, ggf. WP-CLI | Backup & Rollback beachten             |
| Editor                | Elementor, Gutenberg (ACF Blocks) | keine Overengineering, einfache Pflege     |
| ACF / CPT             | ACF Pro + CPT UI / Custom Code   | konsistente Datenstruktur                   |
| Theme-Struktur        | Starter-Theme (z. B. Hello, Underscores) | anpassbar mit Child-Theme              |
| Git Repo              | GitHub / GitLab / self-hosted    | für Änderungsverfolgung + Backup            |
| Container (optional)  | LocalWP oder DDEV                | für lokale Entwicklung                      |

---

## 🗂 Projektverzeichnis (lokal & remote)

```txt
projektname/
├── content/
│   ├── uploads/
│   └── assets/
├── wp/
├── theme/
│   ├── child-theme/
│   └── starter-theme/
├── plugins/
│   └── acf-pro/
├── .env
├── composer.json
├── README.md
└── changelog.md
```

## Verweise & Notizen
#projekt
