            <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan Afifah & Gilang</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
            padding: 20px;
        }
        .header {
            background-color: #c08497;
            color: #fff;
            padding: 40px 20px;
            border-bottom: 5px solid #a8586b;
        }
        .header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .header p {
            margin-top: 10px;
            font-size: 1.2em;
        }
        .guest-name {
            font-size: 1.5em;
            font-weight: bold;
            color: #a8586b;
            margin-bottom: 20px;
            padding: 10px;
            background-color: #ffebee;
            border-radius: 5px;
            display: none; /* Akan ditampilkan oleh JavaScript jika ada nama tamu */
        }
        .content {
            padding: 30px;
        }
        .names {
            font-family: 'Playfair Display', serif; /* Contoh font elegan */
            font-size: 3em;
            color: #a8586b;
            margin: 0;
            line-height: 1.2;
        }
        .names span {
            font-size: 0.5em;
            display: block;
            margin-top: -10px;
        }
        .info-block {
            margin-top: 25px;
            padding-top: 25px;
            border-top: 1px solid #eee;
        }
        .info-block h3 {
            color: #c08497;
            margin: 0;
            font-size: 1.5em;
        }
        .info-block p {
            margin: 5px 0 0;
        }
        .button-link {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background-color: #c08497;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }
        .button-link:hover {
            background-color: #a8586b;
        }
        .footer {
            margin-top: 30px;
            padding: 20px;
            font-size: 0.9em;
            color: #666;
            border-top: 1px solid #eee;
        }
        /* Import Google Font for elegance */
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap');
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <p>Dengan memohon rahmat dan ridho Allah SWT, kami mengundang</p>
            <p class="guest-name" id="guestNameDisplay"></p>
            <p>untuk hadir dalam pernikahan kami:</p>
            <h1>Undangan Pernikahan</h1>
        </div>
        <div class="content">
            <h2 class="names">
                Afifah Romadhon <span>(Pipah)</span>
                <span>&</span>
                Gilang Surya K <span>(Gil / Lang)</span>
            </h2>
            <p style="font-style: italic; color: #555;">Putri dari Bapak/Ibu [Nama Orang Tua Pipah] & Putra dari Bapak/Ibu [Nama Orang Tua Gilang]</p>

            <div class="info-block">
                <h3>AKAD NIKAH</h3>
                <p>Hari, Tanggal: **Minggu, 30 November 2025**</p>
                <p>Waktu: **09.00 WIB**</p>
                <p>Lokasi: **[Alamat Lengkap Tempat Akad Nikah, contoh: Masjid Agung Baiturrahman, Jakarta]**</p>
            </div>

            <div class="info-block">
                <h3>RESEPSI PERNIKAHAN</h3>
                <p>Hari, Tanggal: **Minggu, 30 November 2025**</p>
                <p>Waktu: **11.00 - 15.00 WIB**</p>
                <p>Lokasi: **[Alamat Lengkap Tempat Resepsi, contoh: Gedung Serbaguna [Nama Gedung], Jakarta]**</p>
                <a href="[Link Google Maps Lokasi Resepsi]" class="button-link" target="_blank">Lihat di Peta</a>
            </div>
            
            <p style="margin-top: 30px;">Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir untuk memberikan doa restu.</p>

            <div class="info-block">
                <h3>Konfirmasi Kehadiran (RSVP)</h3>
                <p>Mohon konfirmasi kehadiran Anda melalui formulir berikut:</p>
                <a href="[Link Google Form RSVP Anda]" class="button-link" target="_blank">Konfirmasi Kehadiran</a>
                <p style="font-size: 0.85em; color: #777;">*Link akan mengarahkan ke Google Form untuk konfirmasi kehadiran.</p>
            </div>

            <div class="info-block">
                <h3>Buku Tamu & Ucapan</h3>
                <p>Silakan tinggalkan pesan dan doa terbaik Anda untuk kami:</p>
                <a href="[Link ke Buku Tamu Online Anda]" class="button-link" target="_blank">Tulis Ucapan</a>
                <p style="font-size: 0.85em; color: #777;">*Ini bisa berupa link ke website buku tamu khusus, atau fitur lain (lihat penjelasan di bawah).</p>
            </div>
        </div>
        <div class="footer">
            <p>Kami yang berbahagia,</p>
            <p>Keluarga Besar Afifah & Gilang</p>
        </div>
    </div>

    <script>
        // Fungsi untuk mengambil parameter dari URL
        function getUrlParameter(name) {
            name = name.replace(/[\[]/, '\\[').replace(/[\]]/, '\\]');
            var regex = new RegExp('[\\?&]' + name + '=([^&#]*)');
            var results = regex.exec(location.search);
            return results === null ? '' : decodeURIComponent(results[1].replace(/\+/g, ' '));
        };

        // Mengambil nama tamu dari URL
        var guestName = getUrlParameter('to');
        if (guestName) {
            document.getElementById('guestNameDisplay').innerText = guestName;
            document.getElementById('guestNameDisplay').style.display = 'block'; // Tampilkan elemen
        }
    </script>
</body>
</html>
