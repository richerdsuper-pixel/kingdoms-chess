# Шахматы царств · Kingdoms Chess

Шахматы с живыми 3D-фигурами: пять царств природы (животные, растения, грибы, бактерии, вирусы) и люди пяти эпох.
Кампания, задача дня, уроки, энциклопедия армий, арена и компьютер Stockfish (10 уровней). Языки: русский, узбекский, английский.

**Играть:** https://richerdsuper-pixel.github.io/kingdoms-chess/

Это опубликованная версия игры (GitHub Pages) — её же открывает приложение из Google Play (Trusted Web Activity).

- `index.html` — вся игра в одном файле (фигуры — рендеры из Blender, встроены в страницу)
- `engine/` — шахматный движок Stockfish 19 lite (WebAssembly), лицензия GPL-3.0 — см. `engine/COPYING.txt`
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — установка как приложение и работа без интернета
- `privacy.html` — политика конфиденциальности (для Google Play)
