# SnapMaker FLL сайты

3D assets and models for the BIL A FORCE FLL project (OASIS Smart Box).

Бір парақтық статикалық сайт. Код таза HTML/CSS/JS, сыртқы тәуелділік жоқ (Google Fonts қана).

## Жергілікті қарау
```bash
python3 -m http.server 8000
# немесе жай ғана index.html файлын браузерде ашыңыз
```

## Баптау ұсыныстары
- `index.html`: мәтін, даталар, байланыс деректері.
- `styles.css`: түс палитрасы, өлшемдер.
- `script.js`: тек мобильді мәзір мен тегіс скролл.

## Контентті жаңарту
- Басты бет қысқа карточкалар: `index.html` ішіндегі `.feature-grid`.
- Толық беттер: `team.html`, `season.html`, `project.html`.
- Серіктестер: контакт карточкасына логотиптерді фон арқылы немесе `<img>` көмегімен қосуға болады.
- Логотиптер: SVG нұсқалары `media/SM-logo.svg` (иконка) және `media/SM-logo-text.svg` (мәтіндік) — басты бетте қолданылып тұр, қажет болса header/footer-ге де қоюға болады.

## Түс палитрасы (SnapMaker)
- Primary: #6F3DF4 (Snap Purple)
- Accent: #8C5BFF
- Фон dark: #0F0F14 (Tech Black)
- Фон light: #F5F6FA (Soft White)
- Status: Safe #2ECC71 · Warning #F1C40F · Critical #E74C3C · Info #3498DB

## 3D модель
- `OASIS.glb` — жобаның 3D моделі. Көру: `project.html` бетінде `<model-viewer>` арқылы.

## Логотиптер
- media/SM-logo.svg — қою иконка
- media/SM-logo-text.svg — қою мәтіндік
- media/SM-logo-light.svg — жарық иконка
- media/SM-logo-text-light.svg — жарық мәтіндік
- Header және бренд блокта жарық+қою нұсқалар бірге қолданылады.

## Лицензия
MIT
