<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EDUARDO | www.com</title>
    <link rel="stylesheet" href="css/estilo.css">
</head>
<body>

    


<a href="https://pt.pornhub.com/">
<div class="caixa">

    <h1>Entrar</h1>

</div>
</a>



</body>
</html
    
 *{
padding: 0;
margin: 0;
box-sizing: border-box;
}

body{
display: flex;
justify-content: center;
align-items: center;
min-height: 100vh;
background-color: #000000;

}

.caixa{
position: relative;
width: 400px;
height: 400px;
color: aliceblue;
background-color: rgb(59, 59, 59);
justify-content: center;
align-items: center;
display: flex;
font: bold 2px ;
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}


@keyframes animacaocaixa{

    0%{
    background-position: 0;
    
    }
    100%{
        background-position: 100;
    
    }
    
    
    }

.caixa::before, .caixa::after{
content: '';
z-index: -1;
position: absolute;
width: calc(100% + 20px);
height: calc(100% + 20px);
background: linear-gradient(45deg, #ffff00, #00ff00, #0099ff, #001aff, #a200ff, #ff0055, #ff0000, #ffff00, #00ff00, #0099ff, #001aff, #a200ff);
background-size: 150%;
background-repeat: no-repeat;
border-radius: 5px;
animation: animacaocaixa 8s;
}




.caixa::after{
filter: blur(30px);


}

a{
cursor: pointer;
text-decoration: none;

}   
