<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to the Art Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    text-align: center;
    background: url('paint.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Container */
.container {
    background: rgba(0, 0, 0, 0.7);
    padding: 40px;
    border-radius: 10px;
    color: white;
    width: 90%;
    max-width: 600px;
    animation: fadeIn 2s ease-in-out;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

.fade-in {
    animation: fadeIn 2s ease-in-out;
}

.slide-in {
    animation: slideIn 1.5s ease-in-out;
}

@keyframes slideIn {
    from { transform: translateY(50px); opacity: 0; }
    to { transform: translateY(0); opacity: 1; }
}

/* Button */
.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 18px;
    color: white;
    background: crimson;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s ease-in-out;
}

.btn:hover {
    background: darkred;
    transform: scale(1.1);
}
</style>
<body>

    <div class="container">
        <h1 class="fade-in">Welcome to the Famous Paintings Gallery</h1>
        <p class="slide-in">Explore the world's most iconic artworks</p>
        <a href="Home.html" class="btn">Enter Website</a>
    </div>

</body>
</html>
