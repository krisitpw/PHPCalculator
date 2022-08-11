# PHPCalculator
In this project learn how to accept value input box and calculate value like sum, substract, multi, division and modulus
Using Technology 
HTML, CSS, Bootstrap, Core PHP

Easy to learn how to make simple calculator using above these technology.

if(isset($_POST['sum']))
{
	$a=$_POST['num1'];
    $b=$_POST['num2'];
    $Sum=$a + $b;
    
}
<input  type="submit" name="sum" value="+" class="btn btn-success" style="width: 50px; height: 50px;"> &nbsp; &nbsp;

The isset() function checks whether a variable is set, which means that it has to be declared and is not NULL.

This function returns true if the variable exists and is not NULL, otherwise it returns false.

Note: If multiple variables are supplied, then this function will return true only if all of the variables are set.

Tip: A variable can be unset with the unset() function.
	<?php
echo "<br>";
echo "<br>";
echo "<br>";
echo "<h2> Result Here = $Sum </h2>"  ;


	?>
  echo function print the value of given variable or final output of variable value.
  <h2>PHP echo and print Statements</h2>
echo and print are more or less the same. They are both used to output data to the screen.

The differences are small: echo has no return value while print has a return value of 1 so it can be used in expressions. echo can take multiple parameters (although such usage is rare) while print can take one argument. echo is marginally faster than print.
  
