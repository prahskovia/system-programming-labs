Задание 1-3: Файловая система и права<br>
Требования:<br>
•Bash скрипты<br>
•Работа с правами доступа (chmod)<br>
•Запуск: chmod +x script.sh && ./script.sh<br>

Вариант 6: Создать директорию archive, 10 файлов внутри. Заархивировать: tar -czf<br>
archive.tar.gz archive/. Удалить archive. Распаковать и проверить<br>

Используемые команды:<br>
mkdir -p - создание директории <br>
echo - создание содержимого файлов<br>
chmod - изменение прав доступа к файлам<br>
tar -czf - создание сжатого tar-архива <br>
tar -xzf - распаковка сжатого tar-архива<br>
rm -rf - рекурсивное удаление директории<br>
ls -la - вывод подробной информации о файлах и директориях<br>
Запуск: chmod +x script.sh && ./script.sh<br>

Пример вывода:<br>
Проверка:<br>
total 0<br>
drwxrwxrwx 1 dafna dafna 512 Feb  5 15:46 .<br>
drwxrwxrwx 1 dafna dafna 512 Feb  5 18:00 ..<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file1.txt<br>
-rwxrwxrwx 1 dafna dafna   8 Feb  5 18:00 file10.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file2.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file3.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file4.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file5.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file6.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file7.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file8.txt<br>
-rwxrwxrwx 1 dafna dafna   7 Feb  5 18:00 file9.txt<br>
