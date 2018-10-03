```html
<!DOCTYPE html>
<html>
<head>
    <title></title>
    <style type="text/css">
        div,p,img,strong,span{ border: 2px solid yellowgreen} /*El unico inline que es afectado por altura anchura,etc es IMG*/
        div,p,img,strong,span{ padding: 5px; } 
        div,p,img,strong,span{ margin: 5px; }
        div,p,img,strong,span{ height: 85px; }
        div{ display: inline;}
        
        li{
             display: inline;
             border: 2px solid black;
             background-color: aqua;
             position: relative;
             position: central;

        }
        li:hover{
            background-color: blueviolet;
        }
    #image1{
        display: block;
    }
    </style>
</head>
<body>
<ul>
    <li>Inicio</li>
        <li>Carrito</li>
        <li>Contacto</li>
        <li>Login</li>
</ul>
    <div>Esto es div</div>
<p>Esto parrafo</p>
<span>Spann o Spam</span>
<strong>Strong</strong>
<img id= "image1" src="https://media1.tenor.com/images/22c509cacae4718fc62b1a1a03409d3a/tenor.gif?itemid=9050665" width="180">
<img src="https://media1.tenor.com/images/bacf5d896a369e1cceaeff0cddc7de79/tenor.gif?itemid=5279416" width="180">
<img src="https://media1.tenor.com/images/bacf5d896a369e1cceaeff0cddc7de79/tenor.gif?itemid=5279416" width="180">
<img src="https://media1.tenor.com/images/bacf5d896a369e1cceaeff0cddc7de79/tenor.gif?itemid=5279416" width="180">
<img src="https://media1.tenor.com/images/bacf5d896a369e1cceaeff0cddc7de79/tenor.gif?itemid=5279416" width="180">

<p>hola</p>
</body>
</html>

´´´
