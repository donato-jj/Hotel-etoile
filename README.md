# Hotel-etoile
Hotel etoile bienvenidos 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Etoile | Mar del Plata</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- ===== HEADER ===== -->
    <header class="header">
        <div class="container header-content">
            <h1 class="logo">Hotel Etoile</h1>
            <nav class="nav">
                <a href="#inicio">Inicio</a>
                <a href="#hotel">El Hotel</a>
                <a href="#ubicacion">Ubicación</a>
                <a href="#contacto">Contacto</a>
            </nav>
        </div>
    </header>

    <!-- ===== HERO ===== -->
    <section class="hero" id="inicio">
        <div class="hero-overlay">
            <h2>Hotel Etoile</h2>
            <p>Confort y elegancia en Mar del Plata</p>
        </div>
    </section>

    <!-- ===== EL HOTEL ===== -->
    <section class="section" id="hotel">
        <div class="container hotel-section">
            <img src="recepcion.jpg" alt="Recepción Hotel Etoile">
            <div class="hotel-text">
                <h3>El Hotel</h3>
                <p>
                    Hotel Etoile ofrece un ambiente cálido y elegante, ideal para quienes buscan
                    comodidad, tranquilidad y una atención personalizada. Ubicado estratégicamente
                    en Mar del Plata, es una excelente opción tanto para viajes de descanso como de trabajo.
                </p>
                <p>
                    Nuestro compromiso es brindar una experiencia confortable, con espacios cuidados
                    y un servicio atento que haga sentir a cada huésped como en casa.
                </p>
            </div>
        </div>
    </section>

    <!-- ===== UBICACIÓN ===== -->
    <section class="section location" id="ubicacion">
        <div class="container">
            <h3>Ubicación</h3>
            <p>📍 Santiago del Estero 1869</p>
            <p>Mar del Plata, Argentina</p>
        </div>
    </section>

    <!-- ===== CONTACTO ===== -->
    <section class="section contact" id="contacto">
        <div class="container">
            <h3>Contacto</h3>
            <p class="phone">📞 0223 493-4968</p>
            <a href="tel:02234934968" class="call-button">Llamar ahora</a>
        </div>
    </section>

    <!-- ===== FOOTER ===== -->
    <footer class="footer">
        <p><strong>Hotel Etoile</strong></p>
        <p>Santiago del Estero 1869</p>
        <p>Tel: 0223 493-4968</p>
        <p>Mar del Plata – Argentina</p>
    </footer>

</body>
</html>
/* ===== RESET ===== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* ===== GENERAL ===== */
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    color: #4a3b2a;
    background-color: #f7f3ee;
    line-height: 1.6;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 40px 20px;
}

/* ===== HEADER ===== */
.header {
    background-color: #efe6d8;
    border-bottom: 1px solid #d6c6ad;
}

.header-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 28px;
    color: #6b4e2e;
}

.nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #6b4e2e;
    font-weight: 500;
}

.nav a:hover {
    color: #a67c52;
}

/* ===== HERO ===== */
.hero {
    background-image: url('fachada.jpg');
    background-size: cover;
    background-position: center;
    height: 70vh;
    position: relative;
}

.hero-overlay {
    background-color: rgba(0,0,0,0.45);
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
}

.hero-overlay h2 {
    font-size: 42px;
    margin-bottom: 10px;
}

.hero-overlay p {
    font-size: 20px;
}

/* ===== SECTIONS ===== */
.section {
    background-color: #ffffff;
}

.hotel-section {
    display: flex;
    gap: 40px;
    align-items: center;
}

.hotel-section img {
    width: 50%;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.hotel-text h3 {
    font-size: 30px;
    margin-bottom: 15px;
    color: #6b4e2e;
}

/* ===== LOCATION ===== */
.location {
    background-color: #f3eadc;
    text-align: center;
}

.location h3 {
    font-size: 28px;
    margin-bottom: 10px;
}

/* ===== CONTACT ===== */
.contact {
    text-align: center;
}

.contact h3 {
    font-size: 28px;
    margin-bottom: 10px;
}

.phone {
    font-size: 22px;
    margin-bottom: 20px;
}

.call-button {
    display: inline-block;
    padding: 12px 25px;
    background-color: #a67c52;
    color: #fff;
    text-decoration: none;
    border-radius: 25px;
    font-weight: bold;
}

.call-button:hover {
    background-color: #8b623d;
}

/* ===== FOOTER ===== */
.footer {
    background-color: #6b4e2e;
    color: #fff;
    text-align: center;
    padding: 25px 10px;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 768px) {
    .hotel-section {
        flex-direction: column;
    }

    .hotel-section img {
        width: 100%;
    }

    .nav {
        display: none;
    }
}
