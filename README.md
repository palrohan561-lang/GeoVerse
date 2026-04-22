<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GeoVerse</title>

<style>

body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f4f9f9;
    color:#333;
}

header{
    background:linear-gradient(to right,#0b5d4f,#1565c0);
    color:white;
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:60px;
    margin-bottom:10px;
}

header p{
    font-size:22px;
}

nav{
    background:#083d34;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 20px;
    font-weight:bold;
}

section{
    padding:60px 20px;
    max-width:1100px;
    margin:auto;
}

.card-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

.card h3{
    color:#1565c0;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    border-radius:15px;
    height:250px;
    object-fit:cover;
}

.contact{
    background:linear-gradient(to right,#1565c0,#0b5d4f);
    color:white;
    text-align:center;
    border-radius:20px;
    padding:50px;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}

button{
    padding:12px 25px;
    border:none;
    border-radius:10px;
    background:white;
    color:#1565c0;
    font-weight:bold;
    cursor:pointer;
}

</style>

</head>
<body>

<header>
    <h1>GeoVerse</h1>
    <p>Exploring Geography, GIS & Earth Science</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#topics">Topics</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About GeoVerse</h2>
    <p>
        GeoVerse is a geography-focused educational website dedicated to GIS,
        Remote Sensing, Cartography, LiDAR analysis, and Earth science learning.
    </p>
</section>

<section id="topics">
    <h2>Core Topics</h2>

    <div class="card-container">

        <div class="card">
            <h3>GIS & Mapping</h3>
            <p>Spatial analysis and digital mapping techniques.</p>
        </div>

        <div class="card">
            <h3>Remote Sensing</h3>
            <p>Satellite imagery and earth observation systems.</p>
        </div>

        <div class="card">
            <h3>LiDAR & DEM</h3>
            <p>Terrain analysis, contour creation and elevation models.</p>
        </div>

        <div class="card">
            <h3>Cartography</h3>
            <p>Map design and thematic mapping visualization.</p>
        </div>

    </div>
</section>

<section id="gallery">

    <h2>Geography Gallery</h2>

    <div class="gallery">

        <img src="https://images.unsplash.com/photo-1524661135-423995f22d0b?q=80&w=1200&auto=format&fit=crop">

        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1200&auto=format&fit=crop">

        <img src="https://images.unsplash.com/photo-1469474968028-56623f02e42e?q=80&w=1200&auto=format&fit=crop">

    </div>

</section>

<section id="contact">

    <div class="contact">
        <h2>Contact GeoVerse</h2>
        <p>Email: yourmail@example.com</p>

        <button>Join GeoVerse</button>
    </div>

</section>

<footer>
    <h3>GeoVerse</h3>
    <p>Exploring Geography Through Maps & Science</p>
    <p>© 2026 GeoVerse</p>
</footer>

</body>
</html>
