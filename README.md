# OpenVPN-installer
OpenVPN install script. Secure OpenVPN server installer for Debian, Ubuntu, CentOS, Amazon Linux 2, Fedora, Oracle Linux 8, Arch Linux, Rocky Linux and AlmaLinux.

Исходник кода взят отсюда

> github.com/angristan/openvpn-install

Версия скрипта 2022 год

Ручной скрипт установки OpenVPN на различные сервера с возможностью выбора типа шифрования, DNS, ipv6 и других опций.

Я разобрал весь код и проверил на баги.

Код содержит ошибку, так же в коде используются не нужные повторения не влияющие на результат.

Баг срабатывает очень редко, если после инсталяции нет соединения к серверу, значит нужно переустановить повторно.

В коде нет опции мульти подключения, а так же не отключены логи.

Рекомендую использовать другой мой код одинарного или двойного впн для дебиана и убунты в котором правильно отключены все логи, добавлен параметр мультиподключения, совместим с OpenVPN до версии 2.4, правильно отключен ipv6, а так же выбран надежный метод шифрования.


