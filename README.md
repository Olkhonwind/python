Для запуска файлы: englishbook (текст на английском языке), filename2 (на русском языке). Если в строке 43 указать encoding='utf8', то при запуске русcкоязычного файла выходит ошибка:

Traceback (most recent call last):
  File "C:\Users\Александр\PycharmProjects\pythonProject\venv\15.4.py", line 43, in <module>
    fileText = f.read()
               ^^^^^^^^
  File "<frozen codecs>", line 322, in decode
UnicodeDecodeError: 'utf-8' codec can't decode byte 0xce in position 0: invalid continuation byte

Почему так?! Python 3.11
