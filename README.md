# Cat-Under-Moonlight
Under the moonlight, a place to relax with cats
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Cat Under the Moonlight</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: black;
    color: white;
    text-align: center;
}

/* 네비 */
nav {
    background: #111;
    padding: 15px;
    position: sticky;
    top: 0;
}
nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

/* 공통 섹션 */
section {
    padding: 60px 20px;
}

/* 갤러리 */
.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
}
.gallery img {
    width: 250px;
    height: 250px;
    object-fit: cover;
    border-radius: 15px;
}

/* 메뉴 카드 */
.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}
.card {
    background: #111;
    border-radius: 15px;
    width: 220px;
    overflow: hidden;
}
.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}
.card h3 {
    margin: 10px 0 5px;
}
.card p {
    margin-bottom: 15px;
    color: #ccc;
}

/* 지도 */
.map img {
    width: 80%;
    max-width: 600px;
    border-radius: 15px;
}
</style>
</head>

<body>

<!-- 네비 -->
<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#map">Map</a>
</nav>

<!-- 홈 -->
<section id="home">
    <h1>Cat Under the Moonlight</h1>
    <p>Under the moonlight, a place to relax with cats</p>

    <div class="gallery">
        <img src="cat1.jpg">
        <img src="cat2.jpg">
        <img src="cat3.jpg">
        <img src="cat4.jpg">
    </div>
</section>

<!-- 메뉴 -->
<section id="menu">
    <h1>Menu</h1>

    <div class="menu">
        <div class="card">
            <img src="affogato.jpg">
            <h3>🍨 Affogato</h3>
            <p>$5</p>
        </div>

        <div class="card">
            <img src="maple_latte.jpg">
            <h3>🍁 Maple Latte</h3>
            <p>$4.5</p>
        </div>

        <div class="card">
            <img src="brownie.jpg">
            <h3>🍫 Brownie</h3>
            <p>$4</p>
        </div>

        <div class="card">
            <img src="vanilla_latte.jpg">
            <h3>☕ Double Vanilla Latte</h3>
            <p>$5</p>
        </div>
    </div>
</section>

<!-- 지도 -->
<section id="map">
    <h1>Location</h1>

    <div class="map">
        <img src="map.jpg">
    </div>

    <p style="color:#aaa; margin-top:10px;">
        📍 Cat Under the Moonlight
    </p>
</section>

</body>
</html>
