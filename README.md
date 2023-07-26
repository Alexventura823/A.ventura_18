<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>De Ventura</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: rgb(192, 37, 102);
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('TE JODISTE, AHORA YA SOMOS NOVIOS XD <3 ');
            alert('SALUDAME MI AMOR  by: VENTURA <3 ');
            alert('ES BROMA, PERO SI QUIERES NO ES BROMA')     
           
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";
            

        }
    </script>
</head>
<body>
    <h1> ¿QUIERES SER MI NOVIA? </h1>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <img src="chuec.png" width="550">
    
</body>
</html>
