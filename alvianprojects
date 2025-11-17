# alvianprojects-
halaman semangatt kerja nya kak alvian😸
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Semangat Kerjanya Kak Alvian 💙🐱</title>

<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(135deg, #0a1a3a, #123c7c);
        color: white;
        text-align: center;
        overflow-x: hidden;
    }

    h1 {
        margin-top: 60px;
        font-size: 30px;
        color: #ffffff;
        text-shadow: 0 0 10px #6ea2ff;
    }

    .cat {
        font-size: 60px;
        animation: bounce 2s infinite;
        display: block;
        margin-top: 20px;
    }

    @keyframes bounce {
        0% { transform: translateY(0); }
        50% { transform: translateY(-20px); }
        100% { transform: translateY(0); }
    }

    .hearts {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        overflow: hidden;
        pointer-events: none;
    }

    .heart {
        position: absolute;
        color: pink;
        font-size: 20px;
        animation: floatUp 4s linear infinite;
        opacity: 0.8;
    }

    @keyframes floatUp {
        from { transform: translateY(100vh); opacity: 1; }
        to { transform: translateY(-10vh); opacity: 0; }
    }
</style>

</head>
<body>

<h1>Semangat kerjanya Kak Alvian 💙🐱<br>Jangan lupa senyum!</h1>

<div class="cat">🐱💙</div>

<div class="hearts" id="hearts"></div>

<script>
    function createHeart() {
        const heart = document.createElement("div");
        heart.classList.add("heart");
        heart.innerHTML = "💗";
        heart.style.left = Math.random() * 100 + "vw";
        heart.style.fontSize = (20 + Math.random() * 20) + "px";
        document.getElementById("hearts").appendChild(heart);

        setTimeout(() => { heart.remove(); }, 4000);
    }
    setInterval(createHeart, 400);
</script>

</body>
</html>
