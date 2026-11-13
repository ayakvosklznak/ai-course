# ai-course

Курсы по работе с AI-агентами в инженерной практике. В репозитории два учебных продукта и один архив.

## Продукты

| Продукт | Каталог | Аудитория | Статус |
|---|---|---|---|
| Обобщённый курс | [content/course-unified](content/course-unified/index.md) | Разработчики, QA-инженеры, DevOps/SRE, аналитики, менеджеры | `draft` v0.2, основной продукт |
| Базовый курс | [content/course](content/course/index.md) | Системные, бизнес-, продуктовые и дата-аналитики | `published` v1.0.1 |
| Архив | [docs/archive/course-v1.0.1](docs/archive/course-v1.0.1/README.md) | — | `archived`, только чтение |

Учебный текст правится только в `content/`. Архив не правится. Слои репозитория, роли каталогов и правила работы — в [docs/STRUCTURE.md](docs/STRUCTURE.md).

## Обобщённый курс

Основной продукт: один метод для всех ролей. Часть 0 с быстрым стартом, ядро из 14 глав, пять ролевых треков, шаблоны, квизы и итоговая работа.

| Блок | Время | Результат |
|---|---:|---|
| Часть 0. Быстрый старт | 1,5 ч | Первый артефакт и коммит |
| Части I–IV. Ядро | 17 ч | Контекст, правила, артефакты, процесс |
| Сквозная практика | 3 ч | Пакет артефактов и ревью |
| Часть V. Ролевой трек | 2–3 ч | Артефакты своей роли |

Основные ссылки:

- [Главная страница курса](content/course-unified/index.md)
- [Быстрый старт на 90 минут](content/course-unified/part-0/quick-start.md)
- [Библиотека шаблонов](content/course-unified/templates/README.md)
- [Проверки и рубрика итоговой работы](content/course-unified/assessments/README.md)
- [Карта переиспользования базовых глав](content/course-unified/source-map.md)

## Базовый курс: издание для аналитиков

Тот же метод, написанный для аналитиков. Актуальная версия — по главам, с метаданными.

[Оглавление курса](content/course/index.md)

### Часть I. Рабочая среда

[Индекс части](content/course/part-1/index.md)

- [Глава 1. Как устроена работа аналитика с AI-агентом](content/course/part-1/chapter-01.md)
- [Глава 2. Установка и настройка OpenCode](content/course/part-1/chapter-02.md)
- [Глава 3. Git и безопасная работа с файлами](content/course/part-1/chapter-03.md)

### Часть II. Контекст и поведение агента

[Индекс части](content/course/part-2/index.md)

- [Глава 4. Репозиторий как источник контекста](content/course/part-2/chapter-04.md)
- [Глава 5. Rules и проектные инструкции](content/course/part-2/chapter-05.md)
- [Глава 6. Skills: повторяемые сценарии работы](content/course/part-2/chapter-06.md)
- [Глава 7. MCP: подключение внешних источников и инструментов](content/course/part-2/chapter-07.md)

### Часть III. Инженерия аналитических артефактов

[Индекс части](content/course/part-3/index.md)

- [Глава 8. Требования: от размытой идеи к проверяемой постановке](content/course/part-3/chapter-08.md)
- [Глава 9. Спецификации и SDD](content/course/part-3/chapter-09.md)
- [Глава 10. Rules, Spec и ADR: как не запутаться в документах](content/course/part-3/chapter-10.md)
- [Глава 11. ИИ для разных специализаций аналитика](content/course/part-3/chapter-11.md)

### Часть IV. Собираем командный процесс

[Индекс части](content/course/part-4/index.md)

- [Глава 12. SDD на практике: от запроса до ревью](content/course/part-4/chapter-12.md)
- [Глава 13. Как организовать работу команды с ИИ](content/course/part-4/chapter-13.md)
- [Глава 14. Безопасность, ограничения и итоговая сборка](content/course/part-4/chapter-14.md)
- [Сквозная практика и ревью](content/course/part-4/practice.md)

## Архив

[docs/archive/course-v1.0.1](docs/archive/course-v1.0.1/README.md) — замороженный снимок базового курса v1.0.1 в четырёх файлах-«книгах». Не правится, используется для истории и сравнения формулировок.

## Планы

