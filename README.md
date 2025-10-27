[Uploading teks.html…]()
<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun! 🎉</title>
    <style>
        /* CSS untuk Tampilan Ponsel (Mobile-First) */

        /* 1. Reset Dasar & Font */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f06b6b 0%, #ffc0cb 100%);
            /* Latar belakang gradien merah muda/merah */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            /* Memastikan mengambil seluruh tinggi viewport */
            color: #ffffff;
            /* Warna teks putih */
            text-align: center;
        }

        /* 2. Container Utama */
        .birthday-card {
            width: 90%;
            /* Lebar kartu 90% dari layar */
            max-width: 400px;
            /* Batasan lebar maksimal untuk layar yang lebih besar */
            background-color: rgba(255, 255, 255, 0.9);
            /* Latar belakang semi-transparan putih */
            padding: 30px 20px;
            border-radius: 20px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
            /* Bayangan lembut */
            backdrop-filter: blur(5px);
            /* Efek blur pada latar belakang (jika didukung) */
            animation: fadeIn 2s ease-out;
            /* Animasi muncul */
        }

        /* 3. Animasi Muncul */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* 4. Header & Pesan */
        h1 {
            font-size: 2.5em;
            /* Ukuran besar untuk header */
            color: #ff4500;
            /* Warna oranye terang */
            margin-bottom: 10px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.1);
        }

        h2 {
            font-size: 1.5em;
            color: #333333;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.1em;
            color: #555555;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        /* 5. Tombol atau Elemen Interaktif */
        .celebrate-button {
            display: inline-block;
            background-color: #ff6347;
            /* Tombol merah-jingga */
            color: white;
            padding: 12px 25px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.1s;
        }

        .celebrate-button:hover {
            background-color: #e55337;
            transform: scale(1.05);
        }

        /* 6. Footer/Tanda Tangan */
        .signature {
            margin-top: 30px;
            font-style: italic;
            color: #777777;
            font-size: 0.9em;
        }

        /* 7. Efek Kembang Api/Confetti (Opsional) */
        .emoji-burst {
            font-size: 3em;
            margin-top: 15px;
        }
    </style>
</head>

<body>

    <div class="birthday-card">
        <div class="emoji-burst">🎂🎉🎈</div>

        <h1>Selamat Ulang Tahun!</h1>

        <h2>Untuk [Nama Teman/Keluarga Anda]</h2>

        <p>
            Semoga hari ini penuh dengan kebahagiaan, tawa, dan semua yang terbaik dalam hidupmu.
            Terima kasih telah menjadi bagian yang luar biasa dalam hidup kami.
            Semoga semua impianmu tercapai!
        </p>

        <a href="#" class="celebrate-button">Rayakan Sekarang!</a>

        <div class="signature">
            Salam hangat, <br>
            [Nama Anda]
        </div>
    </div>

</body>

</html>
