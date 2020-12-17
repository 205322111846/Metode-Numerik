<?php 
function y($x) 
{ 
	
	// Declaring the function  
	return (($x*$x*$x)+(2*$x)+2); 
} 

// Function to evalute the 
// value of integral 
function trapezoidal($a, $b, $n) 
{ 
	
	// Grid spacing 
	$h = ($b - $a) / $n; 

	// Computing sum of first 
	// and last terms 
	// in above formula 
	$s = y($a) + y($b); 

	// Adding middle terms 
	// in above formula 
	for ($i = 1; $i < $n; $i++) 
		$s += 2 * Y($a + $i * $h); 

	// h/2 indicates (b-a)/2n. 
	// Multiplying h/2 with s. 
	return ($h / 2) * $s; 
} 

	// Driver Code 
	// Range of definite integral 
	$x0 = 0; 
	$xn = 5; 

	// Number of grids. 
	// Higher value means 
	// more accuracy 
	$n = 100; 

	echo("Value of integral is "); 
	echo(trapezoidal($x0, $xn, $n)); 
	
// This code is contributed by nitin mittal 
?> 
