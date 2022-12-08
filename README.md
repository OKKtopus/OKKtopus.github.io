<html>
  <head>
    <title>Click to Earn Points</title>
  </head>
  <body>
    <h1>Click to Earn Points</h1>
    <p>Click the button below to earn points:</p>

    <button onclick="addPoints()">Earn Points</button>
    <p>You have <span id="points">0</span> points.</p>

    <script>
      let points = 0;
      function addPoints() {
        points++;
        document.getElementById('points').innerHTML = points;
      }
    </script>
  </body>
</html>
