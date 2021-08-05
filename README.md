# Commerceya
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-js.svg)](https://forthebadge.com)


## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Usage](#usage)
* [Frontend](#frontend)
* [Backend](#backend)
    * [Django](#django)
* [Screenshots](#screenshots)
* [Authors](#authors)
* [Contributing](#contributing)


## About the Project
The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. Users can also select the category to add products and filter according to thier prices. They can then enter their address and choose Stripe to handle the payment processing.


### Built With
*   Django

[Back to Table of Contents](#table-of-contents)

## Getting Started
### Prerequisites
* Python
* Django


### Installation



* Backend

    ```Python
    pip install -r requirements.txt
    python manage.py makemigrations
    python manage.py migrate
    ```

### Usage

* To Create Super User

    ``` python
    python3 manage.py createsuperuser
    ```
    
    
* To Run Server

    ``` python
    python3 manage.py runserver
    ```
    
[Back to Table of Contents](#table-of-contents)

## Frontend

* #### Django template language
    Django’s template language is designed to strike a balance between power and ease. It’s designed to feel comfortable to those used to working with HTML. If you have any exposure to other text-based template languages, such as Smarty or Jinja2, you should feel right at home with Django’s templates.
    

## Backend

* #### Django 
    Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It's free and open source.
    
    * ###### Why Django ?
        *  Ridiculously fast
        *  Reassuringly secure
        *  Exceedingly scalable
        *  Incredibly versatile
        *  Easy to Integrate with Python Libraries/Functions

## Features

<b>Products Features</b>

| Feature  |  Coded?       | Description  |
|----------|:-------------:|:-------------|
| Add a Product | &#10004; | Ability of Add a Product on the System |
| List Products | &#10004; | Ability of List Products |
| Edit a Product | &#10004; | Ability of Edit a Product |
| Delete a Product | &#10004; | Ability of Delete a Product |
| Stock History | &#10004; | Ability to see the Stock History |

<b>Purchase Features</b>

| Feature  |  Coded?       | Description  |
|----------|:-------------:|:-------------|
| Create a Cart | &#10004; | Ability of Create a new Cart |
| See Cart | &#10004; | Ability to see the Cart and it items |
| Remove a Cart | &#10004; | Ability of Remove a Cart |
| Add Item | &#10004; | Ability of add a new Item on the Cart |
| Remove a Item | &#10004; | Ability of Remove a Item from the Cart |
| Payment Integration | &#10004; | Ability to handle payment processing |
| Checkout | &#10004; | Ability to Checkout |


<b>Admin Features</b>

| Feature  |  Coded?       | Description  |
|----------|:-------------:|:-------------|
| Manage Product | &#10004; | Ability to add, edit or remove product |
| Manage Category | &#10004; | Ability to add, remove category |
| Manage Customer | &#10004; | Ability to add, edit, remove or view details of customer |
| Manage Order | &#10004; | Ability to handle order status (packed, onTheWay, delivered, cancel) |



[Back to Table of Contents](#table-of-contents)
## Screenshots

##### Home Page

![home_page](https://user-images.githubusercontent.com/39465843/128064172-3b86cf2c-882e-421f-b532-53cf1d3f48aa.png)


##### Customer registration

![costomer_registration](https://user-images.githubusercontent.com/39465843/128064208-1aaf75c3-3163-4113-9f27-a9c9f53548d4.png)


##### Login page

![login form](https://user-images.githubusercontent.com/39465843/128064268-545412af-f99d-4808-937e-b3632244c0aa.png)


##### Product page

![product_page](https://user-images.githubusercontent.com/39465843/128064293-06c2739f-5b9d-4cb0-813a-53677dc29338.png)


##### Shopping cart

![shopping cart](https://user-images.githubusercontent.com/39465843/128064318-19cc3265-0be6-436e-92d7-b446d2a5dbe9.png)


##### Order page

![order page](https://user-images.githubusercontent.com/39465843/128064326-7fee4034-8398-480d-bdf0-e1bd31bc4d26.png)


##### Order Status

![order status](https://user-images.githubusercontent.com/39465843/128064344-17b2d74c-4754-4010-851e-3883e1b63401.png)




