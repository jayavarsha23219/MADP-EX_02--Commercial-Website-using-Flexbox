# MADP-EX_02--Commercial-Website-using-Flexbox
## Date: 09.05.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>ShopEase</title>
    <link rel="stylesheet" href="script1.css">
</head>
<body>
    <header>
        <h1>ShopEase</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="products.html">Products</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section class="banner">
        <h2>Welcome to ShopEase!</h2>
        <a href="products.html" class="btn">Shop Now</a>
    </section>

    <footer>© <span id="year"></span> ShopEase</footer>
    <script src="style.js"></script>
</body>
</html>
```
products.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Products</title>
    <link rel="stylesheet" href="script1.css">
</head>
<body>
    <header>
        <h1>Our Products</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="products.html">Products</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section class="products">
        <div class="product">
            <img src="pr1.png" alt="Product 1">
            <h3>Product 1 - $25</h3>
            <button onclick="addToCart()">Add to Cart</button>
        </div>
        <div class="product">
            <img src="pr2.png" alt="Product 2">
            <h3>Product 2 - $40</h3>
            <button onclick="addToCart()">Add to Cart</button>
        </div>
    </section>

    <footer>© <span id="year"></span> ShopEase</footer>
    <script src="style.js"></script>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Contact</title>
    <link rel="stylesheet" href="script1.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="products.html">Products</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section class="contact">
        <form>
            <p>Email: varsha@gmail.com</p>
            <p>Phone: 8134324523</p>
            <p>Address: 24, Rich Street, Parry's Corner, Chennai</p>
        </form>
    </section>
    <footer>© <span id="year"></span> ShopEase</footer>
    <script src="style.js"></script>
</body>
</html>
```
script.css
```
body { 
    font-family: Arial, sans-serif;
    text-align: center; 
    margin: 0; 
    background: #f5f5f5; }

header { 
    background: #d960bb; 
    color: white; 
    padding: 15px; }

nav a { 
    color: white; 
    margin: 0 15px; 
    text-decoration: none; }

.banner { 
    padding: 50px; 
    background: #000000; 
    color: white; }

.btn { background: white;
     padding: 10px 20px; 
     text-decoration: none; }

.products { 
    display: flex; 
    justify-content: center; 
    gap: 20px; 
    padding: 20px; }

.product { 
    background: white; 
    padding: 15px; 
    box-shadow: 0 0 10px rgba(0,0,0,0.1); }

.product img { 
    width: 150px; }

.contact {
    background: white;
    padding: 30px;
    max-width: 600px;
    margin: 40px auto;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);}
      
.contact p {
    font-size: 16px;
    margin: 10px 0;}

footer { 
    background: #333; 
    color: white; 
    padding: 10px; 
    position: fixed; 
    bottom: 0; 
    width: 100%; }
```

## OUTPUT
![Screenshot 2025-05-02 113728](https://github.com/user-attachments/assets/4e1fd2a8-6f77-400d-a890-22089ec66cfc)
![Screenshot 2025-05-02 113743](https://github.com/user-attachments/assets/16740384-1266-4458-9333-6a6f0b622862)
![Screenshot 2025-05-02 113754](https://github.com/user-attachments/assets/c587c1d0-8cb2-453f-94ed-0744f0f36681)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
