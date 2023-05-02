Download Link: https://assignmentchef.com/product/solved-cosc117-homework-3-strings-formatting-and-some-ifs
<br>
For each of the following create a new project with an appropriate name and then write a program that solves the given problem.

For each of the following create a new project with an appropriate name and then write a program that solves the given problem. Remember to use Shift+Ctrl+F to format the program, or Shift+Command+F on the Mac and include the the standard comments of at the top which include the author, date, and a program description.

For each program, you will be submitting the java code file through MyClasses, as you did before. I also want either a Microsoft Word docx file, LibreOffice Writer odt, or a text file (which you can create with NotePad++) which contains the following.

<ul>

 <li>An algorithm for the program.</li>

 <li>Output of at least three runs of each program on different data inputs.</li>

</ul>

This docx, odt, or text file is to be uploaded to MyClasses as well. You can copy and paste output from the Eclipse console area to the word or text program.

<ol>

 <li>In this exercise you will write a small version of a mail merge feature from a word processor. When you do a mail merge you create a generic letter and in the letter you put special fields that will read in (usually from a file) a person’s name, address, personal pronoun, and what other information is needed. In this program you will allow the user to type in a sentence where one field will be XXX and another will be YYY, then have the user type in the data for the XXX replacement and the YYY replacement. The program should replace the XXX and YYY in the string and print out the resulting string. Three runs of the program are below.</li>

</ol>

Input merge format sentence:

XXX said that YYY was going to the concert.

Input XXX replaceemnt: George

Input YYY replaceemnt: he

George said that he was going to the concert.

Input merge format sentence:

XXX said that YYY was going to the concert.

Input XXX replaceemnt: Sarah

Input YYY replaceemnt: she

Sarah said that she was going to the concert.

Input merge format sentence:

The house that XXX built was being rented by YYY, XXX’s friend.

Input XXX replaceemnt: Jack

Input YYY replaceemnt: Sarah

The house that Jack built was being rented by Sarah, Jack’s friend.

<ol start="2">

 <li>Write a program that will take in an entire sentence that has the word “and” in it. The program should then split the sentence at the word “and” and print out the two half sentences. A run is below and the user typed in</li>

</ol>

This class is very easy and I am going to ace the first exam.

Input a string with the word ’and’ in it:

This class is very easy and I am going to ace the first exam. This class is very easy and I am going to ace the first exam.

<ol start="3">

 <li>Write a program that will ask for two integers, a lower bound and an upper bound, then output a random number between the input lower and upper bounds inclusively.</li>

</ol>

Input Lower Bound: 5

Input Upper Bound: 20

12

<ol start="4">

 <li>Write a program that plays the (rather boring) game of High-Low. In an actual HighLow game you take a regular poker deck of 52 playing cards, shuffle them, then the players take consecutive cards off the top of the deck and compare them. The higher face value wins, with Ace being the top card. If the face values are equal then a Spade wins over a Diamond which wins over a Club which wins over a Heart. To create a program that imitates life and creates a deck of cards and shuffles them uses programming structures we have not seen yet but we will see later in the course. For now, we will simply use a random number generator to create a card. In this case it is possible that both players could have exactly the same card, for example the 7 of clubs, which would not happen in a real game. So there is also a possibility of a draw. It would be like each player had their own deck of cards. In your program you will generate a random card using the random number generator in the Math library for both Player 1 and Player 2, then you will have the program determine the winner of the game or a draw. Four sample runs are below.</li>

</ol>

Player 1: 8 CPlayer 1: 9 CPlayer 1: 10 HPlayer 1: K C

Player 2: J HPlayer 2: 8 DPlayer 2: 10 DPlayer 2: K C Player 2 WinsPlayer 1 WinsPlayer 2 WinsIt is a draw.

<h1>1             Challenge Exercise</h1>

Challenge Exercises are optional, they will be graded as extra credit.

Write a program that will take as input the information about a student and their grades and produce a progress report for them in a nicely presented way. The class the student is in has 7 quizzes (each worth 10 points), three exams (each worth 100 points) and a final exam (worth 200 points). This program is to take all of the grades except for the final, display the grades in tables, calculate the student’s current average, and a table of projections for what they need on the final exam to get a particular letter grade.

Since there are 370 points possible for the quizzes and exams, the current average in percentage form is the sum of the grades divided by 3.7. To calculate the final exam score needed you take the projected final average (90, 80, 70, and 60), multiply by 5.7 and subtract the sum of the scores. For example, for the student to get a A they must have a 90% at the end of the course. Suppose that the student earned 337 points, then the final exam score they need is

