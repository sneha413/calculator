# calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    
    <style>
        #cal{
            align-items: center;
            margin-left: 35em;
            margin-top: 10em;
            margin-right: 35em;
            justify-content: center;
            
        }
        #text{
            margin-bottom: 2em;
            padding: 1em;
            width: 20em;
            text-align: end;
            justify-content: flex-end;
        }
        button{
            padding: 1em;
            margin: 3px;
            color: black;
            width: 5em;
            
        }
        h1{
            margin: 1em;
            align-items: left;
        }
    </style>
</head>
<body>
    <div id="cal">
    <h1>Calculator</h1>
    <input id="text" type="text" value=" "><br>
   
    <button onclick="text.value = ' '">AC</button> 
    <button onclick="text.value += ' %'">%</button>
    <button onclick="text.value = text.value . toString().slice (0,-1)">Del</button>
    <button onclick="text.value += ' /'">/</button>
    <br>
    <button onclick="text.value += '7'">7</button>
    <button onclick="text.value += '8'">8</button>
    <button onclick="text.value += '9'">9</button>
    <button onclick="text.value += ' *'">*</button>
    <br>
    <button onclick="text.value += '4'">4</button>
    <button onclick="text.value += '5'"> 5</button>
    <button onclick="text.value += '6'">6</button>
    <button onclick="text.value  += ' -'">-</button>
    <br>
    <button onclick="text.value += '1'">1</button>
    <button onclick="text.value += '2'">2</button>
    <button onclick="text.value += '3'">3</button>
    <button onclick="text.value += '+'">+</button>
    <br>
    <button onclick="text.value += '00'">00</button>
    <button onclick="text.value += '0'">0</button>
    <button onclick="text.value += '. '">.</button>
    <button onclick="text.value = eval(text.value) ">=</button>
</div>
</body>
</html>
