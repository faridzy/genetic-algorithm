
#### example 
<pre><code>
require 'GeneticAlgorithm.php'; 

$ga = new GeneticAlgorithm(array(
	'mutation' => 25, // 25%
	'goal' => 'Andre Tenosel',
	
	'delay' => 50, // ms, if debug is false, then delay forced to 0
	'debug' => true,
));

$ga->run(); 
</code></pre>
