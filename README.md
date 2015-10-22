## Title: Restaurant Menu Application

## Introduction:
This is a web based data driven application that will help create list of restaurants and their corresponding menu items.

## Requirements:
Flask == 0.9
SQLAlchemy == 0.8.4

## Installation:
1. Use GIT bash to run the below command to get a clone of the repository
"git clone https://github.com/krishna-pandey-git/Restaurant2"
2. Above command will give you a folder named "Restaurant2" in your current working directory

## Set Up and Running:
1. Move to folder Restaurant2 created above.
2. First Run the database_setup.py using below command
    python database_setup.py
3. Run file finalproject.py using below command.
    python finalproject.py
4. you can access the website using below URL
    localhost:5000
    or
    localhost:5000/restaurant

## Usage:
1. Authorized users can create modify and delete restaurant and menu items
2. Only the creater  of restaurant will be able to modify or delete it
3. Public user can only view the content
4. User can register using google account.
5. There are three API endpoints provided for other website or application to use.
   1. Below end point will give you a list of meu items for a specific restaurant
       localhost:5000 /restaurant/<int:restaurant_id>/menu/JSON
   2. Below end point will give you detail about a paricular menu item of a specific restaurant
       localhost:5000/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON
   3. Below end point will give you list of all availabe restaurants
       localhost:5000/restaurant/JSON