<h1>
    Homework 5
</h1>

<ul>
<li>
<strong>Индивидуально</strong>
Напишите функцию которая определяет тип треугольника, в зависимости от переданных (аргументами) сторон.

<br/>

<ol>
<li>
Если сумма длины 2-х любых сторон меньше 3-й стороны или равна ей, такого треугольника не существует.
</li>
<li>
Если сумма квадратов 2-х меньших сторон равна квадрату 3-й стороны - прямоугольный
</li>
<li>
Если сумма квадратов 2-х меньших сторон меньше квадрата 3-й стороны - тупоугольный
</li>
<li>
Если сумма квадратов 2-х меньших сторон больше квадрата 3-й стороны - остроугольный
</li>
</ol>

<br/>
Пример:

<code>triangle(2,4,6)</code> - 'не существует'
<br/>
<code>triangle(14,10,8)</code> - 'тупоугольный'
</li>

<li>
Напишите простой интерфейс(UI) для калькулятора. Поля результата, цифры, 4 символа оператора.
</li>

<li>
Реализуйте функционал калькулятора как минимум для оператора "+" и "-".
</li>

<li>
К калькулятору добавьте кнопку "Сохранить результат", по клику на который текущий результат операции
сохраняется в localStorage со случайно сгенерированным ключем.
</li>

<li>
При повторном заходе на страницу(localStorage НЕ пустой) выводите сообщение
"Результат последнего вычисления равен : "
</li>
</ul>
