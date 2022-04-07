### Hi there 👋

- 🌱 I’m currently learning Flutter, Dart...
- 💬 Ask me about Dart, Bloc, Provider, Hive
- ⚡️ Fun fact I am very HAPPY :) 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text animation</title>
    <link rel="stylesheet" href="style.css">
    <script src="index.js"></script>
    <style>
        *{
    margin: 0;
    padding: 0;
}
body{
    background: #000;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;

}
#write{

    color: hsla(0, 2%, 40%, 0.979);
    font-size: 50px;
    font-weight: bold;
    cursor: pointer;
    font-family: monospace;
    background-image: linear-gradient(
        to right ,
        hsl(0, 1%, 30%) 0,hsl(0,0%,100%) 10%,hsl(0,0%,30%) 20%);
       -webkit-background-clip: text;
       -webkit-text-fill-color: transparent;
       animation: shine 3s infinite linear;
       padding: 60px;



}

@keyframes shine {
    0%{
        background-position: 0;
    }
    60%{
        background-position: 600px;
    }
    100%{
        background-position: 6000px;
    }
}
    </style>
       
</head>
<body>
    <h1 id="write">Shohruh0402</h1>
    <!-- <script>
        let  avl  =  prompt("What is name?");
let h1=document.getElementById('write');
h1.innerHTML=avl;

    </script> -->
</body>
</html>
