 Кейс 1: Установка и настройка SSH-сервера

## Выполненные команды:
```bash
sudo apt-get install openssh-server -y
sudo systemctl status ssh
sudo systemctl start ssh
sudo systemctl enable ssh
sudo ss -tlnp | grep :22

## Результат:

   -  SSH-сервер установлен

   -  Статус: Active: active (running)

   -  Автозапуск включен

   -  Порт 22 прослушивается
