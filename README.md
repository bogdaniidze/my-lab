# Лабораторная работа "Команда grep"
 Команда grep — это мощный инструмент в Unix-подобных операционных системах, используемый для поиска текстовых строк, соответствующих заданному шаблону. Она позволяет фильтровать данные и находить нужную информацию в текстовых файлах. В этой лабораторной работе мы рассмотрим основы работы с grep, выполним простое задание и решим практическую задачу.
## Использование grep для поиска строки в файле.
1. Введите следующую команду, чтобы создать файл text.txt и добавить в него несколько строк текста:
```
echo -e "Privet\privet\Alexander\15ballovzalaby\prosto\shik)" > text.txt
 ```
2. Используйте команду grep для поиска строки "prosto" в файле text.txt.:
```
grep "prosto" text.txt
```
Эта команда выведет все строки из файла, содержащие слово "prosto".

3. Попробуйте выполнить поиск с опцией -i, чтобы игнорировать регистр:
```
grep -i "privet" text.txt
```
Команда выведет "Privet" и "privet"

## Задача на выполнение.
Найти в английской версии стихотворения "Я помню чудное мгновение" Пушкина A.C. все слова "And" и их количество с помощью команд в терминале.
