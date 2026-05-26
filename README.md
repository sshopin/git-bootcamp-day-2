# git-bootcamp-day-2

Тестовый проект курса: [Интенсив по погружению в GIT. Поток 1](https://slurm.io/git-intensive).
Материалы Дня 2.

Содержание:
- [TODO](#todo)
- [Раздел 1](#раздел-1)
- [Плагины](#плагины)
- [Используемые инструменты](#используемые-инструменты)
- [Настройка](#Конфигурация)
- [Итоги](#итоги)

## TODO

Разобраться  с инструментами:
1. HumanifyJS
1. re-Script

> LLM-модели:
> 1. DeepSeek-Coder-V2
> 1. Qwen2.5-Coder 32B

Дальше снова идет список:
1. элемент списка

## Раздел 1

Большой текстовый раздел. Здесь должно быть что-то написано.

Ниже приведена какая-то рабочая таблица:
| Заголовок 1 | Заголовок 2 | Заголовок 3 |
|-------------|-------------|-------------|
| Ячейка 1    | **Ячейка 2**    | ~~Ячейка 3~~    |
| Ячейка 4    | *Ячейка 5*    | Ячейка 6    |


## Плагины

В Obsidian установлены плагины:
- Markdown Formatting Assistant
- Trim whitespace (хоткей `Alt+T`)
- Remove Newlines (хоткей `Alt+B`)
- Scrolling

## Используемые инструменты

Используется утилита [nbdime](https://nbdime.readthedocs.io/en/latest/)


```bash
pipx install nbdime

# в репозитории
nbdime config-git --enable

# Глобально (для всех репозиториев пользователя)
nbdime config-git --enable --global
```

## Конфигурация

Конфигурационный файл `~/.jupyter/nbdime_config.json`:
```JSON
{
  "GitDiff": {
    "Ignore": {
      "/cells/*/outputs": true,
      "/cells/*/execution_count": true,
      "/cells/*/id": true,
      "/cells/*/metadata": true,
      "/metadata": true
    },
    "details": false
  }
}
```

## Итоги

- [x] что-то выполнено
- [ ] что-в работе
- [ ] ещё даже не начато

## Лицензия

MIT — см. [LICENSE](LICENSE).


---