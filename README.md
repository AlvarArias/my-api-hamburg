# my-api-hamburg
## _This is my Api demo for hamburgers restaurants_


How it work:

make a GET call to: 
```sh
https://api-hamburg.herokuapp.com/burgers
```

Then you will get a JSON response. 


You can also search by "id":

make a GET call to 
```sh
https://api-hamburg.herokuapp.com/burgers?id=1
```
It show you the restaurant information for id=1.

You can search for a specific parameter:
```sh
https://api-hamburg.herokuapp.com/burgers?q="Lanskrona"
```
It show you all the restaurants information who include q="Lanskrona".

Object parameters:

- id: identificator
- name = name of the Hamburger
- restaurant = restaurant's name
- web : restaurant web page
- description : hamburger description
- ingredients : hamburger ingredients
- adress : restaurant adress.


