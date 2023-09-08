# vtoroe_dyhanie(Второе дыхание)


### Описание

Заказчик - благотворительный фонд помощи людям в сложной жизненной ситуации “Второе дыхание”.
Проект представляет собой телеграмм бота.

**Задачи бота:**

- оптимизация процесса онбординга для новых коллег фонда Второе дыхание
- сокращение рабочего времени hr на ответы на одинаковые вопросы коллег
- контроль эмоционального состояния коллег
- сбор аналитики

**Бот предоставляет новым сотрудникам фонда:**

- необходимую информацию, ресурсы
- ответы на вопросы
- кадровые документы
- напоминания

**Бот реализует следующие функции:**

- Предоставление информации о фонде (общая, ссылка на сайт) 
- Предоставление общей информации о проекте (адрес, директор, оргструктура) 
- Ответы на часто задаваемые вопросы 
- Помощь с документами и формами (присылать документ по выбору из меню) 
- Собирает информацию для аналитики 
- Отложенное отправление напоминаний для конкретных сотрудников
- Периодический опрос о самочувствии сотрудников

Целевая аудитория бота это новые и действующие сотрудники фонда. 
Суть проекта в быстром и удобном поиске и сборе информации для сотрудников.

## Stack

Инструменты: Python 3.11, Docker, Docker-Compose, Python-telegram-bot 20.5

Система контроля версий: Poetry 1.6.1

### Установка, Как запустить проект:

Клонируйте репозиторий:

```
git clone git@github.com:Studio-Yandex-Practicum/vtoroe_dyhanie.git
```

Перейдите в директорию проекта: 

```
cd vtoroe_dyhanie/
```

Инициализируйте создание директории виртуального окружения в проекте:

```
poetry config virtualenvs.in-project true
```

Создайте директорию виртуального окружения:

```
poetry install
```

Далее вы можете либо запустить виртуальное окружение самостоятельно:

```
poetry shell
```

Или воспользовавшись вот такой командой:

```
source .venv/bin/activate
```

Либо открыть проект в IDE, и IDE само найдёт нужную папку с интерпретатором и зависимостями и запустит виртуальное окружение.

Тимлид:

- [Яна Денисова](https://github.com/Yana-Denisova)

Проджект менеджер:

- [Кумова Татьяна]()

Команда разработки:

- [Александр Мамонов](https://github.com/Alex386386) 
- [Владимир Максимов](https://github.com/v-mcsimoff)
- [Мольков Андрей](https://github.com/MrProfessorCat)
- [Насибуллин Дмитрий](https://github.com/IlDezmond)
- [Андрей Киланов](https://github.com/AndyFebruary74)
- [Мария Ковалева](https://github.com/Maria50538810)
