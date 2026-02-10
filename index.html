<?php
$pageTitle = "Valentine's Day for Maria";
?>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title><?php echo $pageTitle; ?></title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #1a0a1f, #2d1b3d, #1f0f2e);
    background-size: 400% 400%;
    animation: gradientShift 15s ease infinite;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}

@keyframes gradientShift {
    0% {background-position: 0% 50%;}
    50% {background-position: 100% 50%;}
    100% {background-position: 0% 50%;}
}

/* Floating hearts */
.heart-bg {
    position: fixed;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    pointer-events: none;
    z-index: -1;
}

.heart-float {
    position: absolute;
    opacity: 0.15;
    animation: float-up 6s infinite ease-in;
}

@keyframes float-up {
    to {
        transform: translateY(-100vh) rotate(360deg);
        opacity: 0;
    }
}

/* Container */
.container {
    background: rgba(30, 15, 40, 0.95);
    padding: 60px 40px;
    border-radius: 30px;
    box-shadow: 0 20px 60px rgba(255, 20, 147, 0.4);
    text-align: center;
    max-width: 500px;
    width: 90%;
    border: 2px solid rgba(255, 105, 180, 0.6);
    position: relative;
}

.heart-icon {
    font-size: 60px;
    animation: heartbeat 1.5s infinite;
}

@keyframes heartbeat {
    0%,100% {transform: scale(1);}
    50% {transform: scale(1.15);}
}

.title {
    font-size: 2.2em;
    color: #ff69b4;
    margin-bottom: 15px;
}

.message {
    font-size: 1.1em;
    color: #f8c8dc;
    margin-bottom: 20px;
    display: none;
}

.message.show {
    display: block;
}

.question {
    font-size: 1.6em;
    color: #ff1493;
    margin-bottom: 30px;
}

/* Buttons */
.button-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.btn {
    padding: 15px 40px;
    font-size: 1em;
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: 0.3s ease;
}

.btn-yes {
    background: linear-gradient(135deg, #ff1493, #ff69b4);
    color: white;
}

.btn-yes:hover {
    transform: translateY(-3px);
}

.btn-no {
    background: #ccc;
    color: #333;
    position: fixed;
    left: 50%;
    top: 60%;
}
</style>
</head>

<body>

<div class="heart-bg" id="heartBg"></div>

<div class="container">
    <div class="heart-icon">❤️</div>

    <h1 class="title">Hi Maria 💕</h1>

    <p class="message" id="romanticText">
        You've always been an amazing friend.  
        Your smile brightens my world, and your presence makes everything better.  
        I would love to celebrate this Valentine’s Day with you.
    </p>

    <p class="question">Will you be my Valentine? 💖</p>

    <div class="button-container">
        <button class="btn btn-yes" id="yesBtn">YES</button>
        <button class="btn btn-no" id="noBtn">NO</button>
    </div>
</div>

<script>
// Floating hearts
function generateHearts() {
    const heartBg = document.getElementById('heartBg');
    const hearts = ['❤️','💕','💖','💗','💝'];

    for (let i = 0; i < 20; i++) {
        const heart = document.createElement('div');
        heart.className = 'heart-float';
        heart.textContent = hearts[Math.floor(Math.random() * hearts.length)];
        heart.style.left = Math.random() * 100 + '%';
        heart.style.top = '100%';
        heart.style.fontSize = (Math.random() * 30 + 20) + 'px';
        heart.style.animationDuration = (Math.random() * 4 + 4) + 's';
        heartBg.appendChild(heart);
    }
}
generateHearts();

const yesBtn = document.getElementById('yesBtn');
const noBtn = document.getElementById('noBtn');
const romanticText = document.getElementById('romanticText');

let yesClicks = 0;

yesBtn.addEventListener('click', function() {
    yesClicks++;

    // First click → Show romantic message
    if (yesClicks === 1) {
        romanticText.classList.add('show');
        noBtn.style.display = 'none';
        yesBtn.textContent = "YES, I DO! 💖";
    }

    // Second click → Open WhatsApp directly
    else if (yesClicks === 2) {
        const phoneNumber = "254704953928";
        const message = encodeURIComponent(
            "Hey Paul ❤️ YES I wanna be your Valentine! 💕"
        );
        const whatsappURL = `https://wa.me/${phoneNumber}?text=${message}`;
        window.open(whatsappURL, "_blank");
    }
});

// NO button runs away
function moveButton() {
    const radius = 250;
    const angle = Math.random() * 2 * Math.PI;
    const x = Math.cos(angle) * radius;
    const y = Math.sin(angle) * radius;
    noBtn.style.transform = `translate(calc(-50% + ${x}px), calc(-50% + ${y}px))`;
}

noBtn.addEventListener('mouseover', moveButton);
noBtn.addEventListener('click', function(e){
    e.preventDefault();
    moveButton();
});
noBtn.addEventListener('touchstart', function(e){
    e.preventDefault();
    moveButton();
});
</script>

</body>
</html>
