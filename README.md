# Information

| Property     | Value                                              |
| ------------ | -------------------------------------------------- |
| ID           | `ext_c08c5b33`                                     |
| Type         | Add-on                                             |
| License      | GPL-3.0                                            |
| Language     | Russian                                            |
| Requirements | XenForo 2.1                                        |
| Authors      | [Yu Dunaev](mailto:hello@tails.im)               |

Определитель блокировки рекламы в браузере для [**XenForo**](https://xenforo.com).

## Install

1. [Загрузить](https://github.com/marketplace-xenforo/xenforo-ext-adblock-detector/tags) архив с последней версией расширения.
2. Распаковать содержимое архива в `/src/addons/Marketplace/ext_c08c5b33/`, сохраняя структуру директорий.
3. Зайти в **AdminCP**, далее *Add-ons*, и установить необходимое расширение.
3. Создать файл `ext.advert.min.js` в корне форума со следующим содержимым:

```js
"use strict";function extJS_runABDetector(){let a=document.createElement("div");a.id="runABDetector",a.style.display="none",document.body.appendChild(a)}extJS_runABDetector();
```

## Update

1. [Загрузить](https://github.com/marketplace-xenforo/xenforo-ext-adblock-detector/tags) архив с новой версией расширения.
2. Распаковать содержимое архива в `/src/addons/Marketplace/ext_c08c5b33/`, сохраняя структуру директорий, заменяя существующие файлы и папки.
3. Зайти в **AdminCP**, далее *Add-ons*, и обновить необходимое расширение.

## Donations

- [Donation Form](https://donation-form.github.io/)
