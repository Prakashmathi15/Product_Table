# Product Table
## Date:8-07-2-25
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
        <title>Product Table</title>
        <link rel='stylesheet' href="styles.css">
    </head>
<body>
    <table cellspacing="5" cellpadding="5" border="5">
        <caption>Product Information</caption>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>50000</td>
                <td>High performance</td>
            </tr>
            <tr>
                <td>Mouse</td>
                <td>500</td>
                <td>Smooth tracking</td>
            </tr>
            <tr>
                <td>Mobile</td>
                <td>60000</td>
                <td>High resolution display</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
## CSS
```css
body{
    background-color: rgb(8, 247, 195);
    font-family: 'Times New Roman', Times, serif;
}
table{
    margin: auto;
    border: 2px;
    border-collapse: collapse;
    width: 50%;
    
}
th{
    background-color: #f31f50;
    color: rgb(246, 241, 241);
    padding: 10px;
    text-align: center;
}
td{
    border: 1px solid #000000;
    padding: 10px;
}
tr:hover{
    background-color: #ee4b10;
}
tr:nth-child(even) {
    background-color: #f8f803;
}
caption{
    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 30px;
    font-weight: bold;
}
```

## Output:
<img width="953" alt="image" src="https://github.com/user-attachments/assets/3667d709-4101-4401-9d0c-103b9e69eeae" />



## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
