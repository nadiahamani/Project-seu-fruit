# Project-seu-fruit
<> index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">Seu-Fruit</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#">Pages</a></li>
                <li><a href="#">Login / Register</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <div class="left-column">
            <h1>Haii Let's Order!! With Special Price to order delicious sando</h1>
            <p>Setiap Fruit Sando kami dibuat dengan penuh cinta menggunakan bahan-bahan berkualitas tinggi untuk memastikan kesegaran dan kenikmatannya.</p>
            <button>Shop Now</button>
        </div>
    </main>
</body>
</html>

#styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: rgb(198, 185, 193);
}

header {
    background-color: #1b7c9f;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 50px;
    box-shadow: 0 2px 4px #403e611a;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 16px;
}

main {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
    background-color: hwb(119 24% 31%);
}

.left-column {
    max-width: 50%;
}

.left-column h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

.left-column p {
    font-size: 18px;
    margin-bottom: 20px;
}

.left-column button {
    background-color: hwb(77 10% 85%);
    color: hsl(183, 58%, 58%);
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

.left-column button:hover {
    background-color: hsl(73, 100%, 35%);
}

.right-column {
    max-width: 50%;
}

.right-column img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}
