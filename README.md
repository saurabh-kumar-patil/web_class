
<!DOCTYPE html>
<html>
<head>
  <title>RESPONSIVE IMAGE</title>
  <style>
    .container{
      border: 4px solid green;
      text-align: center;
      padding: 20px;
      display:flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .Name{
      background-color:lightblue;
      border: 4px solid green;
      padding: 5px;
    }
    #Name_1:hover{
        transform: scale(1.1);
        color: yellow;
        transition: 1.0s;
      }
    #Name_2:hover{
        color: yellow;
        transform: scale(1.1);
        transition: 1.0s;
      } 
    h1{
      text-align: center;
      font-stretch: 2px;
    }
    body{
      background-color: pink;
    }
    h2{
      text-align: center;
    }
 
    img{
      width:450px;
      height:350px;
      margin:5px;
      border:4px solid red;
    }
    .a:hover{
      transform: rotate(360deg);
      transition: 1.0s;
    }
    .b:hover{
      transform: scale(1.1);
      transition: 1.0s;
    }
    .c:hover{
      transform: rotate(360deg);
      transition: 1.0s;
    }
  </style>
</head>
<body>
  <div class="Name" id="Name_1">
      <h1>FLEXBOX</h1>
  <h2>Responsive image</h2>
  </div>

  <div class="container">
    <img class="a" src="https://tse3.mm.bing.net/th?id=OIP.Tz_WWDQfvtur3Y_BNLQTowHaEK&pid=Api&P=0&w=320&h=180">
    <img class="b" src="doraemon.jpeg" >
    <img class="c" src="doraemon1.png">
  </div>
  
  <div class="Name" id="Name_2">
    <h2>Name - Saurabh Kumar Patil <br>
        Roll No - 1906166</h2>    
  </div>
</body>
</html>
