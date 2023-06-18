<!DOCTYPE html>
<html>
<head>
  <title>Advanced Table</title>
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 8px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }

    th {
      background-color: #f2f2f2;
    }

    tr:hover {
      background-color: #f5f5f5;
    }

    .highlight {
      background-color: yellow;
    }
  </style>
</head>
<body>
  <table>
    <thead>
      <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>John Doe</td>
        <td>25</td>
        <td>john@example.com</td>
      </tr>
      <tr>
        <td>Jane Smith</td>
        <td>30</td>
        <td>jane@example.com</td>
      </tr>
      <tr class="highlight">
        <td>Mike Johnson</td>
        <td>35</td>
        <td>mike@example.com</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
  # Html-Css-table
