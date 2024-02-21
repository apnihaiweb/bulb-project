:::::: HTML File code ::::::

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0"> -->
  <title>Blub Projects</title>
  <link rel="stylesheet" href="cs.css">
</head>
<body>
  <!-- <bg color="black"/> -->
  <center>
  <h1>My First Project  Buld On & Off
</h1>

  <div class="ali">

  </div>
  <button id="btn1"><a href="#">ON</a>
  </button>
  <button id="btn2"><a href="#">OFF</a>
  </button>
</center>
  <script src="ja.js"></script>
</body>
</html>


:::::: CSS File code ::::::



body{
    background-color: grey;
}
.ali{
    height: 200px;
    width: 200px;
    border-radius: 50%;
    border: 4px solid black;
    /* background-color: yellow; */


    }

    button{
        /* padding: 20px; */
        margin-top: 20px;
        margin-left: 20px;
        padding-left: 50px;
        padding-right: 50px;
        padding-top: 30px;
        padding-bottom: 30px;
        border-radius: 20px;
        font-weight: bold;
        font-style: oblique;
        font-size: larger;
        /* position: relative; */
        background-color: aqua;
        

        
    }


    :::::  JavaScript Code :::::


    


var a = document.querySelector(".ali")
var b = document.querySelector("#btn1")
var c = document.querySelector("#btn2")

b.addEventListener('click',function(){
    a.style.backgroundColor="yellow"
})

c.addEventListener('click',function(){
    a.style.backgroundColor="transparent"
})

