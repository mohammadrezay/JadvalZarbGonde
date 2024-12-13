# JadvalZarbGonde.php
https://quera.org/problemset/3409?tab=description
<?php
$n = (int)readline("Enter a number : ");
$m = $n + 1;
for($i = 1; $i < $m; $i++){
	echo PHP_EOL;
	for($j = 1; $j < $m; $j++){
		echo $i * $j." ";
	}
}
