Данный проект создан для обучения русскому языку жестов различных групп людей ( детей и их родителей, слабослышашщих и их круга общения). В данном веб-приложении на данный момент есть 2 темы, в каждой из которых по 5 слов (жестов). Изучая каждое слово показывается ряд изображений, пояснение слова и видео соотвествующего жества. Данный метод обучены подходит как для детей, так и для взрослых.

Фаил start.html - начало веб-приложения (с него начинается запуск)

После идет фаил themes.html - каталог тем 

Файлы начинающиеся на img - сраницы с изоброжениями

Файлы начинающиеся на otv - с видео и блоками текста
  
  Логика расположения файлов (привязки друг к другу) 
у папок и файлов есть нумерация, например : img11 (первая цифра это номер темы, вторая номер "задания") т.е. данная страничка из 1ой темы и это 1ое задание.
К каждой страничке типа img__ есть папка с jpg файлами, номер такой папки совпадает с номером img (например для img11 это папка 11)
Внутри каждой папки лежат нумерованные файлы (111, 112, 113,114), данная нумерация нужна для порядка загрузки изображений на странице img__

В папке video содержатся файлы MP4, которые загружаются в файлы otv__ (но название видео не зависит от номера файла otv__, но между ними установлена свзь)

