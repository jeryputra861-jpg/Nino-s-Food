# Nino-s-Food
bergerak dalam bidang Makanan
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ninos Food - Menu Makanan Lezat</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80'); /* Gambar latar belakang makanan dari Unsplash */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: #333;
        }
        header {
            background-color: rgba (255, 165, 0, 0.9); /* Orange dengan transparansi */
            color: white;
            text-align: center;
            padding: 20 px;
            font-size: 2 em;
        }
        nav {
            background-color: rgba (255, 0, 0, 0.8); /* Red dengan transparansi */
            padding: 10 px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15 px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #FFD700; /* Golden hover */
        }
        .container {
            max-width: 1200 px;
            margin: 20 px auto;
            padding: 20 px;
            background-color: rgba (255, 255, 255, 0.9); /* Putih transparan untuk konten */
            border-radius: 10 px;
        }
        .menu-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .menu-item {
            background-color: rgba (0, 128, 0, 0.8); /* Green dengan transparansi */
            color: white;
            width: 45 %;
            margin: 10 px;
            padding: 20 px;
            border-radius: 10 px;
            text-align: center;
            box-shadow: 0 4 px 8 px rgba (0,0,0,0.2);
        }
        .menu-item img {
            width: 100 %;
            height: 200 px;
            object-fit: cover;
            border-radius: 10 px;
        }
        .menu-item h3 {
            margin-top: 10 px;
        }
        footer {
            background-color: rgba (255, 165, 0, 0.9);
            color: white;
            text-align: center;
            padding: 10 px;
            position: fixed;
            width: 100 %;
            bottom: 0;
        }
       @media (max-width: 768 px) {
            .menu-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Ninos Food</h1>
        <p>Makanan Lezat untuk Semua Selera</p>
    </header>
    <nav>
        <a href="#sapi">Olahan Daging Sapi</a>
        <a href="#ayam">Olahan Daging Ayam</a>
        <a href="#babi">Olahan Daging Babi</a>
        <a href="#kambing">Olahan Daging Kambing</a>
    </nav>
    <div class="container">
        <h2>Menu Kami</h2>
        <div class="menu-section">
            <div class="menu-item" id="sapi">
                <img src="https://images.unsplash.com/photo-1546833999-b9f581a1996d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Olahan Daging Sapi">
                <h3>Olahan Daging Sapi</h3>
                <p>Nikmati steak juicy atau burger daging sapi premium yang dimasak sempurna.</p>
            </div>
            <div class="menu-item" id="ayam">
                <img src="https://images.unsplash.com/photo-1562967914-608f82629710?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Olahan Daging Ayam">
                <h3>Olahan Daging Ayam</h3>
                <p>Ayam goreng renyah atau ayam panggang dengan bumbu spesial.</p>
            </div>
            <div class="menu-item" id="babi">
                <img src="https://images.unsplash.com/photo-1551782450-17144efb5723?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Olahan Daging Babi">
                <h3>Olahan Daging Babi</h3>
                <p>Pork chops lembut atau bacon crispy yang menggugah selera.</p>
            </div>
            <div class="menu-item" id="kambing">
                <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80" alt="Olahan Daging Kambing">
                <h3>Olahan Daging Kambing</h3>
                <p>Kebab kambing atau curry kambing yang kaya rasa dan aroma.</p>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2023 Ninos Food. Semua Hak Dilindungi.</p>
    </footer>
</body>
</html>
