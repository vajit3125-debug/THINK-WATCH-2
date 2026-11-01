# THINK-WATCH-2
THINK watch
<!DOCTYPE html>
<html>
<head>
<title>THINK WATCH</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: #f2f2f2;
}

header {
    background: black;
    color: white;
    text-align: center;
    padding: 25px;
}

h2 {
    text-align: center;
}

.container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
}

.watch {
    background: white;
    width: 230px;
    padding: 15px;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 0 10px gray;
}

.watch img {
    width: 100%;
    height: 180px;
    object-fit: contain;
}

button {
    background: black;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

footer {
    background: black;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>
</head>

<body>

<header>
<h1>THINK WATCH</h1>
<p>Premium Watch Collection</p>
</header>

<h2>Our Watches</h2>

<div class="container">

<div class="watch">
<img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=500">
<h3>Classic Watch</h3>
<p>Price: ₹1499</p>
<button onclick="alert('Thank You!')">Buy Now</button>
</div>

<div class="watch">
<img src="https://images.unsplash.com/photo-1524805444758-089113d48a6d?w=500">
<h3>Luxury Watch</h3>
<p>Price: ₹2499</p>
<button onclick="alert('Thank You!')">Buy Now</button>
</div>

<div class="watch">
<img src="https://images.unsplash.com/photo-1508685096489-7aacd43bd3b1?w=500">
<h3>Smart Watch</h3>
<p>Price: ₹3499</p>
<button onclick="alert('Thank You!')">Buy Now</button>
</div>

</div>

<footer>
<p>Copyright 2026 THINK WATCH</p>
<p>Thank You For Visiting!</p>
</footer>

</body>
</html>
