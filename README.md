<!DOCTYPE html>
<html>
<head>
<title>Black Background Table</title>
<style>
  body {
    background-color: black;
    color: white; /* To make text visible on a black background */
    font-family: Arial, sans-serif;
  }
  table {
    width: 80%; /* Adjust table width as needed */
    border-collapse: collapse; /* Collapses borders into a single border */
    margin: 20px auto; /* Centers the table and adds some top/bottom margin */
    background-color: #333; /* Slightly lighter background for the table */
  }
  th, td {
    border: 1px solid white; /* White borders for cells */
    padding: 10px;
    text-align: left;
  }
  th {
    background-color: #555; /* Slightly different background for table headers */
  }
</style>
</head>
<body>

<h2>My Table</h2>

<table>
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Row 1, Cell 1</td>
      <td>Row 1, Cell 2</td>
    </tr>
    <tr>
      <td>Row 2, Cell 1</td>
      <td>Row 2, Cell 2</td>
    </tr>
    <tr>
      <td>Row 3, Cell 1</td>
      <td>Row 3, Cell 2</td>
    </tr>
    <tr>
      <td>Row 4, Cell 1</td>
      <td>Row 4, Cell 2</td>
    </tr>
  </tbody>
</table>

</body>
</html>
