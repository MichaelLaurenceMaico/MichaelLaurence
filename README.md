<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Table</title>
    <style>
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
            color: #333;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        .price {
            text-align: right;
        }
        .availability {
            text-align: center;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Product Name</th>
                <th class="price">Price</th>
                <th class="availability">Availability</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Lexar</td>
                <td class="price">P3500</td>
                <td class="availability">In Stock</td>
            </tr>
            <tr>
                <td>Laptop</td>
                <td class="price">$1299</td>
                <td class="availability">Out of Stock</td>
            </tr>
            <tr>
                <td>Wireless Earbuds</td>
                <td class="price">$199</td>
                <td class="availability">In Stock</td>
            </tr>
            <tr>
                <td>Smartwatch</td>
                <td class="price">$249</td>
                <td class="availability">In Stock</td>
            </tr>
            <tr>
                <td>Bluetooth Speaker</td>
                <td class="price">$89</td>
                <td class="availability">Limited Stock</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
