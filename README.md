# Lab_tree

This code creates an interactive fractal tree visualization using p5.js (a JavaScript library for creative coding). Here's what it does:

Initial Setup:

Creates an 800x600 pixel canvas.

Adds a slider (0-180°) to control the branching angle of the tree.

Displays three pieces of information: current angle, zoom level, and recursion depth.

Drawing the Tree:

The tree is drawn using recursion (a function that calls itself).

Starts with a vertical trunk (150 pixels tall).

At each branch point, it splits into two smaller branches (67% of previous length) at the current angle set by the slider.

The recursion depth controls how many times the splitting happens.

Interactive Features:

Mouse wheel: Zooms in/out (scales the tree by 1.1x per wheel tick)

Mouse click: Increases the recursion depth (makes the tree more detailed)

Slider: Changes the branching angle in real-time

Technical Details:

Uses push()/pop() to save/restore drawing states during branching.

The zoom level affects both the tree size and line thickness.

The recursion stops when it reaches the maximum depth (initially 1, max 30).

The program keeps running in a loop (draw() function), constantly updating the display as you interact with it. It's essentially a simple but customizable fractal tree generator!


__________________________________________________________________________________________________________________________________________________________________________________



Этот код создаёт интерактивное фрактальное дерево с помощью библиотеки p5.js (для визуализации). Вот что он делает:

1. Настройка
Создаётся холст размером 800×600 пикселей.

Добавляется слайдер (от 0° до 180°), который меняет угол ветвления дерева.

На экране отображаются три параметра:

текущий угол ветвления,

масштаб (зум),

глубина рекурсии (сколько раз ветки делятся).

2. Как рисуется дерево?
Дерево строится рекурсивно (функция вызывает саму себя).

Начинается с вертикального ствола (высота 150 пикселей).

На каждом шаге ветка делится на две меньшие (67% от предыдущей длины) под углом, который задаёт слайдер.

Глубина рекурсии (maxDepth) определяет, сколько раз ветки будут делиться.

3. Интерактивность
Колёсико мыши – увеличивает или уменьшает масштаб (в 1.1 раза за прокрутку).

Клик мыши – добавляет новый уровень ветвления (дерево становится детальнее).

Слайдер – меняет угол между ветками в реальном времени.

4. Технические детали
push() и pop() сохраняют и восстанавливают положение системы координат при ветвлении.

Зум влияет не только на размер дерева, но и на толщину линий.

Рекурсия останавливается, когда достигается максимальная глубина (изначально 1, максимум 30).

Программа работает в бесконечном цикле (draw()), постоянно обновляя изображение при взаимодействии. По сути, это генератор фрактальных деревьев с настройками!


![image](https://github.com/user-attachments/assets/223e8220-cebd-438f-8ce2-1ce8386c923d)

![image](https://github.com/user-attachments/assets/9f2fade7-7481-4966-ab32-0e298f18a69b)

![image](https://github.com/user-attachments/assets/9b268b9b-6dce-44fd-8c52-3610642b7b53)

![image](https://github.com/user-attachments/assets/0de4eec8-8369-4217-8c1b-0d3ec4c5d6bc)


