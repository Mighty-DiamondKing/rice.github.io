<!DOCTYPE html>
<html>
<head>
  <style>
    .money {
      color: green;
      font-weight: bold;
    }

    table {
      border-collapse: collapse;
    }

    td, th {
      border: 1px solid black;
      padding: 8px;
    }
  </style>
</head>

<body>

<h2>Simple Farming Table</h2>

<table>

  <tr>
    <th>Item</th>
    <th>Amount</th>
  </tr>

  <tr>
    <td>Seed Cost</td>
    <td>₹2000</td>
  </tr>

  <tr>
    <td>Profit (normal)</td>
    <td>₹5000</td>
  </tr>

  <tr>
    <td>Profit (highlighted)</td>
    <td class="money">₹5000</td>
  </tr>

</table>

</body>
</html>
