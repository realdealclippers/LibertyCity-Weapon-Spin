<!DOCTYPE html>
<html>
<head>
  <title>Liberty City RP Spin</title>
  <style>
    body {
      background: #111;
      color: white;
      text-align: center;
      font-family: Arial;
    }

    h1 { margin-top: 20px; }

    #wheel {
      width: 320px;
      height: 320px;
      border-radius: 50%;
      border: 6px solid white;
      margin: 30px auto;
      transition: transform 4s cubic-bezier(0.2, 0.8, 0.2, 1);
      background: conic-gradient(
        #555 0% 20%,
        #1e90ff 20% 40%,
        #32cd32 40% 60%,
        #ff8c00 60% 80%,
        gold 80% 100%
      );
    }

    button {
      padding: 12px 25px;
      font-size: 18px;
      border: none;
      background: gold;
      cursor: pointer;
    }

    #result {
      margin-top: 20px;
      font-size: 22px;
    }
  </style>
</head>
<body>

<h1>🎡 Liberty City RP Gun Spin</h1>

<div id="wheel"></div>

<button onclick="spin()">SPIN</button>

<p id="result"></p>

<script>
const rewards = [
  {name: "Nothing", weight: 40},
  {name: "Glock", weight: 25},
  {name: "SMG", weight: 20},
  {name: "Draco", weight: 10},
  {name: "Switch", weight: 5}
];

function weightedRandom() {
  let total = rewards.reduce((sum, r) => sum + r.weight, 0);
  let rand = Math.random() * total;

  for (let r of rewards) {
    if (rand < r.weight) return r.name;
    rand -= r.weight;
  }
}

function spin() {
  let wheel = document.getElementById("wheel");

  let result = weightedRandom();
  let randomDeg = 360 * 6 + Math.floor(Math.random() * 360);

  wheel.style.transform = `rotate(${randomDeg}deg)`;

  setTimeout(() => {
    document.getElementById("result").innerText =
      "You got: " + result;
  }, 4000);
}
</script>

</body>
</html>
