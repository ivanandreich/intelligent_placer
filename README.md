# intelligent_placer

<h2>Постановка задачи</h2>
<h3>Входные данные:</h3>
-На вход задаётся многоугольник массивом с координатами вершин на естественной плоскости.<br>
-На вход задаётся фотография предметов на белом листе<br>
<h3>Требования к фотографии:</h3>
-Разрешение не менее 3000х4000px<br>
-Вертикальная ориентация<br>
-Каждый объект присутствует на фотографии в единственном экземпляре<br>
-Угол камеры ~0 градусов по отношению к поверхности, на которой лежат предметы<br>
<h3>10 изображений предметов</h3>

![avatar](examples/1.jpg)<br> й
![avatar](examples/2.jpg)<br>
![avatar](examples/3.jpg)<br>
![avatar](examples/4.jpg)<br>
![avatar](examples/5.jpg)<br>
![avatar](examples/6.jpg)<br>
![avatar](examples/7.jpg)<br>
![avatar](examples/8.jpg)<br>
![avatar](examples/9.jpg)<br>
![avatar](examples/10.jpg)<br>

<h3>Изображение фона</h3>

![avatar](examples/0.jpg)<br>

<small>Не судите строго, камера на телефоне разбита, перефоткаю потом на другую</small>


<h3>Примеры входных данных:</h3>
<b>Пример 1:</b><br>
Программа будет работать корректно, все предметы расположены независимо друг от друга, к тому же выпуклые оболочки их крайних точек не пересекются

![avatar](input_data/1.jpg)<br>

<b>Пример 2:</b><br>
Программа будет работать некорректно, либо выдаст ошибку. Один предмет перекрывает часть другого

![avatar](input_data/2.jpg)<br>

<b>Пример 3:</b><br>
Программа будет работать корректно. Интересный аспект данного случая состоит в том, что выпуклые оболочки крайних точек предметов пересекаются, при этом предметы не перекрывают друг друга

![avatar](input_data/3.jpg)<br>

<b>Пример 4:</b><br>
Программа будет работать корректно. Интересный аспект данного случая состоит в том, что выпуклые оболочки крайних точек предметов пересекаются, при этом предметы не перекрывают друг друга

![avatar](input_data/4.jpg)<br>

<b>Пример 5:</b><br>
Программа будет работать некорректно, либо выдаст ошибку. Один предмет перекрывает часть другого

![avatar](input_data/5.jpg)<br>

<b>Пример 6:</b><br>
Программа будет работать корректно. Интересный аспект данного случая состоит в том, что выпуклые оболочки крайних точек предметов пересекаются, при этом предметы не перекрывают друг друга

![avatar](input_data/6.jpg)<br>



