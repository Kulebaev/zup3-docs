# 1С:Зарплата и управление персоналом 3 — Документация

Полная структурированная документация по конфигурации **1С:Зарплата и управление персоналом, редакция 3** в формате Markdown.

Репозиторий предназначен для использования в **Cursor** (и других AI-редакторах) в качестве базы знаний.

## Как использовать в Cursor

1. Клонируй этот репозиторий.
2. Открой проект в Cursor.
3. Добавь папку репозитория в Workspace.
4. Cursor автоматически проиндексирует все `.md` файлы.

### Рекомендуемые правила для Cursor

В репозитории уже есть готовый файл правил:
1c-zup-3.mdc


Cursor автоматически подхватит эти правила, когда ты будешь работать с файлами, связанными с 1С:ЗУП.

## Структура документации

### Быстрый старт
- [quick-start.md](quick-start.md) — Типичные задачи разработчика и как их решать

### Основные разделы

| № | Файл | Название |
|---|------|----------|
| 00 | [00-vvedenie.md](00-vvedenie.md) | Введение |
| 01 | [01-obshchaya-harakteristika.md](01-obshchaya-harakteristika.md) | Общая характеристика программы |
| 02 | [02-nastroika-programmy.md](02-nastroika-programmy.md) | Выбор используемых возможностей и настройка программы |
| 03 | [03-struktura-predpriyatiya.md](03-struktura-predpriyatiya.md) | Описание структуры предприятия |
| 04 | [04-shtatnoe-raspisanie.md](04-shtatnoe-raspisanie.md) | Ведение штатного расписания |
| 05 | [05-uchet-kadrov.md](05-uchet-kadrov.md) | Учет кадров и формирование фонда оплаты труда |
| 07 | [07-uderzhaniya.md](07-uderzhaniya.md) | Назначение удержаний |
| 09 | [09-otpuska-komandirovki.md](09-otpuska-komandirovki.md) | Отпуска, командировки и прочие отсутствия |
| 10 | [10-bolnichnye.md](10-bolnichnye.md) | Больничные листы и пособия ФСС |
| 11 | [11-uchet-vremeni.md](11-uchet-vremeni.md) | Учет времени |
| 13 | [13-naturalnye-dohody.md](13-naturalnye-dohody.md) | Натуральные и незарплатные доходы |
| 14 | [14-vvod-dannyh.md](14-vvod-dannyh.md) | Ввод данных для расчета зарплаты |
| 15 | [15-raschet-zarplaty.md](15-raschet-zarplaty.md) | Расчет зарплаты и взносов |
| 16 | [16-vyplata-zarplaty.md](16-vyplata-zarplaty.md) | Выплата зарплаты |
| 17 | [17-obmen-s-bankami.md](17-obmen-s-bankami.md) | Обмен с банками по зарплатным проектам |
| 18 | [18-ndfl.md](18-ndfl.md) | НДФЛ и отчетность в ФНС |
| 19 | [19-vznosy.md](19-vznosy.md) | Страховые взносы и отчетность в фонды |
| 20 | [20-buhgalterskiy-uchet.md](20-buhgalterskiy-uchet.md) | Формирование данных для бухгалтерского учета |
| 21 | [21-ispravlenie-periodov.md](21-ispravlenie-periodov.md) | Исправление прошлых периодов |
| 22 | [22-prochaya-otchetnost.md](22-prochaya-otchetnost.md) | Прочая отчетность |
| 23 | [23-bazovaya-versiya.md](23-bazovaya-versiya.md) | Особенности базовой версии |

### Приложения

- [pr1-nastroika-nachisleniy.md](pr1-nastroika-nachisleniy.md) — Настройка начислений и удержаний
- [pr2-administrirovanie.md](pr2-administrirovanie.md) — Сервисные возможности и администрирование

## Полезные советы

- Используй файл [quick-start.md](quick-start.md) как точку входа — там собраны самые частые задачи.
- При работе с начислениями и формулами в первую очередь смотри **Приложение 1**.
- Все важные файлы содержат YAML-метаданные (frontmatter) для лучшей индексации в Cursor.
- Можно использовать поиск по репозиторию или команду `@docs` в Cursor.

## Лицензия

Документация создана на основе официальных материалов 1С и предназначена для внутреннего использования.
