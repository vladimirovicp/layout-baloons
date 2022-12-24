# Курс: Верстка и создание веб сайтов 2022 - Продвинутый уровень! 

## layout-baloons

> * [Туры на воздушных шарах Figma](https://www.figma.com/file/ybWpKHKlfkpcCul34DwjzO/%D0%9F%D0%B5%D1%80%D0%B2%D1%8B%D0%B9-%D0%BC%D0%B0%D0%BA%D0%B5%D1%82-%D1%81-float?node-id=0%3A1)
> * [baloons Figma](https://www.figma.com/file/mcesUlxmkTT6y7OJ60CaEO/baloons?node-id=1%3A16&t=nnHAKfZxx0Qv5IiD-0)

> * Live Sass Compiler
> * [Генератор кода Clip-path](https://bennettfeely.com/clippy/)
> * [Методология БЭМ](https://ru.bem.info/methodology/)
> * [все про CSS анимацию @kayframe](https://developer.mozilla.org/ru/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
> * [Нормализация поведения анимации](https://developer.mozilla.org/ru/docs/Web/CSS/backface-visibility)
> * [Все о свойстве transform](https://developer.mozilla.org/ru/docs/Web/CSS/transform)
> * [Символы HTML](https://css-tricks.com/snippets/html/glyphs/)
> * [Все о селекторах](https://itchief.ru/html-and-css/selectors)
> * [Создание иконочного шрифта](https://icomoon.io/)
> * [Как работает свойство perspective](https://webformyself.com/kak-rabotaet-css-perspective/)

## Настройки Плагина SASS - Live Sass Compiler

> *  Файл -> настройки -> параметры
> * ищем Extensions(расширения), а там Live Sass Compiler
> * Live Sass Compile › Settings: Formats
>    Set your exported CSS Styles, Formats & save location.
>    изменить setings.json
>
>    {
>    "liveSassCompile.settings.formats": [
>    
>        {
>            "format": "expanded",
>            "extensionName": ".css",
>            "savePath": null,
>            "savePathReplacementPairs": null
>        }
>    ]
>}
>
> меняем на
>
>{
>    "liveSassCompile.settings.formats": [
>
>        {
>            "format": "expanded",
>            "extensionName": ".css",
>            "savePath": "/css",
>            "savePathReplacementPairs": null
>        }
>    ]
>}