- [docs/plan/plan_unified.md](docs/plan/plan_unified.md) — замысел обобщённого курса
- [docs/plan/plan_of_the_course.md](docs/plan/plan_of_the_course.md) — замысел базового курса

## Продуктовая упаковка

- [docs/product/offer.md](docs/product/offer.md) — позиционирование, аудитория, издания, цены-гипотезы, каналы, метрики, план запуска
- [docs/product/landing.md](docs/product/landing.md) — черновик продающей страницы: оффер, программа, тарифы, FAQ, CTA

## Структура репозитория

```text
ai-course/
├── README.md
├── docs/                     рабочие документы
│   ├── STRUCTURE.md
│   ├── plan/                 замысел курсов
│   ├── archive/              снимок v1.0.1
│   ├── product/              упаковка и продажи
│   └── useful_links.md
└── content/                  учебный текст
    ├── course/               базовый курс
    └── course-unified/       обобщённый курс
```

## Карта файлов обобщённого курса

Кто за что отвечает и что производит.

### Верхний уровень

| Файл | За что отвечает |
|---|---|
| [content/course-unified/index.md](content/course-unified/index.md) | Главная страница: обещание, аудитория, «кому не подходит», карта курса, издания, ролевые маршруты, итоговые артефакты |
| [content/course-unified/source-map.md](content/course-unified/source-map.md) | Авторская карта: что взято из базового курса, что заменено, правила адаптации, статус и список недоделанного |
| [README.md](README.md) | Точка входа в репозиторий: продукты, ссылки, структура, карта файлов |

### Часть 0. Вход и быстрый результат

| Файл | За что отвечает |
|---|---|
| [part-0/index.md](content/course-unified/part-0/index.md) | Зачем нужен быстрый старт, что входит в часть и в каком порядке проходить |
| [quick-start.md](content/course-unified/part-0/quick-start.md) | Сценарий на 90 минут: окружение → репозиторий → обзор проекта → `AGENTS.md` → первая задача → diff → коммит → мини-квиз |
| [setup-guide.md](content/course-unified/part-0/setup-guide.md) | Установка, подключение модели, разрешения, проверка окружения, диагностика |
| [readiness.md](content/course-unified/part-0/readiness.md) | Входной чек-лист: можно ли начинать курс и чего не хватает |
| [git-primer.md](content/course-unified/part-0/git-primer.md) | Минимум Git: `status`, `diff`, `add`, `commit`, `restore`, безопасные эксперименты |

### Части I–IV. Ядро курса

В каждой части есть `index.md` (задача части, таблица глав, результаты), `summary.md` (чек-лист итогов) и главы.

| Файл | За что отвечает |
|---|---|
| `part-N/index.md` | Рамка части: зачем она, сколько времени, что должно получиться |
| [chapter-01.md](content/course-unified/part-1/chapter-01.md) | Модель, чат и агент; уровни действий; критерии делегирования |
| [chapter-02.md](content/course-unified/part-1/chapter-02.md) | Установка и настройка CLI-агента, модель, разрешения, диагностика |
| [chapter-03.md](content/course-unified/part-1/chapter-03.md) | Git, diff, коммиты, откат, защита от секретов |
| [chapter-04.md](content/course-unified/part-2/chapter-04.md) | Репозиторий как источник контекста, источники истины, противоречия |
| [chapter-05.md](content/course-unified/part-2/chapter-05.md) | Rules, `AGENTS.md`, границы и проверка соблюдения правил |
| [chapter-06.md](content/course-unified/part-2/chapter-06.md) | Skills: структура, создание, безопасность сторонних сценариев |
| [chapter-07.md](content/course-unified/part-2/chapter-07.md) | MCP: внешние источники, минимальные привилегии, prompt injection |
| [chapter-08.md](content/course-unified/part-3/chapter-08.md) | Требования: цели, допущения, критерии приёмки, проверяемость |
| [chapter-09.md](content/course-unified/part-3/chapter-09.md) | Спецификации и SDD: структура, сценарии, трассируемость |
| [chapter-10.md](content/course-unified/part-3/chapter-10.md) | Rules, Spec и ADR: какой документ для чего, история решений |
| [chapter-11.md](content/course-unified/part-3/chapter-11.md) | Артефакты разработчика, QA, DevOps, аналитика и менеджера, общая схема проверки |
| [chapter-12.md](content/course-unified/part-4/chapter-12.md) | Полный цикл SDD: от запроса до ревью и обновления документации |
| [chapter-13.md](content/course-unified/part-4/chapter-13.md) | Командный процесс: передача контекста, владельцы артефактов, метрики |
| [chapter-14.md](content/course-unified/part-4/chapter-14.md) | Безопасность: данные, секреты, MCP, prompt injection, сборка среды |
| [part-4/practice.md](content/course-unified/part-4/practice.md) | Сквозная практика: сценарий, пакет артефактов, критерии оценки, саморевью |

