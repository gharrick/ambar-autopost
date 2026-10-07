# Skills de Instagram para Claude Code

Las skills `/ig-*` en `.claude/skills/` vienen de
[Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)
(MIT, licencia en `.claude/skills/LICENSE-instagram-agent-skill`). Escriben
guiones, captions, carruseles, stories, DMs y planes; no publican nada.

Único cambio respecto al original: las rutas `~/.claude/instagram/` se
cambiaron por `.claude/instagram/` (esta carpeta), para que la voz, el
swipe file, el plan y el log queden en el repo y sirvan igual en sesiones
locales y en la nube.

## Para arrancar

1. Completá `voice.md` (10 minutos). Lo más fácil: pegale a Claude 3
   captions o guiones tuyos y decile "armá mi voice.md con esto". Todas las
   skills lo leen; por eso los textos después suenan a la marca y no a IA.
2. `/ig-viral` busca los reels que mejor andan en tu nicho y dice por qué.
3. `/ig-reel` escribe el guion con el gancho puntuado.
4. `/ig-caption` arma la descripción y la pasa por el linter.
5. `/ig-profile` le pone nota al perfil y reescribe la bio.
6. `/ig-plan` arma la semana.

Hablale en español y responde en español.

## Archivos que las skills escriben acá

- `voice.md` — tu voz (lo completás vos).
- `swipe.md` — lo que deja `/ig-viral`.
- `plan.md` — lo que deja `/ig-plan`.
- `log.md` — qué se publicó y a quién se comentó.
