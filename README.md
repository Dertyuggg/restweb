# Ex.06 Restaurant Website
## Date:16/03/1026

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in Localhost.

## PROGRAM:
restarant.html
<html>
<head>
<title>Restaurant</title>

<style>
body{
    font-family: Arial;
    background-color:#f5f5f5;
    text-align:center;
    margin:0;
    display:flex;
    flex-direction:column;
    min-height:100vh;
}

h1{
    background-color:#8b0000;
    color:white;
    padding:15px;
    margin:0;
}

.menu{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:25px;
    padding:30px;
    flex:1;
}

.card{
    background:white;
    padding:15px;
    border-radius:10px;
    box-shadow:0 0 10px gray;
    width:200px;
}

.card img{
    width:100%;
    height:130px;
    border-radius:8px;
    object-fit:cover;
}

.price{
    color:green;
    font-weight:bold;
}

footer{
    background:#222;
    color:white;
    padding:15px;
}
</style>

</head>

<body>

<h1>Dhyaneshwar S Restaurant</h1>

<div class="menu">

<div class="card">
<img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38">
<h3>Pizza</h3>
<p class="price">₹250</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
<h3>Burger</h3>
<p class="price">₹150</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1555949258-eb67b1ef0ceb">
<h3>Pasta</h3>
<p class="price">₹200</p>
</div>

<div class="card">
<img src="https://www.vecteezy.com/free-photos/french-fries">
<h3>French Fries</h3>
<p class="price">₹120</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
<h3>Fried Chicken</h3>
<p class="price">₹300</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1563379091339-03246963d51a">
<h3>Sandwich</h3>
<p class="price">₹130</p>
</div>

</div>

<footer>
<p>© 2026 Dhyaneshwar S | Roll No: 212225040078</p>
</footer>

</body>
</html>

## OUTPUT:
![alt text](<exp6/myapp/screenshot (43).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
