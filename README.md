# Dealhawk
Dealhawk is a personal project of mine which came up when i was looking to buy a tv and wanted to check prices without manually doing it. Project consists of three parts and you can find more info about them on their repositories:

[Dealhawk-backend](https://github.com/joonvena/dealhawk-backend)  
This service is used to read, delete, add & update products. It's mainly used by the  [Dealhawk Google Chrome Extensions](https://github.com/joonvena/dealhawk-chrome-extension)

[Dealhawk-price-watcher](https://github.com/joonvena/dealhawk-price-watcher)  
This service is used to check product prices daily. It reads all the products from DynamoDB and check the prices. If price is changed it updates the new price and then notifies the user with email that contains lists of products with changed price.

[Dealhawk-chrome-extension](https://github.com/joonvena/dealhawk-chrome-extension) (TODO)  
This plugin is used to manage products on client side. It's active only when you are at verkkokauppa.com website. From this plugin you can see list of products you are following, remove products from the list and also add new products to follow from the product page.
