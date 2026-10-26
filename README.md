# EME-L расширение Visual Studio Code
Расширение [Visual Studio Code](https://code.visualstudio.com/) для подсветки синтаксиса и вставки шаблонов кода языка EME-L.


## Начать использование

-   **Шаг 1.** [Установите EME-L расширение для Visual Studio Code](https://code.visualstudio.com/docs/editor/extension-gallery).

<img src=https://raw.githubusercontent.com/LeONTheProfess/vscode-emeltools/master/images/emel_install.gif width=500 height=300>

-   **Шаг 2.** Откройте или создайте emel файл и можно начинать писать код!

## Шаблоны кода

Начните вводить префикс шаблона в `.emel` файле и выберите нужный вариант из списка автодополнения. Доступны шаблоны для `If`, `For`, `While`, `Loop`, `Switch`, обработки query через `Select`, объявления метода и API-обработчика `GetTemplate`, а также комментариев.

Однострочные комментарии начинаются с апострофа (`'`), блочные — с `/*` и заканчиваются `*/`.


## Настройка среды разработки

-   Выберете в статус-баре язык разработки и можно приступать к редактированию кода.

<img src=https://raw.githubusercontent.com/LeONTheProfess/vscode-emeltools/master/images/emel_work.gif width=634 height=313>

## Сборка VSIX

Установите зависимости командой `npm install`, затем выполните `npm run package`.
Файл `.vsix` появится в корне проекта; VSCE автоматически создаст внутри него
`extension.vsixmanifest`.
