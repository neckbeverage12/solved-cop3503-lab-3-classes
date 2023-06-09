Download Link: https://assignmentchef.com/product/solved-cop3503-lab-3-classes
<br>
<span class="kksr-muted">Rate this product</span>




The purpose of this assignment is give you some experience writing classes in C++, the various special functions they make use of (such as copy constructors, assignment operators, and destructors), as well as and introduction dynamically allocating memory within those classes.

Description

This program will represent a stereotypical college pantry, which consists of shelves that contain various “food” items. To that end, there are three classes you will be writing:

 Food Shelf Cabinet

For this assignment, main.cpp will be provided for you, so you don’t have to worry about the structure of the program. Instead, you can focus solely on the structure of the classes and their interactions.

Food

The Food class is the basic container of this assignment. You will need to store the following data:

<ul>

 <li>  The type of food (such as cereal, fruit, vegetable, frozen etc)</li>

 <li>  The name of the food product (such as Fruity Pebbles, Ramen, Tomato, etc)</li>

 <li>  The expiration year</li>

 <li>  The price</li>

 <li>  How many calories does the food have?In addition to a constructor which takes in the necessary information, you will also need the following functions defined. If you are using dynamic memory in your class, you will also want to define a destructor, in which you will clean up (delete) any memory which was allocated by the class.</li>

</ul>

Shelf

The Shelf class is a bit more sophisticated. Its purpose is to store an array of Food objects. Each Shelf that you create could have a different number of Food objects, so you will have to use dynamic memory allocation in this case. Your Shelf should contain variables for the following:

<ul>

 <li>  The name of the Shelf</li>

 <li>  A pointer to the array of Food objects, and because pointers don’t have any addition info ontheir own…</li>

 <li>  A maximum capacity of the array</li>

 <li>  A count of how many Food objects you currently haveIn addition, you should create the following functions (plus the special functions—a copy constructor, assignment operator, and destructor):</li>

</ul>

Cabinet

The Cabinet class in some ways is very similar to the Shelf. It will store a dynamic array, this time of Shelf objects. It will also need a name and ways to keep track of how many Shelves it can store, versus how many it is currently storing.

Based on the layout of main.cpp (and the test output), you will also need a way to print everything in its inventory (which consists of Shelves which consist of Food), but also a way to get the average price of each food item.

Be sure to define the big three as well.

Tips

A few tips about this assignment:

 Remember the “Big Three” or the “Rule of Three”o If you define one of the three special functions (copy constructor, assignment operator,

or destructor), you should define the other two You can print out a tab character (the escape sequence ‘t’ ) to help line up the output.

<ul>

 <li>  Don’t try to tackle everything all at once. Work on one class at a time. Can’t have a Shelf without Food…</li>

 <li>  You can customize the way numbers are displayed in C++ (particularly floating-point numbers). The header file &lt;iomanip&gt; contains this functionality. Look into std::fixed and std::setprecision()</li>

 <li>  Refer back to the recommended chapters in your textbook as well as lecture videos for an explanation of the details of dynamic memory allocation</li>

</ul>