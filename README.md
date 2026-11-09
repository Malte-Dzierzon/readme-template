<div align="center">

# readme-template

**README-Strukturvorlage · dot-files-Stil · Agent-ready**

![](https://img.shields.io/github/last-commit/Malte-Dzierzon/readme-template?style=flat-square&color=16242d&labelColor=070e15)
![](https://img.shields.io/badge/style-dot--files-16a3da?style=flat-square&labelColor=070e15)
![](https://img.shields.io/badge/for-agents-0e0e43?style=flat-square&labelColor=070e15)

</div>

---

Strukturelle README-Vorlage im Stil meines [dot-files](https://github.com/Malte-Dzierzon/dot-files)-Repos. Keine fertige README — ein Skelett, das ein Agent pro Projekt ausfüllt.

## Quick start

Zeig dem Agent `TEMPLATE.md`, dann ein Satz zum Projekt:

```text
Schreib anhand von TEMPLATE.md (exakt diese Struktur, Platzhalter füllen,
leere Blöcke löschen) eine README für: <Projekt, 2–3 Sätze was es ist>.
```

## Struktur

| Datei | Zweck |
|---|---|
| `TEMPLATE.md` | Die Vorlage (Source of Truth, inkl. Agent-Anweisungen im Kopfkommentar) |
| `README.md` | Diese Datei — was das Repo ist, kein Beispiel |
| `AGENTS.md` | Regeln für Agents, die in diesem Repo arbeiten |

Stil in Kurzform: zentrierter Header (Name, Keyword-Zeile, Badges, max. 2 Hero-Bilder) → Übersichtstabelle → Quick start → Inhalte in `<details>`-Blöcken → optionale Galerie. Details stehen als Kommentare in `TEMPLATE.md`.
