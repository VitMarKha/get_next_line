# get_next_line

## Описание

get_next_line - второй проект в School 21. Будь то файл, стандартный ввод или даже сетевое соединение, вам всегда понадобится способ чтения содержимого построчно. Пришло время начать работу над этой функцией, которая будет необходима для ваших будущих проектов.

В этом проекте мы используем некоторые функции из libft, так же некоторые функции мы модифицируем.

Компилирование было с флагами: "gcc -Wall -Wextra -Werror".

Все файлы проходят на Norminette.

## my_test

Закидываем ``main.c`` и ``text.txt`` в папку с ``get_next_line``, после чего компилируем ``gcc -Wall -Wextra -Werror -D BUFFER_SIZE=32 get_next_line.c get_next_line_utils.c main.c``. Запускаем ``a.out``, так же можем проверить на лики с помощью команды ``leaks a.out``.
