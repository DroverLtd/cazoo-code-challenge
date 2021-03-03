# Cazoo - Search. Drive. Smile.

# Software Engineer Challenge
## About Us

Hello, we’re [Cazoo](http://cazoo.co.uk/) and we’re transforming the way people buy used cars. We understand how much people love their cars but that they often don’t love the experience of buying one.

We buy only the best used cars and we lovingly recondition every single one to the highest standards. You can have your car delivered or collect it in as little as 72 hours and we give you up to 7 days to get to know your Cazoo car. If you change your mind, we'll collect it and give you a full refund.

We provide better selection, value, quality and convenience to give you total peace of mind when buying a used car. We think you should be able to simply and seamlessly purchase a used car entirely online much like buying any other product today.

## Cars
As you know Cazoo is an online marketplace to buy or to subscribe cars, and as you expect we try to have as much cars as we can on our platform. For this challenge we want you to implement a simple frontend to create, update and list cars.

A car's maker is the brand of the vehicle, while the model refers to the name of a car product and sometimes a range of products. For example, Toyota is a car maker and Yaris is a car model. So for each car we will create on the challenge we will need to have the following properties:
* Maker
* Model
* Year
* Color
* Monthly, subscription price
* Available from, when the car is available for booking

For this challenge only consider the following Makers and Models:
* BMW
  * Series3
  * X1
* Toyota
  * Yaris
  * RAV4
* Renault
  * Clio
  * Megane

## What do we expect from you?
Code is your 1st class citizen.

* Good documentation.
* Good design decisions.
* Testable code.

If you are comfortable with Backend and Frontend development, please consider the "Full-stack challenge". If you are purely experienced with Frontend development, please consider the "Frontend only challenge".

Please create a repository on your private github account and once you finish the challenge we will share with you the github usernames you should invite for the review.

## Full-stack challenge

The backend must have the following 4 endpoints implemented:
1. Create a REST endpoint to create a `car` in one POST request
1. Create an endpoint to update a `car`.
1. Create an endpoint to fetch all `cars`. The results *should be sorted* by price from lowest to highest by default and all cars with an available from bigger than three months in the future should be filtered.
1. Add on the GET cars endpoint the possibility to filter by maker and/or color.

The frontend must have the following implemented:
1. Create a simple Frontend interface where the cars can be listed.
1. Should be possible to add a new car.
1. Should be possible to update a car.

### Bonus Points

1. Possibility to do pagination, showing 10 cars at a time
1. On the GET cars API add the possibility to do a sort by price, year, maker or availability
1. Add documentation to all endpoints

## Frontend only challenge

The frontend must have the following implemented:
1. Create a Frontend interface where the cars can be listed.
1. Should be possible to add a new car.
1. Should be possible to update a car.
2. Should be possible to view more details about the car.
3. The page should support pagination, showing 10 cars at a time.


------
