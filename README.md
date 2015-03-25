shoppingcart
============

A java-based shoppingcart.

This project contains 4 folders:

- src: the source code folder
- lib: contains the exported jar library file
- example: an example of using the shopping cart library
- doc: contains the javadoc documentations

In order to use the library, just download the shoppingcart-{version number}.jar from lib library and include it in your project build path.

For any product/item that you want to add into the shopping cart, just create a class which implements the Saleable interface and override two methods:

- getName(): should return the name of the item
- getPrice(): should return the price of the item

A Cart object represents a shopping cart. The Cart class provides various methods to manipulate items and quantities on the shopping cart like adding items, updating quantities, removing items,... For more details, check out the javadoc from here: https://rawgit.com/tonyvu2014/shoppingcart/master/doc/index.html

For most of web-based shopping cart, you will have to store and retain the cart object in session by yourself.