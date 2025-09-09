<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday Nani 🎉</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Poppins', sans-serif;
      overflow: hidden;
    }h1 {
  font-size: 3rem;
  color: #fff;
  text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
  animation: fadeIn 3s ease-in-out;
}

h2 {
  font-size: 1.5rem;
  color: #fff;
  margin-top: 10px;
  animation: fadeIn 4s ease-in-out;
}

.heart {
  position: absolute;
  width: 20px;
  height: 20px;
  background: red;
  transform: rotate(45deg);
  animation: float 6s infinite;
  bottom: -20px;
}

.heart::before, .heart::after {
  content: '';
  position: absolute;
  width: 20px;
  height: 20px;
  background: red;
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

@keyframes float {
  0% {transform: translateY(0) rotate(45deg); opacity: 1;}
  100% {transform: translateY(-800px) rotate(45deg); opacity: 0;}
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}

.message {
  margin-top: 20px;
  padding: 15px 25px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 15px;
  color: #fff;
  font-size: 1.2rem;
  text-align: center;
  animation: fadeIn 6s ease-in-out;
}

  </style>
</head>
<body>
  <h1>🎂 Happy Birthday Nani 💖</h1>
  <h2>Lots of love to you, Radha 💕</h2>
  <div class="message">
    You are my world, my smile, and my forever. <br>
    Wishing you the happiest birthday, my dearest Nani! 💝
  </div>  <audio autoplay loop>
    <source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_5bfb0b72e6.mp3?filename=romantic-piano-11364.mp3" type="audio/mpeg">
  </audio>  <script>
    function createHeart() {
      const heart = document.createElement('div');
      heart.className = 'heart';
      heart.style.left = Math.random() * 100 + 'vw';
      heart.style.animationDuration = (3 + Math.random() * 5) + 's';
      document.body.appendChild(heart);
      setTimeout(() => heart.remove(), 8000);
    }
    setInterval(createHeart, 400);
  </script></body>
</html># Nani-s-birthday
Special 
