<h1 align="center">
  <br>
  <a href="http://www.amitmerchant.com/electron-markdownify"><img src="https://art.pixilart.com/f9d02ba31d48e6f.png" alt="Markdownify" width="200"></a>
  <br>
  By LittleToxicBoy
  <br>
</h1>
<h4 align="center">String Calculator Kata - Solucion en java </h4>

<hr>

## Step 1
Create a simple String calculator with a method signature:

` int Add(string numbers)`

The method can take up to two numbers, separated by commas, and will return their sum.

For example “” or “1” or “1,2” as inputs.

For an empty string it will return 0.

<hr>

## Step 2

Allow the Add method to handle an unknown amount of numbers.

<hr>

## Step 3
Allow the Add method to handle new lines between numbers (instead of commas):

The following input is ok: “1\n2,3” (will equal 6)

The following input is NOT ok: “1,\n” (not need to prove it - just clarifying)

<hr>

## Step 4
Support different delimiters:

To change a delimiter, the beginning of the string will contain a separate line that looks like this: “//[delimiter]\n[numbers…]” for example “//;\n1;2” should return three where the default delimiter is ‘;’.

The first line is optional. All existing scenarios should still be supported.

<hr>

## Step 5
Calling Add with a negative number will throw an exception “negatives not allowed” - and the negative that was passed.

If there are multiple negatives, show all of them in the exception message.

<hr>

## Step 6
Numbers bigger than 1000 should be ignored, so adding 2 + 1001 = 2

<hr>

## Step 7
Delimiters can be of any length with the following format: “//[delimiter]\n” for example: “//[***]\n1***2***3” should return 6.

<hr>

## Step 8
Allow multiple delimiters like this: “//[delim1][delim2]\n” for example “//[*][%]\n1*2%3” should return 6.

<hr>

## Step 9
Make sure you can also handle multiple delimiters with length longer than one char.