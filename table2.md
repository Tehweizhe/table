<!DOCTYPE html>
<html>
<head>
  <title>Table 2</title>
  <script>
    function calculateValues() {
      var values = {
        "A1": 41,
        "A2": 18,
        "A3": 21,
        "A4": 63,
        "A5": 2,
        "A6": 53,
        "A7": 5,
        "A8": 57,
        "A9": 60,
        "A10": 93,
        "A11": 28,
        "A12": 3,
        "A13": 90,
        "A14": 39,
        "A15": 80,
        "A16": 88,
        "A17": 49,
        "A18": 60,
        "A19": 26,
        "A20": 28
      };

      var alphaValue = values["A5"] + values["A20"];
      var betaValue = values["A15"] / values["A7"];
      var charlieValue = values["A13"] * values["A12"];

      document.getElementById("alphaValue").innerText = alphaValue;
      document.getElementById("betaValue").innerText = betaValue;
      document.getElementById("charlieValue").innerText = charlieValue;
    }
  </script>
</head>
<body onload="calculateValues()">

<h2>Table 2</h2>

<table>
  <tr>
    <th>Category</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>Alpha</td>
    <td id="alphaValue"></td>
  </tr>
  <tr>
    <td>Beta</td>
    <td id="betaValue"></td>
  </tr>
  <tr>
    <td>Charlie</td>
    <td id="charlieValue"></td>
  </tr>
  <!-- Add more rows as needed -->
</table>

</body>
</html>

