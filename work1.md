# Инструкция #

*Git* - самая популярная система контроля версий проектов. Git хранит не файлы целиком, а отличия между ними. 

## Команды Git ##

* git --version - позволяет увидеть текущую версию установленной программы, если она установлена на компьютер. 

* git init - инициализация. Указываем папку, в которой git начнет отслеживать изменения. 

* git status -  показывает текущее состояние гита, есть ли изменения, которые нужно закомитить (сохранить). 

* git add -  добавляет содержимое рабочего католога в индекс для последующего коммита. Для добавления конкретного файла, указаываем команду *git add <имя_файла>* . Для добавления всех файлов проекта, нам потребуется команда *git add .* или *git add --all* .

* git commit - данная команда берет все данные, добавленные в индекс с помощью git add , и сохраняет их слепок во внутренней базе данный, а затем сдвигает указатель текущей ветки на этот слепок. 

* git log - журнал изменений. Помогает увидеть количество сохранений. 

* git reflog - выводит журнал ссылок для указателя активной ветки в данный момент. 

* git diff  - показывает разницу между текущим файлом и сохраненнным. 

* git checkout - переключение между версиями. Для возвращения к коммиту, в котором ведется работа, используем команду **git checkout master** . 

## **Синтаксис языка Markdown** ##

1. ### Блочные элементы

**Параграфы и разрывы строк** . Для того, чтобы создать параграф с использованием синтаксиса Markdown, достаточно отделить строки текста одной или более пустой строкой. 

**Заголовки** . В основном для заголовков используют символы "#" или же "=" / "-". Таким образом получается: 

# Заголовок 1

### Заголовок 2

###### Заголовок 3


**Цитаты** . Для обозначения цитат используется знак "больше" ">". 

>Например, цитата 1
>>Цитата 2
>>>Цитата 3

**Списки**. Бывают упорядоченные и неупорядоченные. 

Дл упорядоченных списков используется стандартная нумерация: 

1. Пример 1
2. Пример 2
3. Пример 3

Неупорядоченные списки выводятся следующим образом:
* Один
* Два
* Три

- Один
- Два
- Три

+ Один
+ Два
+ Три

**Горизонтальные линии (разделитеи)** . Для создания горизонатальной разделительной линии, требуется использовать звездочки или дефисы между строк. Например: 

Первая часть текста
***
Вторая часть текста

**Использование гиперссылок**

Для использования гиперссылок с использованием дополнительного текста ссылки, существует команда [пример](https://gb.ru)

Либо можно использовать [https://gb.ru]

