Download Link: https://assignmentchef.com/product/solved-cse102-homework-2
<br>
Write a complete program describing all the tasks below. In the main () function, the 3 integer values requested from the user will represent the lengths of the sides of a triangle, and the 4 functions specified below will be called from the main ( ) function, ensuring that all tasks are performed completely.

    Determining whether the triangle can be drawn according to the triangle inequality theorem.

<ul>

 <li><strong><u>If the triangle cannot be drawn;</u> </strong>

  <ul>

   <li>“<em>According to the triangle inequality theorem, this triangle cannot be drawn</em>. ” message should be printed on the screen and the process should end.</li>

  </ul></li>

</ul>

<ul>

 <li><strong><u>If the triangle can be drawn</u></strong>;

  <ul>

   <li><em>“According to the triangle inequality theorem, this triangle can be drawn</em>.” message should be printed on the screen</li>

   <li>the type of triangle should be determined</li>

   <li>the perimeter of the triangle should be calculated <strong>–</strong> the area of the triangle should be calculated</li>

  </ul></li>

</ul>

<ol>

 <li>Write a function that determines whether the triangle can be drawn according to the triangle inequality theorem and returns 1 if it can be plotted and 0 if it cannot be drawn.</li>

</ol>

<strong><em>“The Triangle Inequality Theorem states that the sum of any 2 sides of a triangle must be greater than the measure of the third side.” </em></strong>

Function prototype is int draw_triangle(int side1,int side2, int side3)

<ol start="2">

 <li>Write a function that determines the type of the triangle (equilateral, isosceles or scalene) and prints on the screen, without returning value.</li>

</ol>

Function prototype is void type_triangle(int side1,int side2, int side3)

<ol start="3">

 <li>Write a function that calculates the perimeter of the triangle and returns this value.</li>

</ol>

Function prototype is int perimeter_triangle(int side1,int side2, int side3)

<ol start="4">

 <li>Write a function that calculates the area of the triangle according to the formula below and returns this value.</li>

</ol>

Function prototype is double area_triangle(int side1,int side2, int side3,int perimeter)

<em>Tip: When calculating the area of the triangle, take root by using the sqrt () function of the math library. You can find detailed information about using this function here. </em>

<strong>Part 2.</strong>

In the main ( ) function, ask the user to enter a maximum of 6 digits and consider this number written 100 times next to each other. Write a complete program that tries to find the number in an index to be determined by the user in this large series of numbers.

<strong>Please note that the integer array and loops will not be used in the question. </strong>




You are expected to use 2 functions except the main function while performing the desired operations in the question.

<ol>

 <li>A function that finds the length of the number entered by the user on the command screen and returns the integer value expressing the length should be defined.</li>

</ol>

Function prototype is int number_length(int number)

Hint : You can use the logarithm to find out how many digits the number is. You can access log functions and their uses in the math library for logarithm operation from <a href="https://www.codecogs.com/library/computing/c/math.h/log.php">here</a><a href="https://www.codecogs.com/library/computing/c/math.h/log.php">.</a>

<ol start="2">

 <li>According to the index value entered by the user on the command screen, define a function that finds the number in the specified index and returns that integer value.</li>

</ol>

Function prototype is int find_digit(int number, int index)




Hint : In order to obtain the number in a certain index within the number, you should use the digit       values of the number. You may need the powers of 10 in your mathematical calculation. In this case, you can find detailed information about using pow () function in the math library <a href="https://www.programiz.com/c-programming/library-function/math.h/pow">here.</a>

<strong>Part 3.</strong>

Write a currency converter program in the Main () function. You do not have to define functions for this part.

Exchange rate information will be accepted as follows.

<strong>1 Euro = 6.69 Turkish Lira </strong>

<strong>1 Dollar = 6.14 Turkish Lira </strong>

As you can see the screen output below, the user must first be greeted with the message  “***** Welcome to ABC Exchange Office *****”.

Then the user should be asked to write the amount of money he/she has on the command screen. The menu in the screenshot below should be created in order to select the currency that the user has.

By using the <strong>‘switch case’ </strong>structure according to the user’s choice;

For example, if the user chose 1, ‘You have xxx Turkish Liras’ message should be printed on the screen.

Then, the user should be asked to choose the rate he / she wants to convert according to the menu above.

Currency exchange calculations should be completed depending on the user’s choice again.

Please note that when the user makes a wrong choice (for example, if he makes a choice of 5), ‘Your selection is invalid.’ message should be printed.













<strong> </strong>

<strong> </strong>

<strong> </strong>