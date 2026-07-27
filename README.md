<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>DRH LUDO</title>
</head>
<body>
  <h1>🎲 DRH LUDO</h1>

  <button onclick="rollDice()">Roll Dice</button>

  <p id="dice">Dice: -</p>

  <script>
    function rollDice() {
      let dice = Math.floor(Math.random() * 6) + 1;
      document.getElementById("dice").innerText = "Dice: " + dice;
    }
  </script>
</body>
</html>
