---
title: "Активация Windows через Командную строку"
date: "2026-02-08"
draft: false
---

1. Открой CMD от имени администратора
Нажми Win → введи cmd → ПКМ → Запуск от имени администратора

2. Установи ключ Windows
slmgr /ipk XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
Пример:

slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
3. Укажи KMS-сервер
slmgr /skms kms.digiboy.ir
4. Активируй Windows
slmgr /ato
5. Проверка активации
slmgr /xpr
📋 KMS ключи Windows
Windows 10 Pro: W269N-WFGWX-YVC9B-4J6C9-T83GX
Windows 10 Home: TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
Windows 11 Pro: W269N-WFGWX-YVC9B-4J6C9-T83GX
Важно: без рабочего KMS-сервера активация не пройдёт!  


