# My projects

In this repository, you will find programs I made, there is 99% of chance that none of them are finish. They are all made to develop my skills in programming. Of course, I will successively add them and tip a description in this Readme file.

I am 100% open for suggestions, constructive critism, even if you want to debate with me, I am here and I will try to respond as fast as I can.

I already thank everyone who participate, or not. And for the students finding something interesting in my projects, it is a honor for me.

# Stock Manager (Gestion de Stock)

This is my first project I totally made myself (not exactly but I will explain later). It doesn't really have to work perfectly but with this project I tried to implement some "mechanics" and work the MVC pattern, try to understand it. Of course it is not exactly how it should be, but whatever, my main purpose in this project was to develop a Menu system in Console Application by loading menu's titles from a textfile and loading classes, models and controllers directly from the textfile too. This was the "difficult" part of this program.

The idea was to avoid all the 'Switch() case' when you want to create a menu, and just load a line in the textfile that will be the name of the class you want to load. In the projects folder Datas -> Menus, there is a MainMenu.txt file. When I load this file, I create an object MenuModel that has 3 attributes : ID, Name, Action. When I load the MainMenu file using 'ConvertToMenu' method of the class 'TextProcessor' The ID and the name are simple, it is just a 'i' variable I increment at every loop in the foreach, the name is just the line in my textfile, but the Action is different, it is the name + Controller at the end.
This way I just have to create the controller with the right name I need and in the textfile, if I need to change something, I'll just change it in the textfile and it's done.

Earlier I said I didn't really make it all myself, it is mainly because the classes in the DataAccess folder are TimCorrey's, I just took them and modify to fit to my project, but the big lines are from him (Big Up to Tim Correy, best C# tutorials maker on Youtube) and if you download the project and generate it, you'll get errors and mainly because it misses a library called PAP.

This library was made by my teacher and I am not sure if I can post it on GitHub so I prefer not to.
