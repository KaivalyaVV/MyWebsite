<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Green Residency Society</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #f4f6f8;
}

/* HEADER */
header {
    background: #2c3e50;
    color: white;
    padding: 15px;
    text-align: center;
}

/* NAVBAR */
nav {
    background: #34495e;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

nav a {
    color: white;
    padding: 12px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    background: #2c3e50;
}

/* HERO SECTION */
.hero {
    background: url('https://images.unsplash.com/photo-1560448204-e02f11c3d0e2') no-repeat center/cover;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 28px;
    text-align: center;
    padding: 10px;
}

/* CONTAINER */
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    padding: 20px;
}

/* CARDS */
.card {
    background: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* BUTTON */
button {
    background: #27ae60;
    color: white;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background: #219150;
}

/* FOOTER */
footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 10px;
}

/* 📱 MOBILE RESPONSIVE */
@media (max-width: 768px) {

    .container {
        grid-template-columns: 1fr;
    }

    .hero {
        height: 200px;
        font-size: 20px;
    }

    nav {
        flex-direction: column;
        align-items: center;
    }

    nav a {
        width: 100%;
        text-align: center;
        border-top: 1px solid #555;
    }
}
</style>
</head>

<body>

<header>
    <h1>Green Residency Society</h1>
    <p>Mumbai, Maharashtra</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Members</a>
    <a href="#">Notices</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    Welcome to Our Society
</div>

<div class="container">

    <div class="card">
        <h2>About Society</h2>
        <p>
            Green Residency is a modern housing society with a safe and friendly environment.
        </p>
    </div>

    <div class="card">
        <h2>Latest Notices</h2>
        <ul>
            <li>Water maintenance Sunday</li>
            <li>Meeting on 25th</li>
            <li>Parking update</li>
        </ul>
    </div>

    <div class="card">
        <h2>Contact</h2>
        <p>Email: society@gmail.com</p>
        <p>Phone: +91 9876543210</p>
        <button onclick="alert('Complaint feature coming soon')">
            Raise Complaint
        </button>
    </div>

</div>

<footer>
    <p>© 2026 Green Residency Society</p>
</footer>

</body>
</html>
