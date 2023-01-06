# Django Ecommerce 

This is a very simple e-commerce website built with Django.


 ## Quik Demo 
![Demo](https://user-images.githubusercontent.com/68337132/210933685-ec9714af-d35e-4d56-a870-8850591857a6.gif)


## Project summary

The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. They can then enter their address and choose Stripe to handle the payment processing.

## Running this project
To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```bach
pip install virtualenv
```
Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project
```bash
virtualenv env
```
That will create a new folder env in your project directory. Next activate it 

Then install the project dependencies with
```bash
pip install -r requirements.txt
```
Now you can run the project with this command
```bash
python manage.py runserver
```
thanks to divanov11
