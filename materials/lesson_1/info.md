*   Python - потужна компьютерна мова программування, яка підтримує багато парадигм і оптимізована для забезпечення високої продуктивності програмістів, читаємості коду та якості програмного забазпечення.

*   Інтерпретатор - це різновид програми, яка виконує інші програми. Коли ви пишете програму на Python, інтерпретатор Python читає її і виконує інструкції, що містяться в ній. Фактично інтерпретатор є рівнем програмної логіки між вашим кодом і обладнанням комп'ютера.

*   Трансля́тор - програма, яка виконує перетворення чи іншу обробку текстів програм.

*   Є два основні способи виконання програм Python: інтерактивний і виконання файлів з кодом.

*   Коментарі - це пояснення для людини всередині тексту програми, транслятор їх ігнорує.
    Коментарі починаються зі спеціального символу: #

*   Символьний рядок - це набір символів заключений в подвійні або одинарні кавички:
    ```python
    "якийсь текст та символи%:??!("
    '212321'
    ```

*   Для виводу даних на екран використовують функцію print
    приклад:
    ```python
    >>> print("Україна починається з тебе.")
    Україна починається з тебе.
    >>> print("Любіть", "Україну,", "як", "сонце," "любіть,")
    Любіть Україну, як сонце,любіть,
    >>> print(1, 2, 3)
    1 2 3
    >>> print(1, 2, 3, sep='')
    123
    >>> print(1, 2, 3, sep='/')
    1/2/3
    >>> print("вивід без переводу курсору на новий рядок", end='')
    вивід без переводу курсору на новий рядок>>> 

    ```

*   При виводі кількох значень вони за змовчуванням розділяються пробілами, якщо це непотрібно треба додати іменований аргумент *sep=''*

*   За змовчуванням курсор переводиться на інший рядок, щоб цього запобігти потрібно додати іменований аргумент *end=''*