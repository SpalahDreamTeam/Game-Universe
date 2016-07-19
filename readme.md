
Верстку выполнил с минимальным использованием классов и без использования HTML5 тегов для простоты работы с DOM. 

Для работы с DOM рекомендую смотреть саму верстку в файле index.html, а также эти заметки. 

схема записей тегов и классов, ид:

тег  класс;  тег  ид; 
div.class	 div#id

Опишу только необходимые блоки!


Корзина: a.basket
	Белый круг возле корзины: div.basketPoints

Боковая панель: div.aside
	Цена: div#price
		input[type="checkbox"]

	Жанр: div#genre
		input[type="checkbox"]

	Платформа: div#platform
		input[type="checkbox"]

Основной контент: div.main
	Каждый отдельный товар: a.mainItem
		Картинка: img
		Описание: div>ul>li
		Кнопка: div>button



