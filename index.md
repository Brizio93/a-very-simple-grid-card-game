<head>
   <style>
     figure.handCard {
       text-align: center;
     }
   </style>
</head>
<html>
   <body>
      <figure class="handCard">
         <img id="handCard" width="70" height="70">
         <figcaption id="handCardCaption"></figcaption>
      </figure>
      <span style="padding-left:25px"></span>
      <button type="button" onclick="put(1,1)">
         <img id="r1c1" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(1,2)">
         <img id="r1c2" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(1,3)">
         <img id="r1c3" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(1,4)">
         <img id="r1c4" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(1,5)">
         <img id="r1c5" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <br>
      <span style="padding-left:25px"></span>
      <button type="button" onclick="put(2,1)">
         <img id="r2c1" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(2,2)">
         <img id="r2c2" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(2,3)">
         <img id="r2c3" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(2,4)">
         <img id="r2c4" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(2,5)">
         <img id="r2c5" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <br>
      <span style="padding-left:25px"></span>
      <button type="button" onclick="put(3,1)">
         <img id="r3c1" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(3,2)">
         <img id="r3c2" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(3,3)">
         <img id="r3c3" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(3,4)">
         <img id="r3c4" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(3,5)">
         <img id="r3c5" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <br>
      <span style="padding-left:25px"></span>
      <button type="button" onclick="put(4,1)">
         <img id="r4c1" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(4,2)">
         <img id="r4c2" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(4,3)">
         <img id="r4c3" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(4,4)">
         <img id="r4c4" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(4,5)">
         <img id="r4c5" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <br>
      <span style="padding-left:25px"></span>
      <button type="button" onclick="put(5,1)">
         <img id="r5c1" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(5,2)">
         <img id="r5c2" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(5,3)">
         <img id="r5c3" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(5,4)">
         <img id="r5c4" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(5,5)">
         <img id="r5c5" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <br>
      <span style="padding-left:25px"></span>
      <button type="button" onclick="put(6,1)">
         <img id="r6c1" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(6,2)">
         <img id="r6c2" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(6,3)">
         <img id="r6c3" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(6,4)">
         <img id="r6c4" src="assets/empty-token.jpg" width="70" height="70">
      </button>
      <button type="button" onclick="put(6,5)">
         <img id="r6c5" src="assets/empty-token.jpg" width="70" height="70">
      </button>

      <script>
        var waitFlag = false;
        const cards = ["white-rock", "white-paper", "white-scissors"];
        var currentCard = cards[Math.floor(Math.random() * cards.length)];
        const enemyCards = ["black-rock", "black-paper", "black-scissors"];
        var enemyCurrentCard = enemyCards[Math.floor(Math.random() * enemyCards.length)];
        const tokenWinLose = [
          ["rock", "scissors", "paper"],
          ["paper", "rock", "scissors"],
          ["scissors", "paper", "rock"],
        ]
        var freeBoxes = [[1,1],[1,2],[1,3],[1,4],[1,5],[2,1],[2,2],[2,3],[2,4],[2,5],[3,1],[3,2],[3,3],[3,4],[3,5],
          [4,1],[4,2],[4,3],[4,4],[4,5],[5,1],[5,2],[5,3],[5,4],[5,5],[6,1],[6,2],[6,3],[6,4],[6,5]];
        var grid = [
          ["sentinel", "sentinel", "sentinel", "sentinel", "sentinel", "sentinel", "sentinel"],
          ["sentinel", "empty-token", "empty-token", "empty-token", "empty-token", "empty-token", "sentinel"],
          ["sentinel", "empty-token", "empty-token", "empty-token", "empty-token", "empty-token", "sentinel"],
          ["sentinel", "empty-token", "empty-token", "empty-token", "empty-token", "empty-token", "sentinel"],
          ["sentinel", "empty-token", "empty-token", "empty-token", "empty-token", "empty-token", "sentinel"],
          ["sentinel", "empty-token", "empty-token", "empty-token", "empty-token", "empty-token", "sentinel"],
          ["sentinel", "empty-token", "empty-token", "empty-token", "empty-token", "empty-token", "sentinel"],
          ["sentinel", "sentinel", "sentinel", "sentinel", "sentinel", "sentinel", "sentinel"]
        ];
        freeBoxes = shuffle(freeBoxes);
        showCard();
        async function put(row, column) {
          if(grid[row][column]=="empty-token" && waitFlag==false) {
            waitFlag = true;
            document.getElementById("handCard").src = "assets/wait.jpg";
            document.getElementById("handCardCaption").innerHTML = "Attendi..";
            grid[row][column] = currentCard;
            updateFreeBoxes(row, column);
            document.getElementById("r"+row+"c"+column).src = "assets/"+currentCard+".jpg";
            await new Promise(r => setTimeout(r, 500));
            resolveClashAround(row, column);
            await new Promise(r => setTimeout(r, 1000));
            const enemyTarget = freeBoxes.pop();
            const enemyRow = enemyTarget[0];
            const enemyColumn = enemyTarget[1]
            enemyCurrentCard = enemyCards[Math.floor(Math.random() * enemyCards.length)];
            grid[enemyRow][enemyColumn] = enemyCurrentCard;
            document.getElementById("r"+enemyRow+"c"+enemyColumn).src = "assets/"+enemyCurrentCard+".jpg";
            await new Promise(r => setTimeout(r, 500));
            resolveClashAround(enemyRow, enemyColumn);
            if(freeBoxes.length==0) {
              endGame();
            }
            else {
              currentCard = cards[Math.floor(Math.random() * cards.length)];
              showCard();
            }
            waitFlag = false;
          }
        }
        function showCard() {
          document.getElementById("handCard").src = "assets/"+currentCard+".jpg";
          document.getElementById("handCardCaption").innerHTML = "Posizionala:";
        }
        function resolveClashAround(row, column){
          var token = grid[row][column].split("-")[1];
          var win;
          var lose;
          for(var k=0; k<3; k++) {
            if(tokenWinLose[k][0]==token) {
              win = tokenWinLose[k][1];
              lose = tokenWinLose[k][2];
            }
          }
          for(var i=row-1; i<=row+1; i++) {
            for(var j=column-1; j<=column+1; j++) {
              if(grid[i][j].split("-")[1]==win) {
                grid[i][j] = "destroyed-token";
                document.getElementById("r"+i+"c"+j).src = "assets/destroyed-token.jpg";
              }
              else if(grid[i][j].split("-")[1]==lose) {
                grid[row][column] = "destroyed-token";
                document.getElementById("r"+row+"c"+column).src = "assets/destroyed-token.jpg";
              }
            }
          }
        }
        function endGame() {
          var whitePoints = 0;
          var blackPoints = 0;
          for(var i=1; i<=6; i++) {
            for(var j=1; j<=5; j++) {
              if(grid[i][j].split("-")[0]=="white") {
                whitePoints++;
              }
              else if(grid[i][j].split("-")[0]=="black") {
                blackPoints++;
              }
            }
          }
          document.getElementById("handCardCaption").innerHTML = whitePoints + "-" + blackPoints;
          if(whitePoints>blackPoints) {
            document.getElementById("handCard").src = "assets/win.jpg";
          }
          else {
            document.getElementById("handCard").src = "assets/lose.jpg";
          }
        }
        function updateFreeBoxes(row, column){
          for(var i=0; i<freeBoxes.length; i++) {
            if(freeBoxes[i][0]==row && freeBoxes[i][1]==column) {
              freeBoxes.splice(i, 1);
            }
          }
        }
        function shuffle(array) {
          var currentIndex = array.length, temporaryValue, randomIndex;
          while (0 !== currentIndex) {
            randomIndex = Math.floor(Math.random() * currentIndex);
            currentIndex -= 1;
            temporaryValue = array[currentIndex];
            array[currentIndex] = array[randomIndex];
            array[randomIndex] = temporaryValue;
          }
          return array;
        }
      </script>

   </body>
</html>
