# primeiroRepositorio
OLA VASCO
OLA VENESH
HELLO MY CIMENTO
OLA FRANCHESCO

KATIAU  
HEY LESGO VANISOUS E PETRERSNO
kkkkk 1 versão a menos
SAI SAMUEWL DESGRAÇAAA
OQ Q QUER DESGRAÇA DESFRAAÇAÇAK

ta bom mas stephen curry?
STEFEIN COURI

Cada dia uma frase nova?sim

Eu sou o escolhido pra ter erros em todas as programaões possiveis AAAAAAAAAAAAAAAAAAAAAAA





TABUADA EM PHP
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <title>Tabuada - Curso PHP - eXcript</title>
</head>

<body>

    <?php

    $tab = 0;
    if(isset($_POST["edTABUADA"])){
        $tab = $_POST["edTABUADA"];
        if(!is_numeric($tab)){
            echo "<br>O valor informado não é um número.<br>";
        }else{
    //            for($num=0; $num<=10; $num++){
    //                echo $num . " x " . $tab . " = " . ($num * $tab) . "<br>";
    //            }

        //$num x $tab = ($num * $tab)
        //0 x 5 = 0
        //1 x 5 = 5

        $num=0;
        while($num<=10){
            echo $num . " x " . $tab . " = " . ($num * $tab) . "<br>";
            $num++;
        }

    }
}

?>

<form method="post">
    <input type="text" name="edTABUADA" >
    <input type="submit">
</form>

</body>


</html>
