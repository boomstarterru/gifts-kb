### Подключение к CMS:

* [Amiro](https://github.com/boomstarterru/gifts-kb/wiki/amiro)
* [Bitrix](https://github.com/boomstarterru/gifts-kb/wiki/Bitrix)
* [Insales](https://github.com/boomstarterru/gifts-kb/wiki/insales) (в разработке)
* [Joomla](https://github.com/boomstarterru/gifts-kb/wiki/joomla)
* [Opencart](https://github.com/boomstarterru/gifts-kb/wiki/opencart)
* [WordPress](https://github.com/boomstarterru/gifts-kb/wiki/wordwress)

[Универсальный метод](https://github.com/boomstarterru/gifts-kb/wiki/universal) (beta)
 
### Стиль кнопки

Стиль кнопки:
* дизайн, 
* цвет, 
* размер, 
* шрифт,
* ...

задаются через аттрибут `style=""`.

Проще говоря, 

для стиля:

![custom-style](https://raw2.github.com/boomstarterru/gifts-kb/master/images/custom-style.jpg)

разметка будет выглядеть так:

    <script type="text/javascript" src="http://boomstarter.ru/assets/gifts/api/v1.js" async></script>
    <div class="boomstarter-gift" 
         style="margin: 1em 0 0 1em; float: left;">
        <a href="#" 
           product-id="<product_id>" 
           boomstarter-shop-uuid="<shop_uuid>" 
           boomstarter-shop-key="<shop_key>" 
           boomstarter-button-style="metro" 
           style="color: white; padding: 0.5em 1em; font: inherit; font-weight: bold; ">
            Хочу в подарок
        </a>
    </div>

