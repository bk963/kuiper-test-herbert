# BRIEFING — kuiper-test-herbert

**Datum:** 2026-04-13
**Repo:** github.com/bk963/kuiper-test-herbert
**Deine Rolle:** Projektmanager + Coder

## Mission

Baue eine kleine statische Selbstvorstellungs-Website auf GitHub Pages.

Inhalt:
- Wer du bist (Herbert)
- Was du kannst (stichpunktartig)
- Deine Grenzen / was du bewusst NICHT machst
- Welche Modelle hinter dir stehen (ChatGPT-Plus via Codex, Claude Max via Code)
- Wer dich angelegt hat (Bjoern, 2026-04-10)

## Design

- CI-konform: **weiss + cyan**, schlicht aber fett
- Typografie: gross, klar, kein Clutter
- Kein Darkmode
- Mobile-responsive (Bjoern liest oft am iPhone)

## Dateien die du anlegen sollst

- `index.html` — die Seite selbst
- `style.css` — separate CSS (keine Inline-Styles)
- Beide im Repo-Root, damit GitHub Pages sie direkt ausliefert

## Workflow

1. Arbeite auf einem Branch namens `herbert/self-intro`
2. Committe klein und oft, aussagekraeftige Commit-Messages
3. Wenn fertig: pushe den Branch
4. Ein Cron auf dem CRM-Server entdeckt deinen Branch und oeffnet automatisch einen Pull Request
5. Claude reviewt den PR und merged (oder bittet um Aenderungen)
6. Dann ist GitHub Pages live unter https://bk963.github.io/kuiper-test-herbert/

## Status-Log

Schreibe parallel zum Arbeiten Status-Updates in `.herbert/log.md` — eine Zeile pro Schritt, Format:
```
[YYYY-MM-DD HH:MM]  was du gemacht hast / als naechstes planst
```

Das hilft Bjoern live zu sehen was du tust.

## Regeln

- NICHT direkt auf `main` pushen, NUR auf `herbert/self-intro`
- NICHT force-pushen
- Bei Problemen: schreib eine Telegram-Nachricht an Bjoern (ueber deinen normalen Bot)
- Wenn du festhaengst: bitte Claude um Hilfe via `/acp spawn claude`

## Akzeptanzkriterien

- Seite ist visuell sauber (weiss + cyan, schlicht, fett)
- Alle Inhalts-Punkte von oben sind drin
- Mobile schaut sauber aus
- HTML ist valide, CSS ist separat

Viel Erfolg. Starte wenn du bereit bist.
