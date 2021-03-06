Напишите реализацию игры жизнь на C++
<h3>Оглавление</h3>
<a href="#one">1. Теория</a><br>
<a href="#two">2. Правила</a><br>
<a href="#three">3. Пример работы</a><br>

<h3 id="one">Теория</h3>
Игра «Жизнь» — клеточный автомат, придуманный английским математиком Джоном Конвеем в 1970 году.

<h3 id="two">Правила</h3>
* Место действия этой игры — «вселенная» — это размеченная на клетки поверхность или плоскость — безграничная, ограниченная, или замкнутая (в пределе — бесконечная плоскость). <br>

* Каждая клетка на этой поверхности может находиться в двух состояниях: быть «живой» или быть «мёртвой» (пустой). Клетка имеет восемь соседей (окружающих клеток). <br>

* Распределение живых клеток в начале игры называется первым поколением. Каждое следующее поколение рассчитывается на основе предыдущего по таким правилам: <br>
&nbsp;&nbsp;&nbsp; - в пустой (мёртвой) клетке, рядом с которой ровно три живые клетки, зарождается жизнь<br>
&nbsp;&nbsp;&nbsp; - если у живой клетки есть две или три живые соседки, то эта клетка продолжает жить; в противном случае (если соседей меньше двух или больше трёх) клетка умирает («от одиночества» или «от перенаселённости»)<br>

* Игра прекращается, если на поле не останется ни одной «живой» клетки, если при очередном шаге ни одна из клеток не меняет своего состояния (складывается стабильная конфигурация) или если конфигурация на очередном шаге в точности (без сдвигов и поворотов) повторит себя же на одном из более ранних шагов (складывается периодическая конфигурация). <br>

* Игрок не принимает прямого участия в игре, а лишь расставляет или генерирует начальную конфигурацию «живых» клеток, которые затем взаимодействуют согласно правилам уже без его участия (он является наблюдателем). <br>

<h3 id="three">Пример работы</h3>
<img src="https://habrastorage.org/files/367/3ea/1de/3673ea1de70f4837a7a352573b8e28d9.gif"/>