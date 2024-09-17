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
                <th>Name of product</th>
                <th class="price">Price</th>
                <th class="availability">Availability</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Fabs</td>
                <td class="price">$35</td>
                <td class="availability">In Stock</td>
            </tr>
            <tr>
                <td>Dryer</td>
                <td class="price">$500</td>
                <td class="availability">Out of Stock</td>
            </tr>
            <tr>
                <td>Microwave</td>
                <td class="price">$80</td>
                <td class="availability">In Stock</td>
            </tr>
            <tr>
                <td>Television</td>
                <td class="price">$400</td>
                <td class="availability">In Stock</td>
            </tr>
            <tr>
                <td>Air conditioning</td>
                <td class="price">$250</td>
                <td class="availability">Limited Stock</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
