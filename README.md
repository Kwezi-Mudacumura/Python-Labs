<h1>Python labs:</h1>
<ul>
  <li><h3>DoublingInput:</h3> </br> The following code reads in an integer from input and outputs the number with 5 added to it.</br>
Input consists of a single integer N.</br>
Output 2N</li>
  <li><h3>DifferenceBetweenTwoNumbers:</h3></br>The following program reads from input two real numbers and outputs their difference.</br>
Input consists of two real-valued numbers x and y, each on their own line.</br>
Output x − y.
 </li>
  <li><h3>Variance,Mean,StandardDeviation:</h3> </br> The following program computes and displays the mean, variance and standard deviation of four real numbers entered by a user. 
</br>To compute the mean, variance, and standard deviation of numbers a, b, c, d entered by a user, use the following three equations:<ul>
<li> 1. mean =(a + b + c + d)/4</li>
<li> 2. variance =((mean − a)^2 + (mean − b)^2 + (mean − c)^2 + (mean − d)^2)/4 </li>
<li> 3. standard deviation =√variance </li>
</ul>
</br>
Input consists of four real-valued numbers a, b, c, d, each on their own line.
Output the mean, variance and standard deviation of the numbers, each on a new line. 
</li>
<li><h3>MinimumBetweenThreeNumbers:</h3> </br> The following program for finding and displaying the minimum of three real-valued numbers entered
by a user. The following pseudocode was used for this program:</br> </br>
input x </br>
input y </br>
input z </br>
if x <= y </br>
  minimum = x </br>
else </br>
  minimum = y </br>
if z < minimum: </br>
  minimum = z </br>
display minimum </br>
   </br>
Input consists of a three real-valued numbers (of type float), each on a new line. </br>
Output the smallest of the three numbers.
</li>
  
<li><h3>GradeCodeAccordingtoGradeScore:</h3> </br>The following program accepts an integer in the range [0, 100] and outputs the corresponding
grade. Using the following list below to match the mark with the correct grade.</br>
<h4>Grade Mark</h4><ul>
<li>1.First: 75+</li>
<li>2.Upper second: 70 − 74</li>
<li>3.Lower second: 60 − 69</li>
<li>4.Third: 50 − 59</li>
<li>5.Fail: < 50</li>
</ul>
</br>
Input consists of a single integer specifying the mark then
the program outputs the corresponding grade.
 </li>

 <li><h3>Leap year</h3> </br>A leap year is a calendar year that contains one extra day.The following program that accepts a year
and outputs whether that year is a leap year or not. </br>The following rules determine leap years:<ul>
<li>• Years that are exactly divisible by 100 are only leap years if they are also divisible by 400</li>
<li>• Years that are not divisible by 100 but are divisible by 4 are leap years</li>
<li>• No other years are leap years</li>
</ul>
</br>
The input consists of a single year (a non-negative integer) y read from the user.
If the given year y is a leap year,the output [y] is a leap year; otherwise,the output
[y] is not a leap year
 </li>  

 <li><h3>Rock,Paper,Scissors</h3> </br> <p></p>In the popular game Rock-Paper-Scissors (RPS) two players compete against one another by
simultaneously making one of three hand symbols: rock, paper or scissors. The outcome of
the game depends on the symbols both players have chosen: a player who decides to play rock
beats another player who has chosen scissors (“rock crushes scissors”) but will lose to one who
has played paper (“paper covers rock”); a play of paper will lose to a play of scissors (“scissors
cuts paper”). If both players choose the same shape, the game is tied.</p>
The following program takes as input the choices made by two players (Player 1
and Player 2), and outputs the result.
</br>Input:</br>
Your program will receive 2 lines of input: the first line is Player 1’s choice (either rock, paper,
or scissors), while the second line is Player 2’s choice.
</br>Output:</br>
The result of the game have three possible outcomes:<ul>
<li>1. Player 1 wins</li>
<li>2. Player 2 wins</li>
<li>3. Tie      </li>
  </ul>
</li>
<li><h3>FindingMinimumBetweenAnyAmountOfNumbers:</h3> </br>The following program accepts many integers as input, and outputs the smallest one.</br></br>
Input:</br>
The input consists of a series of integers, one per line. The assumuption is that there will always
be at least one number given. The end of the input will be signalled by the number −1. When
you receive a −1, your program should then output the smallest number it has seen so far.
Note that −1 is completely ignored and thus isnt taken into consideration when
calculating the smallest number.
</br>
Output:</br>
Print out the minimum value of the numbers.                          

</li>

<li>
<h3>MeanOfAnyAmountOfNumbers</h3></br>The following program that accepts many real numbers as input, and outputs their average.
</br>
Input</br>
The input consists of a series of numbers, one per line. The assumption is that there will always
be at least one number given. The end of the input is signalled by the number −1. When
you receive a −1, your program will output the average of all numbers received. Note
that −1 is completely ignored and thus isnt taken into consideration when
calculating the average.
</br>
Output</br>
Print out the mean of the numbers.
</li>
<li>
  <h3>ShiftingEveryCharacterByOne</h3></br>The following program accepts a string then shifts each of its characters to the next one in the
alphabet, and outputs the resulting string.
The input consists of a single string. The assumption is that the string contains neither the
character ’Z’ nor ’z’, nor does it contain any spaces.
The output displays the string that results when each character in the given string is shifted to its following
letter in the alphabet.
  
</li>

<li>
<h3>VowelCount:</h3></br>Vowels are a useful feature of the English language[Citation required]. The following program that counts
how many vowels there are in a bunch of words.</br> Please note for our purposes, the letter ’y’ is not a vowel.
(And, for any Welsh people, neither is ’w’.)
</br>
</br>
The input consists of lines of text, terminated by a line with the value end. Each line
contains both upper- and lower-case letters, as well as spaces. The program terminates
when it accepts end as input.
The output is the number of vowels the given line contained.
</li>
<li>
<h3>ReverseInput:</h3></br>The following program reads in lines of data from the user, and then outputs the data in the reverse
order in which it was entered. Input is read in until the string ### is provided as input.
</br>
</br>
Input consists of a series of data, one per line. This data is of any datatype. Input is
terminated by the string ###, which isnt processed.
The output is of each line of input, but in the reverse order it was entered.
</li>
<li>
<h3>Median:</h3></br><p>The median is the middle value separating the greater and lesser halves of a data set. It can
be found by arranging all the numbers from smallest to greatest. If there is an odd number
of numbers, the middle one is picked. Otherwise, if there are an even number of numbers,
the median is defined to be the average of the two middle values.</p>The following
program calculates the median of a set of numbers.</br>
  
Input:</br>
The first line of input is a single integer N . N lines of input follow, with each line containing a
single integer number.
</br>
Output:</br>
Outputs the median of the numbers provided as input
</li>

<li>
<h3>MatchingMarksToNamesUsingDictionary</h3></br>The following program receives list of names and grades,then outputs the names in alphabetical order, with their associated grade.</br></br>
Input:</br>
The first line of input is an integer N. 2N lines follow, each containing a name and a mark on
their own lines. The assumpution is that the name is a single word, and that the mark is an integer.</br>
Output:</br>
The names and associated grades in alphabetical order. Each name is separated
from its grade by a space, a colon, and a single space






  
</li>
</ul>