5<em>.</em>7 · 90 − 337 = 176

The tables are to have their columns right justified and the current average must be to 3 decimal places. Also note that in the examples below if we do the projection calculation for Martha the projected score for the D would come up as a negative number. If this is the case then the student could have skipped the final and received that letter grade. So a negative number here should be replaced by 0.

Two sample runs of the program are below. Your program should produce student reports that are identical to these.




<table width="104">

 <tbody>

  <tr>

   <td width="64">Quiz</td>

   <td width="40">Score</td>

  </tr>

  <tr>

   <td width="64">—-</td>

   <td width="40">—–</td>

  </tr>

  <tr>

   <td width="64">1</td>

   <td width="40">8</td>

  </tr>

  <tr>

   <td width="64">2</td>

   <td width="40">9</td>

  </tr>

  <tr>

   <td width="64">3</td>

   <td width="40">10</td>

  </tr>

  <tr>

   <td width="64">4</td>

   <td width="40">7</td>

  </tr>

  <tr>

   <td width="64">5</td>

   <td width="40">6</td>

  </tr>

  <tr>

   <td width="64">6</td>

   <td width="40">9</td>

  </tr>

  <tr>

   <td width="64">7</td>

   <td width="40">8</td>

  </tr>

  <tr>

   <td width="64">Exam</td>

   <td width="40">Score</td>

  </tr>

  <tr>

   <td width="64">—-</td>

   <td width="40">—–</td>

  </tr>

  <tr>

   <td width="64">1</td>

   <td width="40">89</td>

  </tr>

  <tr>

   <td width="64">2</td>

   <td width="40">100</td>

  </tr>

  <tr>

   <td width="64">3</td>

   <td width="40">76</td>

  </tr>

 </tbody>

</table>

Input Student’s Name: John Smith

Input Student’s ID: 123456789

Input Quiz #1 Score: 8

Input Quiz #2 Score: 9

Input Quiz #3 Score: 10

Input Quiz #4 Score: 7

Input Quiz #5 Score: 6

Input Quiz #6 Score: 9

Input Quiz #7 Score: 8

Input Exam #1 Score: 89

Input Exam #2 Score: 100

Input Exam #3 Score: 76

Progress Report

—————

John Smith

ID: 123456789

Average = 87.027%.

Score needed on a 200 point final for each letter grade is as follows.

Grade Needed Score

—– ————

<ul>

 <li>191</li>

 <li>134</li>

 <li>77</li>

 <li>20</li>

</ul>

Input Student’s Name: Martha Jones

Input Student’s ID: 987654321

Input Quiz #1 Score: 10

Input Quiz #2 Score: 9

Input Quiz #3 Score: 10

Input Quiz #4 Score: 10

Input Quiz #5 Score: 8

Input Quiz #6 Score: 10

Input Quiz #7 Score: 9

Input Exam #1 Score: 98

Input Exam #2 Score: 100

Input Exam #3 Score: 99

Progress Report

—————

Martha Jones

ID: 987654321

<table width="104">

 <tbody>

  <tr>

   <td width="64">Quiz</td>

   <td width="40">Score</td>

  </tr>

  <tr>

   <td width="64">—-</td>

   <td width="40">—–</td>

  </tr>

  <tr>

   <td width="64">1</td>

   <td width="40">10</td>

  </tr>

  <tr>

   <td width="64">2</td>

   <td width="40">9</td>

  </tr>

  <tr>

   <td width="64">3</td>

   <td width="40">10</td>

  </tr>

  <tr>

   <td width="64">4</td>

   <td width="40">10</td>

  </tr>

  <tr>

   <td width="64">5</td>

   <td width="40">8</td>

  </tr>

  <tr>

   <td width="64">6</td>

   <td width="40">10</td>

  </tr>

  <tr>

   <td width="64">7</td>

   <td width="40">9</td>

  </tr>

  <tr>

   <td width="64">Exam</td>

   <td width="40">Score</td>

  </tr>

  <tr>

   <td width="64">—-</td>

   <td width="40">—–</td>

  </tr>

  <tr>

   <td width="64">1</td>

   <td width="40">98</td>

  </tr>

  <tr>

   <td width="64">2</td>

   <td width="40">100</td>

  </tr>

  <tr>

   <td width="64">3</td>

   <td width="40">99</td>

  </tr>

 </tbody>

</table>

Average = 98.108%.

Score needed on a 200 point final for each letter grade is as follows.

Grade Needed Score

—– ————

<ul>

 <li>150</li>

 <li>93</li>

 <li>36</li>

 <li>0</li>

</ul>