# Шаблон репозитория для лабораторных работ по курсу Технологии программирования 2026

## Окружение

1. **JDK 17 или новее**: [скачать](https://adoptium.net/);
2. **IntelliJ IDEA Community**: [скачать](https://www.jetbrains.com/idea/download/).

## Как начать работу с проектом

Основной путь — **fork** этого шаблона (инструкция [тут](https://docs.github.com/ru/pull-requests/how-tos/work-with-forks/fork-a-repo)).

1. Сделайте fork к себе на GitHub.
2. Склонируйте **свой** fork (`origin` = ваш fork): в IDEA — New → Project from Version Control (URL вашего fork).
3. IDEA импортирует Maven-проект; после индексации можно работать.

В Project Structure: JDK 17+, Language level не ниже 17.

## Структура пакетов

Для каждой лабораторной работы выделен отдельный пакет:

| Пакет                   | Лаба   |
|-------------------------|--------|
| `org.misis.tp.lab2` | Лаба 2 |
| `org.misis.tp.lab3` | Лаба 3 |
| `org.misis.tp.lab4` | Лаба 4 |
| `org.misis.tp.lab5` | Лаба 5 |
| `org.misis.tp.lab6` | Лаба 6 |
| `org.misis.tp.lab7` | Лаба 7 |

В каждом пакете уже заготовлен `Main.java`.

## Как запустить код

1. Откройте нужный `Main.java` файл, например `org.misis.tp.lab2.Main`.
2. Нажмите зелёный ▶ сбоку от названия метода `main` или сделайте правый клик по классу → **Run 'Main.main()'**.
3. Результат выводится во вкладку Run.

## Сдача и обновления шаблона

Код коммитьте и пушьте в **свой fork** (не в общий шаблон), как в первой лабе.

Обновления из шаблона курса: на GitHub откройте свой fork → **Sync fork** (встроенная кнопка GitHub, upstream руками добавлять не нужно) → локально `git pull`.
