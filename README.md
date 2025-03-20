# arreglo-de-figuras-
mi primer arreglo =)

<?php
	//echo "china";
	
 $figuras = array("triangulo", "cuadrado", "rectangulo,", "obalo", "rombo" ,"octagono");
 $figuras[] ="obalo";
 print_r($figuras);
	
	//$nombres= ["juan", "pedro", "alejandro", "felipe", "thomas"];
	
	//unset($nombres[3]);
	
	//print_r($nombres);
	
	$figurasEliminar = "cuadrado";
	$llave = array_search($figurasEliminar, $figuras);
	if($llave!==false){
	  unset($figuras[$llave]);
	}
	print_r($figuras)
?>;
