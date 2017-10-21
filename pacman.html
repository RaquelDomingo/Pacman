<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Pacman</title>
    <style type="text/css">
      body{
        background-color: black;
        margin:0px;
      }
      div.row div{
        width: 20px;
        height: 20px;
        display:inline-block;
      }
      div.brick{
        background-color: #0b756a;
      }
      div.coin{
        background: url('coin.gif');
        background-repeat: no-repeat;
        background-position: center;
      }
      div.cherry{
			background: url('cherry.png');
			background-repeat: no-repeat;
			background-position: center;
			background-size: cover;
		  }
      div.empty{

      }
      div#pacman{
        background: url('pacman.gif');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        width: 20px;
        height: 20px;
        position:absolute;
      }
      div#score{
        border: 5px solid pink;
        width: 45px;
        height: 40px;
        color: white;
        padding: 7px;
        text-align: center;
        position: absolute;
        top: 70px;
        left: 810px;
        font-size: 25px;
      }
      div.points{
        font-size: 20px;
        color: white;
        position: absolute;
        top: 10px;
        left: 810px;
      }
      div.points img{
          width: 40px;
          height: 40px;
      }
    </style>
  </head>
  <body>

    <div id="container">
      <div id="world"></div>
      <div id="pacman"></div>
      <div id="score"></div>
      <div class="points">
        <h3>SCORE:</h3>
        <br>
        <br>
        <br>
        <img src="coin.gif"> 10 points
        <br>
        <img src="cherry.png"> 50 points
      </div>
    </div>
    <script>

    var world =  [
		[2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2],
		[2,1,1,1,1,1,1,1,1,1,1,1,1,1,3,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,3,1,1,1,1,1,1,2],
		[2,1,1,1,1,3,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2],
		[2,1,1,2,1,1,1,2,1,1,2,2,2,2,1,1,2,1,1,1,1,1,2,1,1,1,1,1,1,2,1,2,1,1,1,2,1,1,2],
		[2,1,1,2,1,1,1,2,1,1,2,1,1,1,1,1,2,1,1,1,1,1,2,1,1,1,1,1,2,1,1,1,2,1,1,2,1,1,2],
		[1,1,1,2,1,1,1,2,1,1,2,1,1,1,1,1,2,1,1,1,1,1,2,1,1,1,1,1,2,1,1,1,2,1,1,2,3,1,1],
		[1,1,1,2,2,2,2,2,1,1,2,2,2,2,1,1,2,1,1,3,1,1,2,1,1,1,1,1,2,1,3,1,2,1,1,2,1,1,1],
		[2,1,1,2,1,1,1,2,1,1,2,1,1,1,1,1,2,1,1,1,1,1,2,1,1,1,1,1,2,1,1,1,2,1,1,1,1,1,2],
		[2,1,1,2,1,1,1,2,1,1,2,2,2,2,1,1,2,2,2,2,1,1,2,2,2,2,1,1,1,2,1,2,1,1,1,2,1,1,2],
		[2,1,1,1,1,1,1,3,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2],
		[2,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,3,1,1,1,1,1,1,1,1,1,1,1,1,2],
		[2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2]
	];
    var score = 0;
    var pacman = {
        x: 1,
        y: 1
    };

    function displayWorld(){
      var output ='';

      for(var i=0; i<world.length; i++){
        output += "\n<div class='row'>\n";
        for(var j=0; j<world[i].length; j++){
            if(world[i][j] == 2)
                output += "<div class='brick'></div>";
            else if(world[i][j] == 1)
                output += "<div class='coin'></div>";
            else if(world[i][j] == 3)
    					   output += "<div class='cherry'></div>";
            else if(world[i][j] == 0)
                output += "<div class='empty'></div>";
        }
        output += "\n</div>";
      }
      // console.log(output);
      document.getElementById('world').innerHTML = output;
    }
    function displayPacman(){
      document.getElementById('pacman').style.top = pacman.y*24.5+"px";
      document.getElementById('pacman').style.left = pacman.x*20+"px";
    }
    function displayScore(){
      document.getElementById('score').innerHTML = score;
    }
    displayWorld();
    displayPacman();
    displayScore();

    document.onkeydown = function(e){
      if(e.keyCode == 37 && world[pacman.y][pacman.x-1] != 2 && pacman.x == 0){
			document.getElementById('pacman').style.transform = "rotate(-180deg)";
			pacman.x = world[0].length-1;
      }
      else if(e.keyCode == 37 && world[pacman.y][pacman.x-1] != 2 && pacman.x > 0){
        document.getElementById('pacman').style.transform = "rotate(-180deg)";

        pacman.x--;
      }
      else if(e.keyCode == 39 && world[pacman.y][pacman.x+1] != 2 && pacman.x == world[0].length-1){
			document.getElementById('pacman').style.transform = "none";
			pacman.x = 0;
      }
      else if(e.keyCode == 39 && world[pacman.y][pacman.x+1] != 2){
      document.getElementById('pacman').style.transform = "none";
      pacman.x++;
      }
      else if(e.keyCode == 38 && world[pacman.y-1][pacman.x] != 2 && pacman.y > 0){
			document.getElementById('pacman').style.transform = "rotate(-90deg)";
			pacman.y--;
		  }
      else if(e.keyCode == 40 && world[pacman.y+1][pacman.x] != 2){
			document.getElementById('pacman').style.transform = "rotate(90deg)";
			pacman.y++;
		  }

      if(world[pacman.y][pacman.x] == 1){
          world[pacman.y][pacman.x] = 0;
          score+=10;
          displayWorld();
          displayScore();
      }
      else if (world[pacman.y][pacman.x] == 3) {
    			world[pacman.y][pacman.x] = 0;
    			score+=50;
    			displayWorld();
    			displayScore();
  		}
      // console.log(e.keyCode);
      displayPacman();
    }
    </script>


  </body>
</html>
