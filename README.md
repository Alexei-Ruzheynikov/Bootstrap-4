# Bootstrap-4

# Подключение и NavBar

Подключаем стили и скрипты, а так же тэг viewport(обязательный).
Для локального подключения в css подключаем:

<link rel="stylesheet" href="css/bootstrap.min.css" />

Это полный минифицированыый css со всеми свойствами bootstrap 4.
Дла js:

<script defer="" src="js/jquery-3.6.0.min.js"></script>

    <script defer="" src="js/bootstrap.bundle.min.js"></script>

Это jquery и js bootsrapa 4 включающий в себя poper библиотеку, которая нужна для его работы.

# Класс container -

Обязательный для построения сетки(у него есть максимальная ширина).
А класс container-fluid имеет ширину 100%

Классы
1).navbar-brand - для названия компании или логотипа. (Лучше использовать ссылку, внутри которой можно разместить название или img)
2).navbar-toggler - кнопка button для мобильных (используется вместе с плагином collapse)
.navbar-toggler-icon - какая-то иконка бургера
3).collapse и .navbar-collapse - для открытия и скрытия содержимого навигации в точке останова ( точка останова это .navbar-expand-lg - >= 992px)
4).navbar-nav - для навигации, включает поддержку выпадающих списков - для тэга ul
5).form-inline - для любых элементов управления и действий формы
6)Утилита colors - .bg-light -значит белый background-color
Утилита spacing - отвечает за расстояние, например
.my-2 - margin по y 2 = .5 rem для менее 576px
.my-lg-0 - для >=992px
7)Дочерние элементы .navbar по умолчанию спользуют justify-content: space-between;
8)Утилиты flex: .d-flex, .flex-row, .flex-column, .justify-content-start, .justify-content-end, .justify-content-center, .justify-content-between, .justify-content-around, .align-items-start, .align-items-end, .align-items-center и т д 9) .fixed-top рядом с .navbar - фиксированное меню сверху

10. Класс .navbar-nav-scroll делает вертикальную прокрутку для меню в адаптиве.

11. Класс .navbar-expand-lg - не сворачивает меню на lg и выше
