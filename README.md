# Test_tasks
## Test tasks from MCST Elbrus internship

### 1  
Complete vimtutor

### 2.1  
Написать bash-скрипт, выводящий на экран текущее дерево каталогов в файловой системе, начиная с "/" с глубиной поиска "1" - то есть вывести только те каталоги, которые находятся в корне файловой системы.
### 2.2  
Написать bash-скрипт, выполняющий поиск в каталоге /usr/lib всех файлов, содержащих буквы qt в названии и вывести пути с именами этих файлов на экран.
### 2.3  
Написать скрипт, записывающий в переменную текущую дату при помощи команды "date", затем удалить из ее вывода, хранящегося в переменной, все двоеточия, после чего вывести получившуюся переменную на экран.
### 2.4  
Написать скрипт, который выводит второй столбец из списка всех установленных в системе пакетов (например, используя утилиту "dpkg" для Debian-подобных системы, либо другую утилиту при отсутствии "dpkg"). Столбец выводить при помощи "awk".
### 2.5  
Написать скрипт, объединяющий в себе содержимое предыдущих 4 скриптов, оформив их как функции.

### 3 
Написать программу на языке Си, состоящую из двух *.c файлов - в одном из них находится функция main(), в другом - функция обработки файла.
Также должен присутствовать заголовочный файл .h, в котором содержится протип функции обработки файла, подключаемый к файлу, содержащему main().
Компиляция производится при помощи Makefile, содержащего в себе цели "all" и "clean".
Алгоритм работы программы следующий:
Программе на вход в качестве подается текстовый файл, содержащий в себе строки текста - стихотворение В. Маяковского или И. Бродского на английском языке.
Программа записывает файл построчно в двусвязный список - структуру linked list. В структуре должны быть поля, в которых содержится: номер текущей строки, содержание текущей строки, указатель на предыдущую и следующую структуры.
После заполнения списка структур их необходимо вывести на экран.