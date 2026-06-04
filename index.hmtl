# index.html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BitFaucet Gratis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1a1a1a;
            color: #ffffff;
            text-align: center;
            padding: 50px 20px;
        }
        .container {
            max-width: 400px;
            margin: 0 auto;
            background: #2a2a2a;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0px 4px 15px rgba(0,0,0,0.5);
        }
        h1 { color: #ff9900; }
        input[type="text"] {
            width: 90%;
            padding: 10px;
            margin: 15px 0;
            border: none;
            border-radius: 5px;
        }
        button {
            background-color: #ff9900;
            color: black;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 5px;
            cursor: pointer;
            width: 95%;
        }
        button:hover { background-color: #e68a00; }
        .footer { margin-top: 20px; font-size: 12px; color: #888; }
    </style>
</head>
<body>

<div class="container">
    <h1>BitFaucet</h1>
    <p>Masukkan alamat Bitcoin / Email FaucetPay kamu untuk mengklaim Satoshi gratis!</p>
    
    <!-- Form untuk user memasukkan alamat crypto -->
    <input type="text" id="wallet" placeholder="Contoh: user@email.com atau Alamat BTC">
    <br>
    <button onclick="claimFaucet()">Klaim Sekarang</button>
</div>

<div class="footer">
    Powered by FaucetPay API & GitHub Pages
</div>

<script>
    function claimFaucet() {
        var walletInput = document.getElementById('wallet').value;
        if(walletInput === "") {
            alert("Harap isi alamat dompet atau email FaucetPay kamu!");
            return;
        }
        
        // Catatan keandalan keamanan: Proses klaim API FaucetPay yang asli 
        // harus ditembak lewat Server/Backend (bukan di JavaScript frontend ini) 
        // agar API Key rahasia kamu tidak dicuri orang lain.
        alert("Permintaan klaim dikirim untuk: " + walletInput + ". Hubungkan script backend kamu untuk memproses payout otomatis.");
    }
</script>

</body>
</html>
