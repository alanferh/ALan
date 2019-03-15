\\Cachorro.php

<?php

class Cachorro{

	public $cor;
	public $raca;
	public $nome;

}

\\ Test.php

<?php

require_once "Cachorro.php";

$cao1 = new Cachorro();
$cao1->nome = "Rex";
var_dump($cao1);
