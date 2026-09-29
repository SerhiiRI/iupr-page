# Книга переведення старої структури на нову (ROADMAP §0 R8)

Кожен файл старої теки має тут рядок. Файл без рядка вважається забутим.
Статуси: `не розглянуто`, `перенесено`, `частково`, `не переносимо (причина)`.
Вказівники (`status: moved`) у `pro-nas/` видалено 2026-09-29; повні донори — у `original/`.
Розділ `instytut_new/` закрито 2026-09-29: усі вказівники в `pro-nas/` і проміжні заглушки в `instytut_new/` видалено (`pro-nas/index.md` лишається до фінального обміну).
Пороги: цей файл — робочий, у фіналі його видаляє власник.

## pro-nas/ → instytut_new/

| Старий файл | Куди | Статус | Примітка |
|---|---|---|---|
| `pro-nas/index.md` | — | не переносимо (службовий індекс, замінений лендингом) | рішення власника 2026-09-29 |
| `pro-nas/pro-instytut.md` | `instytut_new/landing.md` (місія, програми, КРОК, фото 4/9), `instytut_new/kontaktna-informatsiya.md` (адреса, телефони, години, соцмережі, директор + фото, кабінети, скринька довіри) | перенесено | 2026-09-29; вказівник видалено. Кабінети студента/викладача — у контактах (посилання обрізані в джерелі, `TODO(кабінети)`); банер набору 2026/27 і фото випускників — у лендингу під TODO |
| `pro-nas/istoriya-zakladu.md` | `instytut_new/istoriya-zakladu.md` (повна), стисла версія — в `landing.md` | перенесено | 2026-09-29; вказівник видалено; виправлено пунктуацію списку керівників (прізвище «Голюка» підтверджено власником); `TODO(бакалаврат)`, `TODO(facts)` |
| `pro-nas/strategiya-rozvitku.md` | `instytut_new/strategiya.md` | перенесено | 2026-09-27; вказівник у `pro-nas/` видалено 2026-09-29 (лишається в `original/`) |
| `pro-nas/struktura-instytutu.md` | `instytut_new/struktura-instytutu.md` | перенесено | 2026-09-28; вказівник у `pro-nas/` видалено 2026-09-29 (лишається в `original/`) |
| `pro-nas/navchalno-organizatsiynyi-viddil.md` | `instytut_new/struktura-instytutu.md` (розділ «Навчально-організаційний відділ») | перенесено | 2026-09-29; вказівник у `pro-nas/` видалено |
| `pro-nas/normatyvni-dokumenty.md` | `instytut_new/publichna-informatsiya.md` (4 групи) + `instytut_new/strategiya.md` (PDF стратегії) | перенесено | 2026-09-29; вказівник видалено; усі 30 PDF на місці; педагогічні положення — у групі «Про Інститут і управління» (рішення власника); футер-контакти не переносимо |
| `pro-nas/monitoryng-yakosti-osvity.md` | `instytut_new/publichna-informatsiya.md` (група «Якість освіти», якір `monitoryng-yakosti-osvity`) | перенесено | 2026-09-29; вказівник у `pro-nas/` видалено; 2 `LINKWIP` замінено на PDF положень; відкрито: колізія PDF звіту 2023–2024 |
| `pro-nas/tsyklova-komisiya-fundamentalnykh-dystsyplin.md` | `instytut_new/struktura-instytutu.md` (розділ комісії) | перенесено | 2026-09-29; вказівник у `pro-nas/` видалено; **PDF резюме голови (`mandych-vira-volodymyrivna.pdf`) видалено за рішенням власника**, фото голови не переносимо (видалено з `wip/assets`, лишається в `original/`); склад — списком з ролями |
| `pro-nas/tsyklova-komisiya-humanitarnykh-dystsyplin.md` | `instytut_new/struktura-instytutu.md` (розділ комісії) | перенесено | 2026-09-29; вказівник у `pro-nas/` видалено; фото голови не переносимо (видалено з `wip/assets`, лишається в `original/`); склад — списком з ролями |

## kontakty/ → instytut_new/

| Старий файл | Куди | Статус | Примітка |
|---|---|---|---|
| `kontakty/adresa-telefony-mapa.md` | `instytut_new/kontaktna-informatsiya.md` | перенесено | 2026-09-29; окрема сторінка не потрібна (рішення власника), вказівник видалено; `kontakty/index.md` і `SITEMAP.md` переспрямовано; мапи в джерелі немає (`TODO(мапа)`), форма «Скринька довіри» — `TODO` |
