Основные различия стандартов языка C

1. C90 (ISO C90 / ANSI C)
   Принят в 1990 году.
   Первый стандарт языка C, официально известный как ANSI C.
   Основные особенности:
   Введение стандарта библиотеки C.
   Поддержка функции void и указателей на void.
   Введение типов данных signed и unsigned.
   Поддержка комментариев в стиле /* ... */.
   Отсутствие функции // для однострочных комментариев (добавлены в более поздних стандартах).
2. C99
   Принят в 1999 году.
   Существенно расширил и улучшил язык C.
   Основные изменения и улучшения:
   Введение новых ключевых слов (inline, restrict, _Bool).
   Поддержка однострочных комментариев // (взяты из C++).
   Поддержка переменных длины массивов (VLA).
   Введение стандартных целочисленных типов фиксированной ширины (stdint.h).
   Введение функции snprintf и улучшенная обработка математических функций.
   Поддержка сложных чисел с помощью заголовочного файла <complex.h>.
3. C11
   Принят в 2011 году.
   Введены улучшения для многопоточности и безопасности типов.
   Основные изменения и улучшения:
   Введение статических утверждений с помощью _Static_assert.
   Поддержка многопоточности через новый заголовочный файл <threads.h>.
   Введение атомарных операций с помощью заголовочного файла <stdatomic.h>.
   Новые функции для управления и обработки памяти (aligned_alloc).
   Добавлены типы char16_t и char32_t для поддержки Unicode.
   Введен тип generic с помощью _Generic для создания макросов типа.
4. C17 (ISO C17 / C18)
   Принят в 2017 году (хотя официально опубликован в 2018 году, он известен как C17).
   В основном исправление ошибок и незначительные улучшения в стандарт C11.
   Основные изменения:
   Исправления ошибок и недочетов, обнаруженных в стандарте C11.
   Не добавлено никаких новых функций или ключевых слов.
5. C23
   Ожидаемый стандарт, принят в 2023 году.
   Еще больше улучшений и обновлений для языка C.
   Основные изменения и улучшения:
   Улучшения для совместимости с C++ и добавление новых функциональных возможностей.
   Поддержка UTF-8 в исходном коде.
   Новые типы, функции и ключевые слова, улучшающие безопасность и удобство программирования.