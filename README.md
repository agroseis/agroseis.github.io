<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agroquímicos Seisa</title>
    <style>
        /* Estilos generales */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        /* Estilos para el encabezado */
        header {
            background-color: #6b8e23;
            color: #fff;
            padding: 20px 0;
            text-align: center;5
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            letter-spacing: 2px;
        }

        /* Estilos para la barra de navegación */
        nav {
            background-color: #3a5a2f;
            padding: 10px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #d9d9d9;
        }

        /* Estilos para las secciones */
        section {
            padding: 40px;
            margin: 20px auto;
            max-width: 1200px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease-in-out;
        }

        section:hover {
            transform: translateY(-5px);
        }

        h2 {
            color: #3a5a2f;
            margin-bottom: 20px;
            text-align: center;
        }

        p {
            margin-bottom: 20px;
        }

        /* Estilos para la galería de productos */
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }

        .product {
            border: 1px solid #ccc;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: box-shadow 0.3s ease;
            background-color: #fdfdfd;
            position: relative;
        }

        .product:hover {
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .product img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease;
        }

        .product img:hover {
            transform: scale(1.05);
        }

        .product-content {
            padding: 15px;
            text-align: center;
        }

        .product p {
            color: #666;
        }

        .price {
            font-size: 1.2em;
            color: #6b8e23;
            font-weight: bold;
            margin-top: 10px;
        }

        .buy-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #6b8e23;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s ease;
            text-decoration: none;
        }

        .buy-button:hover {
            background-color: #3a5a2f;
        }

        /* Estilos para el pie de página */
        footer {
            background-color: #3a5a2f;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        footer a {
            color: #fff;
            text-decoration: underline;
            margin-left: 5px;
        }

        footer a:hover {
            color: #d9d9d9;
        }

        /* Estilos para dispositivos móviles */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
            }

            nav ul li {
                margin: 5px 0;
            }

            .products {
                grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Agroquímicos Seisa</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#Semilla de girasol">semilla de girasol</a></li>
            <li><a href="#agroquimicos">Agroquímicos</a></li>
            <li><a href="#maceteria">Macetería</a></li>
            <li><a href="#flores">Flores Sintéticas</a></li>
            <li><a href="#charolas">Charolas</a></li>
            <li><a href="#bolsas">Bolsas</a></li>
            <li><a href="#floreros">Floreros</a></li>
            <li><a href="#abono">Abono</a></li>
            <li><a href="#compra">Compra en Línea</a></li>
            <li><a href="#ubicacion">Ubicación</a></li>
        </ul>
    </nav>
    <section id="Semilla de girasol">
        <h2>semilla de girasol</h2>
        <div class="products">
            <div class="product">
                <img src="ima/semilla.jpg" alt="semilla de girasol">
                <div class="product-content">
                    <p>semilla de girasol full sun - la semilla es de la variedad full sun, se vende por millar y/o por libra, manejamos 5 variedades de semillas, puede contactarnos para mas informacion.</p>
                    <p class="price">$4500</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div> <!-- Falta cerrar el div de producto -->
        </div> <!-- Falta cerrar el div de productos -->
    </section>
    <section id="agroquimicos">
        <h2>Agroquímicos</h2>
        <div class="products">
            <div class="product">
                <img src="ima/imagen1.jpg" alt="Captan">
                <div class="product-content">
                    <p>Captan - Útil para combatir las enfermedades de los cultivos.</p>
                    <p class="price">$190.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/imagen2.jpg" alt="Agromil Plus">
                <div class="product-content">
                    <p>Agromil Plus - Perfecto para el llenado de fruto.</p>
                    <p class="price">$200.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/imagen3.jpg" alt="Agromilv">
                <div class="product-content">
                    <p>Agromilv - Promueve el crecimiento de las plantas.</p>
                    <p class="price">$100.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/imagen4.jpg" alt="AgroplexCA">
                <div class="product-content">
                    <p>AgroplexCA - Nutrición integral para tus plantas.</p>
                    <p class="price">$170.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/imagen5.jpg" alt="AgrexABC">
                <div class="product-content">
                    <p>AgrexABC - Ajusta el pH del agua para el cultivo óptimo.</p>
                    <p class="price">$185.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/imagen6.jpg" alt="Querkus">
                <div class="product-content">
                    <p>Querkus - Enraizador y abono de alta eficacia.</p>
                    <p class="price">$220.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/imagen7.jpg" alt="AgrexRP">
                <div class="product-content">
                    <p>AgrexRP - Pegamento adherente para mejores resultados.</p>
                    <p class="price">$185.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="maceteria">
        <h2>Macetería para Vivero</h2>
        <div class="products">
            <div class="product">
                <img src="ima/mac1.jpg" alt="Maceta #3">
                <div class="product-content">
                    <p>Maceta #3 - Ideal para cualquier tipo de planta.</p>
                    <p class="price">$2.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/mac2.jpg" alt="Maceta #4">
                <div class="product-content">
                    <p>Maceta #4 - maceta numero 4.</p>
                    <p class="price">$2.20</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/mac3.jpg" alt="Maceta #5">
                <div class="product-content">
                    <p>Maceta #5 -  la maceta es del numero 5.</p>
                    <p class="price">$3.80</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/mac4.jpg" alt="Maceta #4 1/8">
                <div class="product-content">
                    <p>Maceta #4 1/8 - la maceta es del numero 4 1/8.</p>
                    <p class="price">$2.40</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/mac5.jpg" alt="Maceta #6">
                <div class="product-content">
                    <p>Maceta #6  - maceta de numero 6.</p>
                    <p class="price">$3.80</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/mac6.jpg" alt="Maceta #7">
                <div class="product-content">
                    <p>Maceta #7 - Maceta de numero 7.</p>
                    <p class="price">$5.50</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
            <div class="product">
                <img src="ima/mac7.jpg" alt="Maceta #8">
                <div class="product-content">
                    <p>Maceta #8 - Maceta del numero 8.</p>
                    <p class="price">$7.50</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="flores">
        <h2>Flores Sintéticas</h2>
        <div class="products">
            <div class="product">
                <img src="ima/flor.jpg" alt="Orquídeas Sintéticas">
                <div class="product-content">
                    <p>Orquídeas sintéticas y una gran variedad de flores para decorar cualquier ambiente.</p>
                    <p class="price">$140.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="charolas">
        <h2>Charolas para Germinar</h2>
        <div class="products">
            <div class="product">
                <img src="ima/charola.jpg" alt="Charolas para germinar">
                <div class="product-content">
                    <p>Perfectas para iniciar el crecimiento de tus plantas desde semillas. Disponibles en diferentes tamaños.</p>
                    <p class="price">$38.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="bolsas">
        <h2>Bolsas Negras para Plantas</h2>
        <div class="products">
            <div class="product">
                <img src="ima/bolsa.jpg" alt="Bolsas negras para plantas">
                <div class="product-content">
                    <p>Ofrecemos bolsas negras resistentes para el cultivo y traslado de tus plantas se vende por kilo de 17 x 17 y 27 x 27.</p>
                    <p class="price">$75.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="floreros">
        <h2>Floreros y Piedras de Colores</h2>
        <div class="products">
            <div class="product">
                <img src="ima/piedras.jpg"
                <div class="product-content">
                    <p>Disponemos de una variedad de floreros y piedras decorativas para darle un toque especial a tus arreglos florales.</p>
                    <p class="price">contactenos</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="abono">
        <h2>Abono para Orquídea</h2>
        <div class="products">
            <div class="product">
                <img src="ima/abono.jpg" alt="Abono para Orquídeas">
                <div class="product-content">
                    <p>Disponemos de una gran variedad de abonos para orquídeas que asegurarán el crecimiento saludable de tus plantas.</p>
                    <p class="price">$120.00</p>
                    <a href="#" class="buy-button">Comprar Ahora</a>
                </div>
            </div>
        </div>
    </section>

    <section id="compra">
        <h2>Compra en Línea</h2>
        <p>Compra todos nuestros productos en línea a través de nuestro <a href="#">sistema de pago en línea</a>.</p>
    </section>

    <section id="ubicacion">
        <h2>Ubicación</h2>
        <p>Nuestra tienda está ubicada en Tenancingo Degollado, Estado de México. Puedes visitarnos o contactarnos para más información al número: <strong>+7141006527</strong>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Agroquímicos y Productos de Jardinería. Todos los derechos reservados. Visítanos en: <a href="https://www.agroquimicosseisa.com">www.agroquimicosseisa.com</a></p>
    </footer>
</body>
</html>
