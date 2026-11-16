# Jeopardy! – 25+1-utgaven

Statisk Jeopardy-spill for én skjerm (PC koblet til TV). Game master styrer.

Live: https://jeopardy.oscartimm.no

- `board.json` – kategorier, spørsmål, svar, bilder og videoklipp (`start`/`pause`/`end` i sekunder, `rate` = slow-mo på svaret, `mask` = skjul nederste del av videoen)
- `img/`, `video/` – medier
- Spillstatus lagres i nettleserens localStorage

Kjør lokalt: `python3 -m http.server` og åpne http://localhost:8000

Deploy: `npx vercel@latest deploy --prod`
