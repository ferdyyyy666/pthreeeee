
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page Sederhana</title>
    <link rel="stylesheet" href="styles.css">
</head>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: url('pZLqxF5.jpeg.jpeg') no-repeat center center/cover;
}

.container {
    background-color: rgba(178, 176, 176, 0.8);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}
header button {
    background-color: #4CAF50;
    color: rgb(129, 123, 123);
    padding: 15px 25px;
    border: none;
    border-radius: 5px;
    font-size: 1em;
    cursor: pointer;
    transition: background-color 0.3s;
}

header button:hover {
    background-color: #409344;
}
header p {
    font-size: 1.2em;
    margin-bottom: 20px;
}

main section {
    margin-bottom: 20px;
}

main section h2 {
    font-size: 1.8em;
    margin-bottom: 10px;
}

main section p {
    font-size: 1em;
    line-height: 1.5;
}

footer p {
    font-size: 0.9em;
    color: #666;
}

<body>
    <div class="container">
        <header>
            <h1>Selamat Datang di Website PTHREE</h1>
            <p>Menyediakan Layanan Terbaik untuk Anda</p>
        </header>
        <main>
            <section>
                <h2>Tentang Kami</h2>
                <p>Kami adalah adalah komunitas baca dari SMAN 2 MUARA TEWEH .</p>
            </section>
            <section>
                <h2>Kegiatan Kami</h2>
                <p>Kami sering berbagi prolog cerita dari buku yang kami pinjam dan kami juga sering kumpul untuk membahas pembuatan madding atau buku yang kami buat sedndiri, dan kami ada lagu sendiri lo kalian bisa klik dibawah ini .</p>
                <button onclick="location.href='https:.com'">LETS KLIK</button>
            </header>    
            </section>
        </main>
        <footer>
            <p>&copy; 2024 PTHREE.</p>
        </footer>
    </div>
</body>
</html>
