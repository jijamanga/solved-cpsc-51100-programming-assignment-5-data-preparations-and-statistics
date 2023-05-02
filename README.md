Download Link: https://assignmentchef.com/product/solved-cpsc-51100-programming-assignment-5-data-preparations-and-statistics
<br>
<strong>Introduction</strong>

The file cps.csv (attached) contains school profile information for Chicago Public Schools. Your program will derive some data from it and then generate some statistical information.

<strong>Requirements</strong>

You are to create a program in Python that performs the following:

<ol>

 <li>Loads the cps.csv file (assume it’s in the current directory) and create a DataFrame object from it.</li>

</ol>

<ol start="2">

 <li>Based on the data contained in the cps.csv file, generates a dataframe with the following information:

  <ol>

   <li>School_ID</li>

   <li>Short_Name</li>

   <li>Is_High_School</li>

   <li>Zip</li>

   <li>Student_Count_Total</li>

   <li>College_Enrollment_Rate_School</li>

   <li>Lowest Grade Offered (derived from Grades_Offered_All column)</li>

   <li>Highest Grade Offered (derived from Grades_Offered_All column)</li>

   <li>Starting Hour (derived from School_Hours column)</li>

  </ol></li>

</ol>




The values for a-g are based on existing columns in the data. For h-j, you will need to generate new columns which derives information from existing ones.

Replace the missing numeric values with the mean for that column.

Display the first 10 rows of this dataframe.

<ol start="3">

 <li>Displays the following information:

  <ol>

   <li>Mean and standard deviation of College Enrollment Rate for High Schools</li>

   <li>Mean and standard deviation of Student_Count_Total for non-High Schools</li>

   <li>Distribution of starting hours for all schools</li>

   <li>Number of schools outside of the Loop Neighborhood (i.e., outside of zip codes 60601, 60602, 60603, 60604, 60605, 60606, 60607, and 60616)</li>

  </ol></li>

</ol>

<strong>Additional Requirements</strong>

<ol>

 <li>The name of your source code file should be py. All your code should be within a single file.</li>

 <li>You need to use the pandas DataFrame object for storing data.</li>

 <li>Your code should follow good coding practices, including good use of whitespace and use of both inline and block comments.</li>

 <li>You need to use meaningful identifier names that conform to standard naming conventions.</li>

 <li>At the top of each file, you need to put in a block comment with the following information: your name, date, course name, semester, and assignment name.</li>

</ol>

<strong>What to Turn In</strong>

You will turn in the single DataStats.py file using BlackBoard.

Sample Program Output

<strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/08/429.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/08/429.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript>CORRECTION:</strong>

Distribution of Starting Hours should be:

8am: 415

7am: 193

9am: 40


