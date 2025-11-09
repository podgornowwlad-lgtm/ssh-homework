# Кейс 4: Работа с ключами SSH
## Выполненные команды:
```bash
ssh-keygen -t rsa -b 4096 -f /home/osboxes/.ssh/id_rsa_osboxes -N ""
ssh-copy-id -i /home/osboxes/.ssh/id_rsa_osboxes.pub osboxes@127.0.0.1
ssh -i /home/osboxes/.ssh/id_rsa_osboxes osboxes@127.0.0.1
Результат:

    Пара ключей RSA 4096 бит сгенерирована

    Публичный ключ добавлен на сервер

    Подключение без пароля работает
    
