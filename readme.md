Инструкция для новичка в Git
Важные команды

GIT ADD ИМЯФАЙЛА #индексиреут файл для коммита
git commit -m "message" #производит коммит всех индексированных файлов
git push #добавляет на github

Хеш.

Таблица соответствия хеш → информация о коммите хранится в папке .git.
Основной идентификатор коммита — это его хеш.
Если посчитать хеш одного и того же файла (одним и тем же алгоритмом) на двух разных компьютерах, то результат будет гарантированно одинаковым.
Все хеши, а также таблицу соответствий хеш → информация о коммите Git хранит в папке .git.
