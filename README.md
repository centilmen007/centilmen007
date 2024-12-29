<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Döviz Bürosu</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>
    <div class="container mt-5">
        <h1 class="text-center">Canlı Döviz Kurları</h1>
        <table class="table table-bordered mt-3" id="currencyTable">
            <thead>
                <tr>
                    <th>Döviz</th>
                    <th>Alış (Buy)</th>
                    <th>Satış (Sell)</th>
                </tr>
            </thead>
            <tbody>
                <!-- Dinamik olarak doldurulacak -->
            </tbody>
        </table>

        <h2 class="mt-5">Döviz Çevirici</h2>
        <div class="row">
            <div class="col-md-5">
                <input type="number" id="amount" class="form-control" placeholder="Miktar">
            </div>
            <div class="col-md-3">
                <select id="fromCurrency" class="form-control">
                    <!-- Dinamik olarak doldurulacak -->
                </select>
            </div>
            <div class="col-md-3">
                <select id="toCurrency" class="form-control">
                    <!-- Dinamik olarak doldurulacak -->
                </select>
            </div>
            <div class="col-md-1">
                <button id="convert" class="btn btn-primary">Çevir</button>
            </div>
        </div>
        <div id="result" class="mt-3"></div>
    </div>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
![Screenshot_2024-10-22-10-05-56-913_com haremaltin android haremaltin](https://github.com/user-attachments/assets/147cbde5-139a-4a3d-b636-e2b7d7633507)

