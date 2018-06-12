## Краткое руководство

### Процесс сборки:

__.c / .cpp -> .asm -> .o -> .exe__

Препроцессор -> Компилятор -> Компоновщик / Линковщик |
------------------------------------------------------|

1. Препроцессор
> Выполнение директив препроцессора (#include, #define и т.д.)
2. Компилятор
> Перевод исходников в код ассемблера, далее в объектные файлы (имя_файла.o)
3. Компоновщик / Линковщик
> Компоновка всех получившихся объектных файлов в один и прописывание адресов памяти в коде.



Утилита | Команда | Выход |
--------|---------|-------|
gcc(C) | gcc main.c class.c | a.exe (по умол. имя всегда 'a') |
g++(C++) | g++ main.c class.c | a.exe|
