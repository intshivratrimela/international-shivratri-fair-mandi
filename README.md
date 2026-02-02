international-shivratri-fair-mandi/
│
├── index.html
├── style.css
└── images/
    └── hero.jpg   (add later)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>International Shivratri Fair Mandi</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header / Hero Section -->
    <header class="hero">
        <div class="overlay">
            <h1>International Shivratri Fair Mandi</h1>
            <p>A Grand Celebration of Faith, Culture & Tradition</p>
            <a href="#about" class="btn">Explore the Fair</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About the Fair</h2>
        <p>
            The <strong>International Shivratri Fair Mandi</strong> is celebrated every year
            during Maha Shivratri in Mandi, Himachal Pradesh. Known as the
            <em>Chhoti Kashi of Himachal Pradesh</em>, Mandi becomes a spiritual center
            where hundreds of local deities gather to pay homage to Lord Shiva.
        </p>
    </section>

    <!-- Hindi Section -->
    <section class="section light">
        <h2>अंतरराष्ट्रीय शिवरात्रि मेला, मंडी</h2>
        <p>
            अंतरराष्ट्रीय शिवरात्रि मेला मंडी हिमाचल प्रदेश का एक प्रसिद्ध धार्मिक
            एवं सांस्कृतिक उत्सव है। इस अवसर पर सैकड़ों देवी-देवता भगवान शिव के
            दर्शन हेतु मंडी पहुंचते हैं।
        </p>
    </section>

    <!-- Events Section -->
    <section class="section">
        <h2>Major Attractions</h2>
        <ul class="list">
            <li>Devta Milan</li>
            <li>Jaleb Procession</li>
            <li>Maha Shivratri Puja</li>
            <li>Cultural Nights</li>
            <li>Exhibitions & Folk Performances</li>
        </ul>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 International Shivratri Fair Mandi</p>
        <p>Mandi, Himachal Pradesh, India</p>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

/* Hero Section */
.hero {
    height: 100vh;
    background: url("images/hero.jpg") no-repeat center center/cover;
    position: relative;
}

.overlay {
    background: rgba(0, 0, 0, 0.6);
    height: 100%;
    color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
}

.overlay h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.overlay p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

.btn {
    background: #ff9933;
    color: #fff;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.btn:hover {
    background: #e68a00;
}

/* Sections */
.section {
    padding: 60px 20px;
    max-width: 900px;
    margin: auto;
}

.section h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #cc6600;
}

.section p {
    text-align: center;
    font-size: 1.05rem;
}

.light {
    background: #f9f9f9;
}

/* List */
.list {
    list-style: none;
    text-align: center;
}

.list li {
    padding: 8px 0;
    font-size: 1.1rem;
}

/* Footer */
footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px;
}

