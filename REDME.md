<!DOCTYPE html>
<html>
<head>
  <title>General Store Inventory</title>
</head>
<body>
  <h1>General Store Inventory</h1>
  
  <table>
    <tr>
      <th>Item</th>
      <th>Price</th>
      <th>Quantity</th>
    </tr>
    <tr>
      <td>Item 1</td>
      <td>$10.99</td>
      <td>25</td>
    </tr>
    <tr>
      <td>Item 2</td>
      <td>$5.99</td>
      <td>10</td>
    </tr>
    <tr>
      <td>Item 3</td>
      <td>$7.99</td>
      <td>15</td>
    </tr>
    <!-- Add more rows for additional items -->
  </table>
</body>
</html>
In this example, we have a simple table with three columns: Item, Price, and Quantity. You can add more rows for additional items by copying and pasting the <tr> block and modifying the content accordingly.

Feel free to customize the code based on your specific requirements, such as adding more details or styling the table with CSS.





User
create a generale store inventory HTML &CSS code

ChatGPT
Certainly! Here's an example of a general store inventory HTML code with some basic CSS styling:

html
Copy code
<!DOCTYPE html>
<html>
<head>
  <title>General Store Inventory</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }

    h1 {
      text-align: center;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 8px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }

    tr:nth-child(even) {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>
  <h1>General Store Inventory</h1>
  
  <table>
    <tr>
      <th>Item</th>
      <th>Price</th>
      <th>Quantity</th>
    </tr>
    <tr>
      <td>Item 1</td>
      <td>$10.99</td>
      <td>25</td>
    </tr>
    <tr>
      <td>Item 2</td>
      <td>$5.99</td>
      <td>10</td>
    </tr>
    <tr>
      <td>Item 3</td>
      <td>$7.99</td>
      <td>15</td>
    </tr>
    <!-- Add more rows for additional items -->
  </table>
</body>
</html>
