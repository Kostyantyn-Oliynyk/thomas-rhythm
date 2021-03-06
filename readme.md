# Landing page thomas-rhythm

Технології що використовуються в проекті
-----------------------------------
	Бібліотека JavaScript - jQuery	

Плагіни
-----------------------------------
	Google maps api - плагін для використання карт google
	slick-carousel - стилізація каруселі
	slick-nav - стилізація мобільного меню
	init - ініціалізація плагінів

Шрифти і іконки
-----------------------------------
	Font-Awesome  - шрифт іконок
    Et-line icons - шрифт іконок
	Dosis: 300,400,500
	Open Sans: 300,400,500

## Стандартні компоненти і класи



### Компоненты
-----------------------------------


#### Стилізація заголовків:
    .title 
    .title.title-white 
    .title.section-title 
    .title.section-title-light 
    .text-center

#### Стандартні кнопки:
    .btn
    .btn-default
    .btn-black
    .btn-xs
    
#### Стандартні ромбовидні іконки
	.rhomb-icon 
    .rhomb-icon i
    .rhomb-icon.black-icon
    .rhomb-icon.white-icon
    .rhomb-icon.transparent-icon
    
#### Відступи між стандартними блоками:
    .default-section
    .small-section 

#### Стлізація стандартної текстової інформації:
    .text-default
     blockquote, 
    .blockquote 
     blockquote span, 
	.blockquote span
    
### Классы
-----------------------------------

#### Вирівнювання елементів і тексту:
    .text-center
    .text-right
    .text-justify
    .pull-right
    .pull-left
    
#### Колір для Фону:
    .bg-black
    .bg-grey
    
### Колони 
-----------------------------------

#### Стандартні колони до 1200px
	.row - обгортковий блок для колон
    .col - стандартна колона
    .col-1  - 8.33333333%
    .col-2  - 16.66666667%
    .col-3  - 25%
    .col-4  - 33.33333333%
    .col-5  - 41.66666667%
    .col-6  - 50%
    .col-7  - 58.33333333%
    .col-8  - 66.66666667%
    .col-9  - 75%
    .col-10 - 83.33333333%
    .col-11 - 91.66666667%
    .col-12 - 100%
        
#### Середні колони до 991px
	.col-md-1  - 8.33333333%
    .col-md-2  - 16.66666667%
    .col-md-3  - 25%
    .col-md-4  - 33.33333333%
    .col-md-5  - 41.66666667%
    .col-md-6  - 50%
    .col-md-7  - 58.33333333%
    .col-md-8  - 66.66666667%
    .col-md-9  - 75%
    .col-md-10 - 83.33333333%
    .col-md-11 - 91.66666667%
    .col-md-12 - 100%

#### Малі колони до 768px 
	.col-sm-1  - 8.33333333%
    .col-sm-2  - 16.66666667%
    .col-sm-3  - 25%
    .col-sm-4  - 33.33333333%
    .col-sm-5  - 41.66666667%
    .col-sm-6  - 50%
    .col-sm-7  - 58.33333333%
    .col-sm-8  - 66.66666667%
    .col-sm-9  - 75%
    .col-sm-10 - 83.33333333%
    .col-sm-11 - 91.66666667%
    .col-sm-12 - 100%
    
#### Дуже малі колонки до 576px
	.col-xs-1  - 8.33333333%
    .col-xs-2  - 16.66666667%
    .col-xs-3  - 25%
    .col-xs-4  - 33.33333333%
    .col-xs-5  - 41.66666667%
    .col-xs-6  - 50%
    .col-xs-7  - 58.33333333%
    .col-xs-8  - 66.66666667%
    .col-xs-9  - 75%
    .col-xs-10 - 83.33333333%
    .col-xs-11 - 91.66666667%
    .col-xs-12 - 100%
    
### Mедіа
-----------------------------------

#### Осеовні контрольні точки media-запитів
	 @media (max-width: 1200px) - пристрої з роздільною здатністю до 1200px
	 @media (max-width: 991px)  - пристрої з роздільною здатністю до 991px
	 @media (max-width: 768px)  - пристрої з роздільною здатністю до 768px
	 @media (max-width: 576px)  - пристрої з роздільною здатністю до 576px
	 @media (max-width: 320px)  - пристрої з роздільною здатністю до 320px

#### Виснористані в проекті Id 
	 #Tabs
	 #Tabs portfolio

#### Основні назви блоків 
	.header - шапка сайту з посиланням на основні блоки 
    .main   - блок що містить основну частину сайту 
    	.inner - один з основних блоків, який містить заголовок сайту
   		.about - один з основних блоків, який містить опис компанії
        .services - один з основних блоків, який містить опис сервісів що пропонує компанія
        .exclusive-services - блок що містить посилання на соновні сервіси
        .portfolio - один з основних блоків, що демонструє роботи компанії
        .like-creative-works - блок з посиланням який, що пропонує створити новий проект 
        .why-choose-us - блок, яий містить характеристику компанії
        .reviews - блок з каруселлю, що містить відгуки
        .latest-news - блок з новинами
        .subscribe - блок для підписки 
        .contacts - один з основних блоків, який містить контакти компанії
        .map-container - блок з картою 
  	.footer - блок, що містить нижній колонтитул 
        
    
#### Структура папок

Назва Папки     | Вміст Папки
----------------|----------------------
www             | Містить готовий проект
css             | Містить файли стилів
fonts   	    | Містить файли Шрифтів
js		        | Містить файли Javascript

#### Структура файлів

Назва файлів         | вміст файлів
---------------------|----------------------
index.html           | Файл що містить html структуру проекту
guide.html           | Файл для демострації стилів
style.css      		 | Файл з основними таблицями стилів
slick-nav.css  	     | Файл стилазіції меню мобільної навігації по сайті
grid.css        	 | Файл вирівнювання сайту методом 12 колонок.
font-awesome.min.css | Файл стилізації іконок
et-line.css          | Файл стилізації іконок блоку сервіс
etline               | Файд шрифту іконок блоку сервіс
FontAwesome    		 | Файл шрифту іконок 
fontawesome-webfont  | Файл шрифту іконок 
     