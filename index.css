<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Master</title>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
   
   <style>
    *{
        margin: 0;
        padding: 0;
    }
    .fundo{
        background-image: url(smile.jpg);
        height: 100vh; 
        color: #fff; 
        font-family: Georgia, 'Times New Roman', Times, serif;
        text-align: center;
        
        

        }
 
        

    .calculadora{
        position: absolute;
        background-color: rgba(0, 0, 0, 0.7);
        top:50%;
        left:50%;
        transform: translate(-50%, -50%);
        border-radius: 15px;
        padding: 15px;
        color: #fff;
        font-family: 'Tangerine', serif;


    }
    .botao{
        background-color: rgba(31,31,31);
        width: 50px;
        height: 50px;
        font-size: 25px;
        cursor:pointer;
        border: none;
        color: #fff;
        margin: 3px;
    }
    .botao:hover{
        background-color: black;


    }
    #resultado{
        width:207px;
        background-color: #fff;
        height: 30px;
        margin: 12px;
        color: black;
        font-size: 26px;
        text-align: right;

    }
    .nome{
        text-align: center;
        background-color: black;
        color: #fff;
        position: absolute;
        bottom: 0%;
        height: 25px;
        line-height: 25px;
        width: 100%;
        background-size: 25%;
        font-family: Stencil Std, fantasy;
        
    



    
        

        
    }
    .fundo:hover {
        color: rgb(0, 166, 255);
        font-family: 'Tangerine', serif;

    }
    



    </style>
    <div class=" nome "> <footer> Criador por Carolina Almeida </footer> </div>

</head>
<body>
    
    <div class="fundo">

<div class="calculadora">          
<h1>calculadora</h1>
        
<p id="resultado"></p>

<div class="body"> 


 <table>
    <tr> 
        <td> <button class="botao" onclick="clean('')">c</button></td>
        <td> <button class="botao" onclick="back()">></button></td>
        <td> <button class="botao" onclick="insert('/')">/</button></td>
        <td> <button class="botao" onclick="insert('*')">X</button></td>

    </tr>

    <tr> 
        <td> <button class="botao" onclick="insert('7')">7</button></td>
        <td> <button class="botao" onclick="insert('8')">8</button></td>
        <td> <button class="botao" onclick="insert('9')">9</button></td>
        <td> <button class="botao" onclick="insert('-')">-</button></td>

    </tr>
    <tr> 
        <td> <button class="botao" onclick="insert('4')">4</button></td>
        <td> <button class="botao" onclick="insert('5')">5</button></td>
        <td> <button class="botao" onclick="insert('6')">6</button></td>
        <td> <button class="botao" onclick="insert('+')">+</button></td>

    </tr>
    <tr> 
        <td> <button class="botao" onclick="insert('1')">1</button></td>
        <td> <button class="botao" onclick="insert('2')">2</button></td>
        <td> <button class="botao" onclick="insert('3')">3</button></td>
        <td rowspan="2"> <button class="botao" style="height: 106px;" onclick="calcular()">=</button></td>

    </tr>
    <tr> 
        <td colspan="2"> <button class="botao" style="width: 106px;" onclick="insert('0')">0</button></td>
        <td> <button class="botao" onclick="insert('.')">.</button></td>

    </tr>
 </table>

    </div>

    <script>
        function insert (num)
    {
       var numero = document.getElementById('resultado') .innerHTML;
       document.getElementById('resultado').innerHTML = numero + num;

    }

    function clean ()
    {
    document.getElementById ('resultado').innerHTML = "";
    }

    function back ()
    {
        var resultado= document.getElementById ('resultado').innerHTML;
        document.getElementById('resultado').innerHTML = resultado.substring(0, resultado.length -1)
    }
    function calcular()
    {
        var resultado= document.getElementById ('resultado').innerHTML; 
        if(resultado)

    
        document.getElementById('resultado').innerHTML = eval(resultado);
        
     }

    

    </script>

    


</body>
</html>
