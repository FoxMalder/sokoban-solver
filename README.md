# Игрушка "Сокобан" со встроенным решателем уровней
Исходный код к статье "AI на минималках: Пишем свой Сокобан и учим компьютер его решать".

![Компьютер играет в Сокобан](sokoban4.gif)

Собрать:
`mvn package`

Запустить в режиме игры:

`java -jar target\sokoban-solver-1.jar <путь до файла с уровнем>`

Запустить в режиме автоматического решения алгоритмом BFS:

`java -jar target\sokoban-solver-1.jar <путь до файла с уровнем> bfs`

Запустить в режиме автоматического решения алгоритмом А*:

`java -jar target\sokoban-solver-1.jar <путь до файла с уровнем> astar`

Примеры уровней в папке fields.
Обозначения:
* Решётка # это стена, через неё нельзя пройти и продвинуть ящик.
* Буква O это ящик.
* Буква X это метка, куда нужно переместить ящик.
* Собака @ означает игрока.
* Точка означает пустое место.
* Буква G это ящик на метке.

По любым вопросам:
* Telegram: @outofbound
* Email: e.gryaznov@innopolis.ru