CTF на Физтехе
==============

Курс по подготовке к соревнованиям по компьютерной безопасности формата CTF.
Занятия проходят по средам в 20:00 в 324б ЛК.

Каждое занятие состоит из небольшой лекции и практики в виде решения задачек на определенную тему.
Предварительная подготовка не требуется.
Желательно наличие собственного компьютера, но пользоваться компьютерами в аудитории тоже возможно.

[Группа ВКонтакте](https://vk.com/mipt_ctf).

## Прошедшие занятия

**28 октября.** [Компьютерная безопасность. Что такое CTF. Attack-defence, jeopardy (task-based). УК РФ. Командная оболочка bash. Полезные команды и утилиты.](https://github.com/xairy/mipt-ctf/tree/master/01-intro/01-bash)

**11 ноября.** [Язык программирования Python. Основы синсаксиса. Некоторые полезные модули.](https://github.com/xairy/mipt-ctf/tree/master/01-intro/02-python)

**18 ноября.** [Менеджер пакетов Pip. Функция eval. Как выбраться из sandbox'а в Python с помощью эксплуатации функции eval.](https://github.com/xairy/mipt-ctf/tree/master/01-intro/03-eval)

**25 ноября.** [Кодировки. ASCII, ANSI Code Pages, Unicode, UTF-8/16/32. Base64. Классические шифры. Шифр Цезаря. Шифр простой замены. Частотный анализ. Шифр Вижинера. Индекс совпадений. Одноразовый блокнот. Современные симметричные шифры. DES, 3DES, AES.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/01-symmetric)

**2 декабря.** [Асимметричные шифры. Протокол Диффи-Хеллмана. RSA. Электронная цифровая подпись. Сертификат открытого ключа. Как работает HTTPS.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/02-asymmetric)

**24 февраля.** [Криптографические хеш-функции (MD5, SHA-1, SHA-2, SHA-3, bcrypt). Обзор реализации MD5. Length extension attack. Как хранить пароли пользователей. Как ломать хеши. John the Ripper, hashcat.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/03-hashing)

**2 марта.** [Стеганография. Основные понятия. Least Significant Bit (LSB). Контейнеры: текст, изображения, аудио, видео. Стегоанализ.](https://github.com/xairy/mipt-ctf/tree/master/02-crypto/04-stego)

## План на 2015-2016

Предварительный план того, что еще будет в этом году.

* Net
    * Введение в Веб. ip, port, DNS, netcat (-l), ping (of death), nmap. HTTP, HTTPS, HTTP headers, GET/POST/…, cookies. curl, python requests. Browser dev tools, plugins.
    * Анализ трафика. tcpdump. Wireshark. TODO.
    * SQL-инъекции. TODO.
    * Остальные типы инъекций (XPATH, Command, LDAP). XSS, CSRF. robots.txt, FPD. LFI, RFI, .htaccess, .htpasswd, .svn, .git. Dirbuster. MITM, DDOS.
* Binary
    * Ассемблер. Intel и AT&T синтаксисы. Регистры x86, x64. Основные команды. Flags register. Calling conventions. Inline gcc asm. NASM. Контест по NASM’у.
    * Дисассемблирование. Во что компилируется Hello world. Как работают кряки. Binary patching tools (bsdiff, bspatch, …). Утиные истории.
    * Инструменты для реверса. file, strings, readelf, objdump, strace, gdb. IDA Pro, Hopper. Qira. Как устроен ELF. C++, Go и Rust бинарники. Обфускация, деобфускация. Пакеры. Anti debugger. Visual RE.
    * Buffer overflow. Shellcode. Non-executable stack, stack canaries, ASLR, RELRO. checksec.sh. String format exploit. Overwriting PLT. Controlling gdb environment, keeping stdin open.
    * ROP. return-to-libc. gadgets, gadget finders. python struct, zio. Bypassing ASLR on x32. Heap buffer overflow.
