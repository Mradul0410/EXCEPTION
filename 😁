<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Love Animation 💗</title>

<style>
body {
  margin: 0;
  overflow: hidden;
  background: radial-gradient(circle at center, #1a001a, #000);
  font-family: Arial, sans-serif;
}

/* Center text */
.love-text {
  position: absolute;
  top: 40%;
  width: 100%;
  text-align: center;
  font-size: 2.5rem;
  color: #ff80bf;
  text-shadow: 0 0 20px #ff4da6, 0 0 40px #ff1a8c;
  animation: glow 2s infinite alternate;
}

@keyframes glow {
  from { text-shadow: 0 0 10px #ff4da6; }
  to { text-shadow: 0 0 30px #ff1a8c, 0 0 60px #ff66b3; }
}

/* Heart shape */
.heart {
  position: absolute;
  width: 20px;
  height: 20px;
  background: #ff4da6;
  transform: rotate(45deg);
  animation: float 8s linear infinite;
}

.heart::before,
.heart::after {
  content: "";
  position: absolute;
  width: 20px;
  height: 20px;
  background: #ff4da6;
  border-radius: 50%;
}

.heart::before {
  top: -10px;
  left: 0;
}

.heart::after {
  left: -10px;
  top: 0;
}

/* Floating animation */
@keyframes float {
  0% {
    transform: translateY(100vh) rotate(45deg);
    opacity: 1;
  }
  100% {
    transform: translateY(-10vh) rotate(45deg);
    opacity: 0;
  }
}
</style>
</head>

<body>

<div class="love-text">Love You Bachaaa 💗</div>

<!-- Hearts -->
<script>
for (let i = 0; i < 30; i++) {
  let heart = document.createElement("div");
  heart.className = "heart";
  
  heart.style.left = Math.random() * 100 + "vw";
  heart.style.animationDuration = (5 + Math.random() * 5) + "s";
  heart.style.opacity = Math.random();
  heart.style.transform = "scale(" + (0.5 + Math.random()) + ") rotate(45deg)";
  
  document.body.appendChild(heart);
}
</script>

</body>
</html>
