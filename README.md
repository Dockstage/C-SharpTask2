Задание: 

Создать иерархию классов, состоящую из одного базового класса и двух классов-наследников. 

На что следует обратить внимание (за невыполнение оценка будет снижена): 

1) Обязательно классы реализуются в отдельном модуле. 
2) Программа оформляется в соответствии с требованиями к разработке ПО (отступы, названия переменных и т.п.). 
3) В конструкторе класса могут и должны быть настроены значения полей и свойств класса, но инициализация значений должна быть вне класса. Например, не следует в конструкторе класса задавать в списке какие-то значения, или какое-то имя студента, если они не передаются в конструктор через параметр.
4) Должен быть хотя-бы один вирутальный или абстрактный метод или свойство и их перекрытие.
5) Программу желательно сделать с использованием форм (WPF).
6) Необходимо придерживаться модели MVVM. 

Задача под №6:

Базовый класс: живое существо (свойство: скорость перемещения, абстрактные методы: двигаться, стоять)

Производные классы: пантера, собака, черепаха. реализовать методы двигаться и стоять. При этом неоднократный вызов, например, метода двигаться увеличивает скорость до максимально возможного и наоборот - вызов метода стоять, уменьшает вплоть до остановки. У пантеры и собаки должен быть метод - подать голос (определяется вызовом соответствующих событий), и пантера может залезть на дерево.

Для вашего удобства есть возможность запустить .exe файл при открытии файла "StartApp.bat". 
