# Изучение вкладки "Network" (Сеть) в DevTools на примере сайта СберМегаМаркета https://megamarket.ru/
1. Какой запрос(-ы) отправляется на сервер для получения списка типов товаров в шторке "Каталог"?
 * POST https://megamarket.ru/api/mobile/v1/catalogService/catalog/menu
2. Какой запрос(-ы) отправляется на сервер при использовании поиска товаров в каталоге?  
 * POST /api/mobile/v3/catalogService/catalog/searchSuggest
 * POST /api/mobile/v1/catalogService/filters/search
 * POST /api/mobile/v1/catalogService/catalog/search
3. Какой запрос(-ы) отправляется на сервер при поиске региона или города в модалке выбора вашего региона?

 *   POST/api/mobile/v1/addressSuggestService/address/suggest  
