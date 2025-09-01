<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GUDANG.TANDON - Distributor IPAL & Bioseptictank</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="hero-section">
        <div class="container">
            <img src="images/logo_bioss.png" alt="Logo Bioss" class="hero-logo">
            <h1 class="hero-title">DISTRIBUTOR IPAL-BIOSEPTICTANK-STP-WWTP</h1>
            <p class="hero-contact">WHATSAPP <a href="https://wa.me/62895344661346">0895-3446-61346</a></p>
            <a href="https://bit.ly/bioseptictank.id" class="cta-button">SHOP NOW</a>
        </div>
    </header>

    <main>
        <section class="services-section">
            <div class="container">
                <h2 class="section-title">SUPPLIER IPAL, TANDON AIR, BIOSEPTICTANK</h2>
                <div class="services-content">
                    <img src="images/iklan_bioss.jpg" alt="Layanan Bioss" class="section-image">
                    <div class="services-list">
                        <h3>Melayani :</h3>
                        <ul>
                            <li>Pembuatan IPAL-STP-WWTP</li>
                            <li>Perbaikan septitank-STP-WWTP-IPAL</li>
                            <li>Instalasi pengolahan air limbah</li>
                            <li>TANDON AIR & BIOSEPTICTANK</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section class="consultation-section">
            <div class="container">
                <h2 class="section-title">KONTRAKTOR IPAL BIOSS</h2>
                <div class="consultation-content">
                    <img src="images/kontraktor_bioss.jpg" alt="Proyek Bioss" class="section-image">
                    <div class="consultation-details">
                        <h3>Jasa Pembuatan / Konsultan</h3>
                        <ul>
                            <li>IPAL-STP-WWTP</li>
                            <li>Produsen IPAL Klinik/Medis-IPAL Domestik-Ipal Komunal</li>
                            <li>Bioseptictank, Watertank, DLL</li>
                        </ul>
                        <p class="consultation-contact">Pemesanan & Konsultasi <br> WA <a href="https://wa.me/62895344661346">0895-3446-61346</a></p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 GUDANG.TANDON. Hak Cipta Dilindungi.</p>
        </div>
    </footer>

</body>
</html>
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f2f5;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

/* Header & Hero Section */
.hero-section {
    background-image: linear-gradient(to right, #1a2a6c, #b21f1f, #fdbb2d);
    color: white;
    text-align: center;
    padding: 60px 20px;
    position: relative;
    overflow: hidden;
}

.hero-logo {
    width: 120px;
    margin-bottom: 20px;
}

.hero-title {
    font-size: 2.5em;
    font-weight: 700;
    margin: 0;
}

.hero-contact {
    font-size: 1.2em;
    margin: 10px 0 20px;
}

.hero-contact a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}

.cta-button {
    background-color: #fff;
    color: #1a2a6c;
    padding: 12px 30px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: 700;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #eee;
}

/* Main Sections */
.services-section, .consultation-section {
    padding: 60px 0;
    text-align: center;
}

.section-title {
    font-size: 2em;
    font-weight: 600;
    color: #1a2a6c;
    margin-bottom: 40px;
    position: relative;
}

.section-title::after {
    content: '';
    display: block;
    width: 60px;
    height: 3px;
    background-color: #fdbb2d;
    margin: 10px auto 0;
}

.services-content, .consultation-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 30px;
}

.section-image {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}

.services-list, .consultation-details {
    text-align: left;
}

.services-list h3, .consultation-details h3 {
    color: #b21f1f;
    margin-top: 0;
}

.services-list ul, .consultation-details ul {
    list-style-type: '✅ ';
    padding-left: 20px;
}

.services-list li, .consultation-details li {
    margin-bottom: 10px;
}

.consultation-contact {
    font-size: 1.1em;
    font-weight: 600;
    margin-top: 20px;
}

.consultation-contact a {
    color: #1a2a6c;
    text-decoration: none;
}

/* Footer */
footer {
    background-color: #1a2a6c;
    color: white;
    text-align: center;
    padding: 20px 0;
}

/* Responsif */
@media (min-width: 768px) {
    .services-content, .consultation-content {
        flex-direction: row;
        justify-content: space-between;
    }

    .services-content .section-image {
        order: 1;
        width: 55%;
    }

    .services-list {
        order: 2;
        width: 40%;
    }

    .consultation-content .section-image {
        order: 2;
        width: 55%;
    }

    .consultation-details {
        order: 1;
        width: 40%;
    }
}


