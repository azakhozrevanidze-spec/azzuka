<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Alone Tribute</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>🎄 Home Alone 🎄</h1>
        <p class="subtitle">ნოსტალგიური კინომატოგრაფია ბავშვობის შთაბეჭდილებებით</p>

        <button id="showButton">ნახე ფოტო</button>
        <div id="photoContainer" class="hidden">
            <img src="image/Homealone.jpg.jpg" alt="Home Alone" width="300" height="200">
            <p class="caption">Home Alone</p>
        </div>
    </div>

    <script>
        const button = document.getElementById('showButton');
        const photoContainer = document.getElementById('photoContainer');

        button.addEventListener('click', () => {
            photoContainer.classList.toggle('hidden');
        });
    </script>
</body>
</html>
