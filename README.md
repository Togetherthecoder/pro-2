# pro-2.  
`<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta http-equiv="X-UA-Compatible" content="IE=Edge">

  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>pro-1</title>

  <link rel="stylesheet" href="style.css">

</head>
<style>

*{

  margin: 0;

  padding: 0;

  box-sizing: border-box;

  font-family: cursive; 

}

.center{

  display: flex;

  justify-content: center;

  align-items: center;

}

.main{

  height: 100vh;

}

.box{

  width: 450px;

  height: 350px;

  background: #000000;

  border-radius: 20px;

  box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.363);

}

li{

  width: 300px;

  padding: 15px;

  color: #ffff;

  background: #151515;

  list-style: none;

  margin: 12px;

  cursor: pointer;

  transition: all .4s;

  position: relative;

}

li:hover{

  transform: translate(20px);

}

li::before, li::after{

  content: "";

  position: absolute;

  background: #151515;

  transition: all .4s;

}

li::before{

  width: 20px;

  height: 100%;

  top: 0;

  left: -30px;

}

li::after{

  width: 100%;

  height: 2px;

  bottom: 0;

  left: 0;

}

li:hover::before, li:hover::after{

  background: #00ffff;

  box-shadow: 0 0 10px aqua;

}

</style>
<body>

  <div class="main center">

    <div class="box center">

      <ul>

        <li>HTML</li>

        <li>CSS</li>

        <li>JAVASCRIPT</li>

        <li>PYTHON</li>

      </ul>

      

    </div>

    

  </div>

</body>

</html>`
