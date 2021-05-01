<head>
<style>
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto auto auto auto auto;
  background-color: #000;
  padding: 10px;
}
.grid-item {
  background-color: rgba(255, 255, 255, 0.8);
  border: 1px solid rgba(0, 0, 0, 0.8);
  font-size: 30px;
  text-align: center;
}
</style>
</head>
<body>

<div class="grid-container">
  <div class="grid-item">
    <button type="button" onclick="put(1,1)">
      <img id="r1c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,2)">
      <img id="r1c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,3)">
      <img id="r1c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,4)">
      <img id="r1c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,5)">
      <img id="r1c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,6)">
      <img id="r1c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,7)">
      <img id="r1c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(1,8)">
      <img id="r1c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(2,1)">
      <img id="r2c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,2)">
      <img id="r2c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,3)">
      <img id="r2c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,4)">
      <img id="r2c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,5)">
      <img id="r2c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,6)">
      <img id="r2c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,7)">
      <img id="r2c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(2,8)">
      <img id="r2c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(3,1)">
      <img id="r3c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,2)">
      <img id="r3c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,3)">
      <img id="r3c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,4)">
      <img id="r3c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,5)">
      <img id="r3c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,6)">
      <img id="r3c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,7)">
      <img id="r3c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(3,8)">
      <img id="r3c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(4,1)">
      <img id="r4c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,2)">
      <img id="r4c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,3)">
      <img id="r4c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,4)">
      <img id="r4c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,5)">
      <img id="r4c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,6)">
      <img id="r4c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,7)">
      <img id="r4c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(4,8)">
      <img id="r4c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(5,1)">
      <img id="r5c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,2)">
      <img id="r5c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,3)">
      <img id="r5c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,4)">
      <img id="r5c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,5)">
      <img id="r5c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,6)">
      <img id="r5c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,7)">
      <img id="r5c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(5,8)">
      <img id="r5c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(6,1)">
      <img id="r6c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,2)">
      <img id="r6c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,3)">
      <img id="r6c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,4)">
      <img id="r6c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,5)">
      <img id="r6c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,6)">
      <img id="r6c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,7)">
      <img id="r6c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(6,8)">
      <img id="r6c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(7,1)">
      <img id="r7c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,2)">
      <img id="r7c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,3)">
      <img id="r7c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,4)">
      <img id="r7c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,5)">
      <img id="r7c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,6)">
      <img id="r7c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,7)">
      <img id="r7c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(7,8)">
      <img id="r7c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
    <div class="grid-item">
    <button type="button" onclick="put(8,1)">
      <img id="r8c1" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,2)">
      <img id="r8c2" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,3)">
      <img id="r8c3" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,4)">
      <img id="r8c4" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,5)">
      <img id="r8c5" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,6)">
      <img id="r8c6" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,7)">
      <img id="r8c7" src="assets/empty-pawn.jpg">
      </button>
  </div>
  <div class="grid-item">
    <button type="button" onclick="put(8,8)">
      <img id="r8c8" src="assets/empty-pawn.jpg">
      </button>
  </div>
</div>
<script>
  var grid = [
  ["sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel"],
  ["sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel"],
  ["sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel"],
  ["sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel"],
  ["sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel"],
  ["sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel"],
  ["sentinel","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","empty-pawn","sentinel"],
  ["sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel","sentinel"],
  ];
  enemySpawn();
  async function put(row, column) {
    if(grid[row][column]=="empty-pawn") {
      grid[row][column] = "red-pawn";
      document.getElementById("r"+row+"c"+column).src = "assets/red-pawn.jpg";
      enemySpawn();
    }
  }
  function enemySpawn() {  //generate up to 3 new enemies in random positions
    var row;
    var column;
    for(var i=0; i<3; i++) {
      row = getRandomInt(1,8);
      column = getRandomInt(1,8);
      if(grid[row][column]=="empty-pawn") {
        grid[row][column] = "dark-pawn";
        document.getElementById("r"+row+"c"+column).src = "assets/dark-pawn.jpg";
      }
    }
  }
  function getRandomInt(min, max) {
    min = Math.ceil(min);
    max = Math.floor(max);
    return Math.floor(Math.random() * (max - min + 1)) + min;
  }
</script>
</body>
