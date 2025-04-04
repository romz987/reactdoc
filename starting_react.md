# REACT  

## Содержание  

### Общая информация  

[Полезные ссылки](#Полезные-ссылки)
[Vite - Инструмент Сборки](#Vite)
[Babel && SWC](#Babel-&&-SWC)

### Старт проекта  

[Инициализация проекта](#Инициализация-проекта)
[Архитектура проекта](#Архитектура-проекта)
[Структура проекта](#Структура-проекта)

----
## Полезные ссылки 


----
## Vite
Vite - это инструмент сборки frontend приложений  
Обеспечивает:  

    1. Мгновенную загрузку в dev-режиме за счёт ESM (модулей в браузере).
    2. Быструю сборку благодаря esbuild
    3. Горячую перезагрузку (HMR) без лагов

----
## Babel && SWC  
Babel и SWC это инструменты транспиляции кода.  
SWC работает быстрее чем Babel.  
**Транспиляция — это процесс преобразования кода из одного стандарта в другой на том же языке.**

Пример:  

    Современный JS (ES6+ → старый JS (ES5) для поддержки старых браузеров.  
    JSX → чистый JavaScript (React-компоненты превращаются в React.createElement).  

Babel и SWC как раз занимаются этим — преобразуют код, чтобы он работал в нужной среде. 
SWC написан на Rust.
Babel написан на JavaScrpit.

----
## Инициализация проекта
1. Node.js   

    `node -v`  
    `npm -v`

2. Создание проекта:  

    `npm create vite@latest <app_name>`
    Выбираем React
    Выбираем JavaScript + SWC

3. Установка зависимостей:  

    cd <app_name>
    npm install

4. Старт:  

    npm run dev

5. [ОПЦИОНАЛЬНО] Удаляем всё лишнее


6. [ОПЦИОНАЛЬНО] Установка redux:  

    npm install @reduxjs/toolkit react-redux
    далее, создаем хранилище и настраиваем Provider

7. [ОПЦИОНАЛЬНО] Установка React-Router:  

    npm install react-router-dom
