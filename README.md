<!DOCTYPE html>
<html lang="pt--br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora</title>
    <link rel="stylesheet" href="style.css">
    <script src="calculadora.js"></script>
</head>
<body>
    <div class="fundo">
        <h1>Seu Nome</h1>
        <div class="calculadora">
            <h2>Calculadora</i></h2>
            <p id="resultado"></p>
                <table>                 
                    <tr>
                        <td><button class="botao" onclick="clean()">C</td>
                        <td><button class="botao" onclick="back()"><</td>
                        <td><button class="botao" onclick="insert('/')">/</button></td>
                        <td><button class="botao" onclick="insert('*')">*</button></td>
                    </tr>
                    <tr>
                        <td><button class="botao" onclick="insert('7')">7</button></td>
                        <td><button class="botao" onclick="insert('8')">8</button></td>
                        <td><button class="botao" onclick="insert('9')">9</button></td>
                        <td><button class="botao" onclick="insert('-')">-</button></td>
                    </tr>
                    <tr>
                        <td><button class="botao" onclick="insert('4')">4</button></td>
                        <td><button class="botao" onclick="insert('5')">5</button></td>
                        <td><button class="botao" onclick="insert('6')">6</button></td>
                        <td><button class="botao" onclick="insert('+')">+</button></td>
                    </tr>
                    <tr>
                        <td><button class="botao" onclick="insert('1')">1</button></td>
                        <td><button class="botao" onclick="insert('2')">2</button></td>
                        <td><button class="botao" onclick="insert('3')">3</button></td>
                        <td rowspan="2"><button class="botao" style="height: 106px;" onclick="calcular()">=</button></td>
                    </tr>
                    <tr>
                        <td colspan="2"><button class="botao" style="width: 106px;" onclick="insert('0')">0</button></td>
                        <td><button class="botao" onclick="insert('.')">.</button></td>
                    </tr>
                </table>
        </div>
    </div>
</body>
</html>

