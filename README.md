# Pacemaker (водитель ритма)

В организмах существует множество участков являющихся [автоколебательными контурами](https://en.wikipedia.org/wiki/Autowave), часто именуемые «пейсмекером» (pacemaker) задающими ритмы, способных генерировать и поддерживать колебания. Их импульсы передаются по аксонам и вовлекают другие клетки в биологический ритмы [1], одним из ярких примеров может служить [водитель сердечного ритма](https://en.wikipedia.org/wiki/Sinoatrial_node) - участок сердечной мышцы, в котором генерируются импульсы, определяющие частоту сердечных сокращений [2].

Ниже на рисунке ниже приведены три интепритации нейроморфного пейсмекером:
- в форме соответствующего дифференциального уравнения гармонических колебаний с затуханием;
- соответвующее цитоархитектурное представление мозжечковых клеток, как структурного элемента нейрокомпьютера;
- вводимое базовое обозначение с указанием параметров параллельных волокон формирующих фазовое пространство параметров и кратковременную память.

<img src="https://drive.google.com/uc?export=view&id=12RLEPip5QlT-CclSGp1UPJQXaUri4Jvv" width="1000">

Подготовим модель на python с использованием библиотеки [pyglet](https://pyglet.org/) [3] и разверткой во времени. Применение pyglet предоставляющей объектно - ориентированный программный интерфейс для создания игр, является закономерным, так как цель многих игр создать модель реального мира отличительной чертой которого является время как непрерывный процесс.

<img src="https://drive.google.com/uc?export=view&id=1-p8M5DAO_2ymhiDWYNxeUxBVZnJwSXWF" width="900">

1. М. С. Гиляров, А. А. Бабаев, Г. Г. Винберг, Г. А. Заварзин и др. (1986) «Биологический энциклопедический словарь.» - 2-е изд., М.: Советская Энциклопедия.
2. А.А. Семенович, В.А. Переверзев. (2021) Нормальная физиология. Минск: Новое знание, 520 с.
3. https://pyglet.org/ - is a library for the Python programming language that provides an object-oriented application programming interface for the creation of games and other multimedia applications.
 