### Часть V. Ролевые треки

| Файл | За что отвечает |
|---|---|
| [part-5/index.md](content/course-unified/part-5/index.md) | Как выбрать один трек и чем трек отличается от ядра |
| [track-developer.md](content/course-unified/part-5/track-developer.md) | Разработчик: план изменения, тесты, diff, контракты, PR |
| [track-qa.md](content/course-unified/part-5/track-qa.md) | QA: тест-план, граничные сценарии, дефект-репорт, доказательства |
| [track-devops.md](content/course-unified/part-5/track-devops.md) | DevOps/SRE: IaC, пайплайн, runbook, откат, наблюдаемость |
| [track-analyst.md](content/course-unified/part-5/track-analyst.md) | Аналитик: карта проекта, требования, спецификация, ADR |
| [track-manager.md](content/course-unified/part-5/track-manager.md) | Менеджер и продукт: границы, риски, решения, change request |
| [part-5/summary.md](content/course-unified/part-5/summary.md) | Итог трека и общий вывод курса |

### Шаблоны

| Файл | За что отвечает |
|---|---|
| [templates/README.md](content/course-unified/templates/README.md) | Навигация по шаблонам, бесплатный набор и правила заполнения |
| [AGENTS.template.md](content/course-unified/templates/AGENTS.template.md) | Форма правил агента; копируется в проект как `AGENTS.md` |
| [requirements.md](content/course-unified/templates/requirements.md) | Требования, источники, критерии приёмки, допущения, вопросы |
| [specification.md](content/course-unified/templates/specification.md) | Спецификация поведения: границы, сценарии, правила, проверки |
| [adr.md](content/course-unified/templates/adr.md) | Архитектурное решение: контекст, варианты, решение, последствия |
| [test-plan.md](content/course-unified/templates/test-plan.md) | План проверок, риски, окружения, доказательства |
| [runbook.md](content/course-unified/templates/runbook.md) | Эксплуатация: симптомы, диагностика, действия, откат |
| [pr-description.md](content/course-unified/templates/pr-description.md) | Передача изменений на ревью: что, зачем, как проверено |
| [risk-register.md](content/course-unified/templates/risk-register.md) | Реестр рисков с владельцами и мерами |
| [change-request.md](content/course-unified/templates/change-request.md) | Изменение объёма или требований и его влияние |
| [review-checklist.md](content/course-unified/templates/review-checklist.md) | Универсальный чек-лист ревью артефактов |

### Проверки и оценивание

| Файл | За что отвечает |
|---|---|
| [assessments/README.md](content/course-unified/assessments/README.md) | Состав проверок, порядок использования, обозначения форматов ответа |
| `chapter-01-quiz.md` … `chapter-14-quiz.md` | По одному квизу на главу: 7 вопросов, ответы с разбором, шкала |
| [quiz-template.md](content/course-unified/assessments/quiz-template.md) | Формат нового квиза, включая пометку `(несколько ответов)` |
| [progress-tracker.md](content/course-unified/assessments/progress-tracker.md) | Таблица результатов по главам и темы для повторения |
| [capstone-rubric.md](content/course-unified/assessments/capstone-rubric.md) | Итоговая работа: ролевые варианты, критерии, пороги, сертификат |

## Кто чем пользуется

- **Ученик:** главная страница курса, часть 0, части I–V, шаблоны, квизы, итоговая работа.
- **Преподаватель:** те же материалы, состав проверок, рубрика итоговой работы, шаблоны.
- **Автор и редактор:** карта переиспользования, план курса.
- **Маркетинг и продажи:** описание продукта и черновик лендинга.

## Замечание

`templates/AGENTS.template.md` назван с суффиксом `.template.md` специально: иначе агент воспринял бы шаблон как реальные инструкции проекта.