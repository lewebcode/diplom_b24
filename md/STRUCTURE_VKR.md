# Распределение материалов по структуре ВКР (по шаблонам МИФИ и ГОСТ)

Структура приведена в соответствии с **МИФИ_Оформление_ВКР.pdf** и **Шаблон оформления ВКР 2026.pdf**.  
Файлы распределены по папкам в соответствии с разделами ВКР.

---

## Титульный лист

*Оформляется по шаблону кафедры (не md).*

---

## РЕФЕРАТ

| Папка | Файл |
|-------|------|
| **`referat/`** | `referat.md` — текст реферата (объём до 850 знаков, ключевые слова, объект, цель, метод, результаты, область применения) |

---

## СОДЕРЖАНИЕ

*Формируется автоматически по заголовкам разделов (стили Word / PDF).*

---

## ТЕРМИНЫ И ОПРЕДЕЛЕНИЯ / ПЕРЕЧЕНЬ СОКРАЩЕНИЙ И ОБОЗНАЧЕНИЙ

| Папка | Файл |
|-------|------|
| **`terminy/`** | `terminy_i_sokrashcheniya.md` — термины и сокращения |

---

## ВВЕДЕНИЕ

| Папка | Файлы |
|-------|--------|
| **`vvedenie/`** | `aktualnost.md`, `cel_raboty.md`, `zadachi_raboty.md`, `theoretical_and_practical_significance.md` |

---

## ОСНОВНАЯ ЧАСТЬ

### 1. Обзор предметной области

| Папка | Файлы |
|-------|--------|
| **`01_obzor_predmetnoj_oblasti/`** | `russian_banks_solutions.md`, `trade_sectors_applicability.md`, `evaluation_criteria.md`, папка **`banks/`** (vtb.md, sberbank.md, gazprombank.md, rosselkhozbank.md, rosbank.md и др.) |

### 2. Проектирование решения

| Папка | Файлы |
|-------|--------|
| **`02_proektirovanie_resheniya/`** | `vkr_stages.md`, `analysis.md` |

### 3. Моделирование решения

| Папка | Содержимое |
|-------|------------|
| **`03_modelirovanie_resheniya/`** | `README.md` — ссылки на материалы в `01_obzor_predmetnoj_oblasti/evaluation_criteria.md` и `02_proektirovanie_resheniya/vkr_stages.md` |

### 4. Реализация (программная)

| Папка | Содержимое |
|-------|------------|
| **`04_realizaciya/`** | `README.md` — ссылка на Этап 4 в `02_proektirovanie_resheniya/vkr_stages.md` |

### 5. Тестирование и исследование

| Папка | Содержимое |
|-------|------------|
| **`05_testirovanie_issledovanie/`** | `README.md` — ссылки на Этап 5 в `vkr_stages.md` и раздел 7 в `trade_sectors_applicability.md` |

---

## ЗАКЛЮЧЕНИЕ

| Папка | Файл |
|-------|------|
| **`zaklyuchenie/`** | `zaklyuchenie.md` |

---

## СПИСОК ИСПОЛЬЗОВАННЫХ ИСТОЧНИКОВ

| Папка | Файл |
|-------|------|
| **`istochniki/`** | `literatura.md` |

---

## ПРИЛОЖЕНИЯ

| Папка | Файлы |
|-------|--------|
| **`prilozheniya/`** | `kalendarnyj_plan.md`, `analysis.md` |

---

## Текущая структура папок `md/`

```
md/
├── STRUCTURE_VKR.md          ← этот файл (навигация по структуре ВКР)
├── referat/
│   └── referat.md
├── terminy/
│   └── terminy_i_sokrashcheniya.md
├── vvedenie/
│   ├── aktualnost.md
│   ├── cel_raboty.md
│   ├── zadachi_raboty.md
│   └── theoretical_and_practical_significance.md
├── 01_obzor_predmetnoj_oblasti/
│   ├── russian_banks_solutions.md
│   ├── trade_sectors_applicability.md
│   ├── evaluation_criteria.md
│   └── banks/
│       ├── vtb.md
│       ├── sberbank.md
│       ├── gazprombank.md
│       ├── rosselkhozbank.md
│       └── rosbank.md
├── 02_proektirovanie_resheniya/
│   ├── vkr_stages.md
│   └── analysis.md
├── 03_modelirovanie_resheniya/
│   └── README.md
├── 04_realizaciya/
│   └── README.md
├── 05_testirovanie_issledovanie/
│   └── README.md
├── zaklyuchenie/
│   └── zaklyuchenie.md
├── istochniki/
│   └── literatura.md
└── prilozheniya/
    ├── kalendarnyj_plan.md
    └── analysis.md
```
