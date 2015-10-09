Project Description: This is a Data drive website that can hold restaurants and their menus detail.
User can : 
1. Add a restaurant
2. Modify restaurant name
3. Delete a restaurant
4. Add menu items in a particual restaurant
5. Edit menu items
6. Delete menu items
7. Add delete and modify option only available for registerd user.
8. User can register using google account.
9. There are three API endpoints provided for other website or application to use.
   1. Below end point will give you a list of meu items for a specific restaurant
       localhost:5000 /restaurant/<int:restaurant_id>/menu/JSON
   2. Below end point will give you detail about a paricular menu item of a specific restaurant
       localhost:5000/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON
   3. Below end point will give you list of all availabe restaurants
       localhost:5000/restaurant/JSON


How to run this project:
1. Download two files provided in this respository and have them in same folder in your local machine.
     a. database_setup.py
     b. finalproject.py
2. First Run the database_setup.py using below command
    python database_setup.py
3. Run file finalproject.py using below command.
    python finalproject.py
4. you can access the website using below URL
    localhost:5000
    or
    localhost:5000/restaurants