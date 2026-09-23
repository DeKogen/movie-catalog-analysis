# Анализ каталога фильмов

Учебное задание на Python 3.12. Данные и функции находятся в `catalog_analysis.py`.
Скрипт печатает статистику каталога, топ-3 фильма и сведения о жанрах.
В конце показана работа циклов и генератора.

## Запуск

Нужен установленный [uv](https://docs.astral.sh/uv/getting-started/installation/).

```powershell
uv sync
uv run catalog_analysis.py
```

## Проверка кода

```powershell
uv run ruff check .
```

Ruff — единственная зависимость для разработки. В самом скрипте используется
только модуль `math`.
