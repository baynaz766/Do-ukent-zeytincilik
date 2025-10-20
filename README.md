<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doğukent Zeytincilik</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4caf50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        h1 { margin: 0; }
        .container {
            width: 90%;
            max-width: 900px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
        }
        .main-product {
            text-align: center;
            margin-bottom: 30px;
        }
        .main-product h2 {
            color: #d35400;
            font-size: 28px;
            margin-bottom: 10px;
        }
        .main-product p {
            font-size: 22px;
            font-weight: bold;
        }
        .product-list h3 {
            border-bottom: 2px solid #4caf50;
            padding-bottom: 5px;
        }
        .product-item {
            display: flex;
            align-items: center;
            border-bottom: 1px solid #ddd;
            padding: 10px 0;
        }
        .product-item img {
            width: 70px;
            height: 70px;
            object-fit: cover;
            border-radius: 8px;
            margin-right: 15px;
        }
        .product-item span {
            font-size: 16px;
        }
        .whatsapp-btn {
            display: block;
            width: 100%;
            text-align: center;
            background-color: #25D366;
            color: white;
            padding: 15px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 8px;
            margin-top: 20px;
        }
        .whatsapp-btn:hover {
            background-color: #1ebe5d;
        }
    </style>
</head>
<body>

<header>
    <h1>Doğukent Zeytincilik</h1>
</header>

<div class="container">
    <div class="main-product">
        <h2>El Kırması Yeşil Zeytin</h2>
        <p>3 kg - 500 TL | 6 kg - 1.000 TL</p>
        <img src="img/products/el-kirmasi.jpg" alt="El Kırması Yeşil Zeytin" style="width:200px; margin-top:10px; border-radius:10px;">
    </div>

    <div class="product-list">
        <h3>Köy Ürünleri</h3>

        <div class="product-item">
            <img src="img/products/tereyag.jpg" alt="Tereyağ">
            <span>Tereyağ 1 kg - 350 TL</span>
        </div>

        <div class="product-item">
            <img src="img/products/kaymak.jpg" alt="Kaymak">
            <span>Kaymak 1 kg - 300 TL</span>
        </div>

        <div class="product-item">
            <img src="img/products/peynir.jpg" alt="Peynir">
            <span>Peynir 1 kg - 250 TL</span>
        </div>

        <div class="product-item">
            <img src="img/products/susamli-pestil.jpg" alt="Susamlı Pestil">
            <span>Susamlı Pestil 1 kg - 450 TL</span>
        </div>

        <!-- Diğer ürünleri aynı şekilde ekleyebilirsin -->
    </div>

    <a class="whatsapp-btn" href="https://wa.me/905532939315" target="_blank">WhatsApp ile İletişim</a>
</div>

</body>
</html>
