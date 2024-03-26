<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>eu tenho problemakk</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <script type="text/javascript">        

        function mensagem(){
            alert('YAAAAY THANK YOU!! <3')
            window.location.href='https://media.tenor.com/GZyF7v0Z-bwAAAAC/yuna-yuna-itzy.gif'
            
        }

        function f(){
            const generateRandomValue = () => Math.random() * (300 - 50) + 50;
            const formatValue = (value) => Math.ceil(value) + 'px';

            const top = generateRandomValue(); 
            const left = generateRandomValue(); 

            Bn.style.position = 'absolute'
            Bn.style.top =  formatValue(top);
            Bn.style.left = formatValue(left);
            
        }

        

    </script>


    <body>
    
        <div id="container">
            <h1>Can we hang out sometime?</h1>
            <div id="img">
                <img src="https://media.tenor.com/zGm5acSjHCIAAAAC/cat-begging.gif" alt="Pfv">
            </div>
        
            <footer>
                <button id="yes" onclick="mensagem()">YES</button>
                <div id="Bn">
                    <button id="no" onmouseenter="f()">
                        NO
                    </button>
                </div>
            </footer>
        </div>
</body>
</html>
