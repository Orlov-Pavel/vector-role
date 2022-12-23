Verctor-role
=========

Роль устанавливает ПО Vector.

Предварительные требования
------------

Предполагается что роль будет выполняться на deb-based дистрибутивах Linux (Debian, Ubuntu).

Переменные роли
--------------

В [переменных по умолчанию](./defaults/main.yml) указана версию ПО Vector 0.25.2, в случае необходимости её нужно изменить.

Зависимости
------------

Нет зависимостей

Пример плейбука с использованием роли
----------------
```
- name: Install Vector
  hosts: vector
  roles:
    - vector-role
```

License
-------

Free

Author Information
------------------

Сделано Павлом Орловым специально для занятия в Netology.
