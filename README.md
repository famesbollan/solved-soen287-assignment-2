Download Link: https://assignmentchef.com/product/solved-soen287-assignment-2
<br>
<strong>Purpose: </strong>The purpose of this assignment is to help you learn the selection flow control statements, if, if / else, while and do while loops – can use for loops but not required.

<strong>CEAB/CIPS Attributes: </strong>This assignments is primarily evaluating your use of JavaScript Basics. (Use of engineering tools).




<strong><u>General Guidelines When Writing Programs</u>: </strong>

<ul>

 <li>Include the following comments at the top of your source codes</li>

</ul>




// ——————————————————————————

// Assignment (include number)

// Written by: (include your name (s) and student id(s))

// For SOEN 287 Section (your section) – Winter 2017

// —————————————————————————–

<ul>

 <li>In a comment, give a general explanation of what your program does.</li>

 <li>Include comments in your program describing the main steps in your program.</li>

 <li>Display clear prompts for users when you are expecting the user to enter data from the keyboard.</li>

 <li>All output should be displayed with clear messages and in an easy to read format.</li>

</ul>




<strong><u>Question #1:</u> – Formatting a list and table/External style sheet </strong>(5 pts)

Script the webpage in figure 2 using an html file for the format and content and an external CSS file for the presentation. You choose the topic; here are a few ideas: cars, animals, sports, foods ….

Here are the specifications:

<ol>

 <li>The <strong>background</strong> of your page has a repeated image of your choice.</li>

 <li>The <strong>header</strong> must be formatted using the box model. The image to the right illustrates the CSS box model.</li>

</ol>

To accomplish this use the &lt;div&gt; tag. You can use any color combinations for the border and the background. The color of your header must be the same color as the border of the box model. Set the margin of the box model to be the same as the

margin of the table that follows (so they line up nicely). Set <em>Figure 1- Box model</em> the border to be at least 10px and solid. Set the internal padding to be at least 10px. Set the width to a value of your choice other than 100%.

<ol start="3">

 <li>The table must have 3 rows and 2 columns.

  <ol>

   <li>Set the table margin the same as the header margin.</li>

   <li>Set the border of the table to be at least 15px, dotted and a different color from any other colors in the table.</li>

   <li>The 1<sup>st</sup> row is for headings. The background color must be different from any of the other cells in the table, and the text must be any color other than black. Add a padding of at least 10px for the heading cells.</li>

   <li>The cells in rows 2 and 3 must all have a different color background and a different colored border.</li>

   <li>The cells in the column 1 of row 2 and 3 each have an ordered list whose list style is upper roman. Notice that the numbering of the list items in the cell col 1/row 3 starts at 2 (and not 1).</li>

   <li>The cell in row 2/col 2 has an ordered list whose list type is uppercase letters. The 1<sup>st</sup> nested unordered list has bullets that are a 25px x 25px image of your choice. The second nested unordered list’s bullets are the default circle. The color of the text in the 2<sup>nd</sup> unordered list is the same as the border of that cell.</li>

   <li>The cell in row 3/col 2 has an ordered list whose list type is Armenian numbering. The 1st nested unordered list’s bullets are square. The 2<sup>nd</sup> nested unordered list has bullets that are a 25px x 25px image of your choice, different from the image used in cell Row 2/col 2. The color of the text in the 1st unordered list is the same as the border of that cell.</li>

  </ol></li>

 <li>All style are to be entered in an external CSS.</li>

 <li>Be sure to include your name in the page as well as the sources of your images with links to the pages at a location of your choice.</li>

 <li>Validate your code using the HTML5 validator.</li>

</ol>







<em>Figure 2 – Template of page to script for question #1 </em>













<strong><u>Question #2:</u></strong>

Write a script that prompts the user to enter three numbers and the program displays the following results:

 The number of negative numbers  The number of positive numbers  The number of zeroes.

For the table format, you can use the property values of width = ‘50%’ and Border = ‘1’.

Here is a sample output to illustrate the expected behavior of your program:




<strong><u>The result is:</u> </strong>




<strong><u>Question #3:</u></strong>

Write a script in the head section that calculate the square and cubes of the numbers from 0 to 5. The program displays the resulting values in HTML5 table format including the width = 50% and border = 1, as below:

<strong><u>Note:</u></strong> You don’t need to develop any function to calculate the square and cube of these numbers.

<strong><u>Question #4:</u></strong>

Write a function <strong><em>NbnamePattern</em></strong> in JavaScript language declared in the document head section. This function takes a parameter an array of strings called <strong><em>names</em></strong>. This function returns the number of names in the given array that end in either “ie” or “y” patterns.

The test driver of the program must be defined as a script in the body section, including the declaration of the array and the invocation of the function. Use this following data of the array (names):

Names = “freddie”, “bob”, “mieke”, “yahoo2”, “georgey”

The array must be created as an instance of the class <strong>Array</strong> using the “<strong>new</strong>” operator.

The program displays the result as follows:







<strong><em><u>Hint:</u>  </em></strong>

<ul>

 <li>Use the loop : for</li>

 <li>Use the existing method <strong><em>search()</em></strong> to provide you the position of these patterns in the array like (names[i].search(/ie$/).</li>

</ul>


