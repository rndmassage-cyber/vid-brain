---
title: Approval MOC
type: approval
status: approved
scope: Russian review layer for the English vault.
used_when: When the user wants to approve or quickly inspect the vault structure.
not_needed_when: The English vault is already accepted and in active use.
aliases: ["RU MOC", "Russian Approval Hub"]
tags: ["approval", "ru"]
related: ["00_Master_MOC"]
priority: medium
token_weight: light
---

# Approval MOC

## Что это за база
Это не энциклопедия по кинотехнике и не курс по реальной съёмке с разбором всех департаментов.  
Это рабочая база для агента, который должен понимать, **почему food commercial выглядит дорогим, аппетитным, динамичным и профессиональным**.

## Как устроена база
- `00_HUB` — навигация и правила использования
- `10_CORE` — ядро общих принципов
- `20_PLAYBOOKS` — модули по типам блюд
- `30_TEMPLATES` — шаблоны для сборки брифа, последовательности, continuity и промпта
- `90_RU_APPROVAL` — русский слой для быстрого чтения и утверждения

## Что грузить всегда
- `10_15s_Commercial_Architecture`
- `11_Visual_Deliciousness_and_Appetite_Principles`
- `16_Continuity_Consistency_and_State_Tracking`

## Что подключать по задаче
- свет / блики / пар / цвет → `13`
- ракурсы / движение / слоумо → `14`
- действия с едой → `15`
- подача / посуда / фон → `17`
- сенсорные cues → `18`
- вертикальный короткий ролик → `19`

## Когда подключать playbook
Когда блюдо имеет свою физическую логику:
- бургер и сэндвич → layers + squish
- пицца → crust + cut + cheese pull
- суп / лапша → steam + spoon / noodle lift
- суши → precision + translucency
- жареное → crunch + fracture
- wraps / tacos → folds + packed filling
- bowls / salads → fresh geometry
- desserts / drinks → glaze / ice / condensation

## Зачем нужны шаблоны
Они уменьшают количество токенов и помогают агенту сначала принять решения, а уже потом писать финальный промпт.
