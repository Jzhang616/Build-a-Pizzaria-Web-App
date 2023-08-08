# Build-a-Pizzaria-Web-App

You will complete the following exercises in building the Pizzeria Django project. Organize your project the way the Learning_Log project is organized.
A. Exercise 18-4 - Pizzeria:
1. Start a new project called pizzeria with an app called pizzas.
2. Define a model Pizza with a field called name, which will hold name values, such as Hawaiian
and Meat Lovers.
3. Define a model called Topping with fields called pizza and name. The pizza field should be a
foreign key to Pizza, and name should be able to hold values such as pineapple, Canadian
bacon, and sausage.
4. Register both models with the admin site (Test your work by using the admin site to enter
some pizza names and toppings and by using the Django shell to explore the data you
entered.)
5. Set the username and password for the superuser account to: admin, admin
B. 18-6 - Pizzeria Home Page:
1. Add a home page to the Pizzeria project you started in Exercise 18-4.
C. 18-8 - Pizzeria Pages:
1. Add a page to the Pizzeria project from Exercise 18-6 that shows the names of available
pizzas.
2. Then link each pizza name to a page displaying the pizza’s toppings. 3. Make sure you use template inheritance to build your pages efficiently.
When your project is complete, compress the project directory into a zip archive, and include the entire archive in your submission.
