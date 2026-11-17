# Notification Platform

## Состав проекта

- `01_requirements.md` — ответы на задания 1–7.
- `02_rfc.md` — RFC по шаблону.
- `diagrams/a_container.puml` — C4 Container варианта 1.
- `diagrams/a_main.puml` — основной сценарий варианта 1.
- `diagrams/a_failover.puml` — failover варианта 1.
- `diagrams/b_container.puml` — C4 Container варианта 2.
- `diagrams/b_main.puml` — основной сценарий варианта 2.
- `diagrams/b_failover.puml` — failover варианта 2.

## Просмотр

Для получения SVG при установленном PlantUML:

    plantuml -charset UTF-8 -tsvg diagrams/*.puml

Для C4 используется стандартная библиотека PlantUML:
`!include <C4/C4_Container>`.
Для построения C4 также может потребоваться Graphviz.

## Покрытие задания

| Пункт | Где выполнен |
|---|---|
| 1. Функциональные требования | 01_requirements.md, раздел 1 |
| 2. Нефункциональные требования | 01_requirements.md, раздел 2 |
| 3. ASR | 01_requirements.md, раздел 3 |
| 4. Архитектурные вопросы | 01_requirements.md, раздел 4 |
| 5. Последствия ASR | 01_requirements.md, раздел 5 |
| 6. Неподходящие решения | 01_requirements.md, раздел 6 |
| 7. Неопределённости и риски | 01_requirements.md, раздел 7 |
| 8. RFC, два решения, расчёты и диаграммы | 02_rfc.md и diagrams/ |

SLO и характеристики являются проектными целями.
