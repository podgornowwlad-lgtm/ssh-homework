# Кейс 3: Копирование файлов с помощью SCP
## Выполненные команды:
```bash
echo "Тестовый файл для SCP" > example.txt
scp example.txt osboxes@127.0.0.1:/home/osboxes/
scp osboxes@127.0.0.1:/home/osboxes/example.txt downloaded_example.txt
diff example.txt downloaded_example.txt
md5sum example.txt downloaded_example.txt
Результат:

    Файлы успешно скопированы туда и обратно

    MD5 хеши совпадают: db12efdbedf85c0c5d24450afd8a2646

    Целостность данных подтверждена
