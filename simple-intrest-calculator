<!DOCTYPE html>
<html>
<head>
  <title>Simple Interest Calculator</title>
</head>
<body>
  <h2>Simple Interest Calculator</h2>
  <form onsubmit="calc(); return false;">
    Principal: <input id="p" type="number"><br><br>
    Rate (%): <input id="r" type="number"><br><br>
    Time (years): <input id="t" type="number"><br><br>
    <button type="submit">Calculate</button>
  </form>
  <h3 id="result"></h3>

  <script>
    function calc() {
      let p = +document.getElementById("p").value;
      let r = +document.getElementById("r").value;
      let t = +document.getElementById("t").value;
      let si = (p * r * t) / 100;
      document.getElementById("result").innerText =
        "Simple Interest = " + si;
    }
  </script>
</body>
</html>
