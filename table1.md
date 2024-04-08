<!DOCTYPE html>
<html>
<head>
  <title>table 1</title>
</head>
<body>
<h1>Table 1</h1>
<table>

<tr>
<th>Index#</th>
<th>Value</th>
</tr>

<tr>
<td>A1</td>
<td>41</td>
</tr>

<tr>
<td>A2</td>
<td>18</td>
</tr>

<tr>
<td>A3</td>
<td>21</td>
</tr>

<tr>
<td>A4</td>
<td>63</td>
</tr><tr>
<td>A5</td>
<td>2</td>
</tr>

<tr>
<td>A6</td>
<td>53</td>
</tr>

<tr>
<td>A7</td>
<td>5</td>
</tr>

<tr>
<td>A8</td>
<td>57</td>
</tr>

<tr>
<td>A9</td>
<td>60</td>
</tr>

<tr>
<td>A10</td>
<td>93</td>
</tr>

<tr>
<td>A11</td>
<td>28</td>
</tr>

<tr>
<td>A12</td>
<td>3</td>
</tr>

<tr>
<td>A13</td>
<td>90</td>
</tr>

<tr>
<td>A14</td>
<td>39</td>
</tr>

<tr>
<td>A15</td>
<td>80</td>
</tr>

<tr>
<td>A16</td>
<td>88</td>
</tr>

<tr>
<td>A17</td>
<td>49</td>
</tr>

<tr>
<td>A18</td>
<td>60</td>
</tr>

<tr>
<td>A19</td>
<td>26</td>
</tr>

<tr>
<td>A20</td>
<td>28</td>
</tr>

</body>
</table>
</html>

<!DOCTYPE html>
<html>
<head>
  <title>Table 2</title>
  <script>
    function calculateValues() {
      // Get the values from Table 1
      var values = {
        A5: 2,
        A20: 28,
        A15: 80,
        A7: 5,
        A13: 90,
        A12: 3
        // Add more values from Table 1 as needed
      };

      // Calculate the values for Table 2
      var alphaValue = values.A5 + values.A20;
      var betaValue = values.A15 / values.A7;
      var charlieValue = values.A13 * values.A12;

      // Display the calculated values in Table 2
      document.getElementById("alphaValue").innerText = alphaValue;
      document.getElementById("betaValue").innerText = betaValue;
      document.getElementById("charlieValue").innerText = charlieValue;
    }
  </script>
</head>
<body onload="calculateValues()">

<h1>Table 2</h1>

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
</table>

</body>
</html>

