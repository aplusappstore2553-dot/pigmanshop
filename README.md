<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PIGMAN Shop - Game Keys</title>

    <!-- ฟอนต์แนวเกม -->
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: "Kanit", sans-serif;
            background: #0a0a0a;
            color: #fff;
        }

        /* HERO SECTION */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.8)),
                        url('LOGO.jpeg') center/contain no-repeat;
            height: 330px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
            padding: 20px;
            border-bottom: 3px solid #00eaff;
        }

        .hero h1 {
            font-size: 3rem;
            font-weight: 600;
            color: #00eaff;
            text-shadow: 0 0 10px #00eaff;
        }

        .hero p {
            font-size: 1.3rem;
            opacity: 0.9;
        }

        h2 {
            text-align: center;
            margin-top: 40px;
            font-size: 2rem;
            color: #00c8ff;
            text-shadow: 0 0 8px #0088cc;
        }

        .products {
            max-width: 1100px;
            margin: 30px auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            padding: 10px;
        }

        .item {
            background: #111;
            padding: 20px;
            border-radius: 14px;
            border: 2px solid #00c8ff44;
            box-shadow: 0 0 12px #003b4a;
            transition: 0.2s;
        }

        .item:hover {
            transform: translateY(-6px);
            box-shadow: 0 0 15px #00eaff;
        }

        .item img {
            width: 100%;
            border-radius: 10px;
        }

        .item h3 {
            margin-top: 15px;
            font-size: 1.4rem;
            color: #00eaff;
        }

        .price {
            margin: 10px 0;
            font-size: 1.2rem;
            color: #00ff9d;
            font-weight: 600;
            text-shadow: 0 0 6px #00ff9d;
        }

        .item p {
            opacity: 0.85;
        }

        button {
            width: 100%;
            padding: 12px 0;
            margin-top: 10px;
            border: none;
            border-radius: 8px;
            font-size: 1.1rem;
            color: #fff;
            cursor: pointer;
            background: linear-gradient(45deg, #0066ff, #00eaff);
            box-shadow: 0 0 10px #009dff;
            transition: 0.2s;
        }

        button:hover {
            opacity: 0.85;
            transform: scale(1.03);
        }

        footer {
            margin-top: 40px;
            padding: 20px;
            text-align: center;
            color: #999;
            border-top: 1px solid #222;
        }
    </style>
</head>

<body>

<div class="hero">
    <h1>PIGMAN SHOP</h1>
    <p>ขายรหัสเกมแท้ ราคาถูก ปลอดภัย 100%</p>
</div>

<h2>🕹️ รายการสินค้า</h2>

<div class="products">

    <!-- Steam -->
    <div class="item">
        <img src="https://i.ibb.co/vY3N3fV/steam.jpg" alt="Steam Key">
        <h3>Steam Game Key</h3>
        <div class="price">เริ่มต้น 199 บาท</div>
        <p>รหัสเกม Steam ถูกที่สุด พร้อมใช้งานทันที</p>
        <button onclick="window.open('https://facebook.com','_blank')">สั่งซื้อผ่าน Facebook</button>
    </div>

    <!-- Garena -->
    <div class="item">
        <img src="https://i.ibb.co/0m61qYk/garena.png" alt="Garena Shells">
        <h3>Garena Shells</h3>
        <div class="price">เริ่มต้น 50 บาท</div>
        <p>โค้ดเติม Garena / ROV / LoL ของแท้ 100%</p>
        <button onclick="window.open('https://facebook.com','_blank')">สั่งซื้อผ่าน Facebook</button>
    </div>

    <!-- Valorant -->
    <div class="item">
        <img src="https://i.ibb.co/2F0xmMC/valorant.jpg" alt="Valorant Points">
        <h3>Valorant Points</h3>
        <div class="price">เริ่มต้น 399 บาท</div>
        <p>โค้ดเติม VP ของแท้ ราคาพิเศษสำหรับสายยิง</p>
        <button onclick="window.open('https://facebook.com','_blank')">สั่งซื้อผ่าน Facebook</button>
    </div>

    <!-- Roblox -->
    <div class="item">
        <img src="https://i.ibb.co/GHhjmV1/roblox.jpg" alt="Robux">
        <h3>Robux (Roblox)</h3>
        <div class="price">เริ่มต้น 99 บาท</div>
        <p>เติม Robux ราคาถูก 100% ปลอดภัยแน่นอน</p>
        <button onclick="window.open('https://facebook.com','_blank')">สั่งซื้อผ่าน Facebook</button>
    </div>

    <!-- Free Fire -->
    <div class="item">
        <img src="https://i.ibb.co/nrNbNhx/freefire.jpg" alt="Free Fire Topup">
        <h3>Free Fire Diamond</h3>
        <div class="price">เริ่มต้น 399 บาท</div>
        <p>เพชร Free Fire ราคาถูก เติมไว ชัวร์ 100%</p>
        <button onclick="window.open('https://facebook.com','_blank')">สั่งซื้อผ่าน Facebook</button>
    </div>

</div>

<footer>
    © 2025 PIGMAN SHOP - All Rights Reserved
</footer>

</body>
</html>
