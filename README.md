<!DOCTYPE html>
<html>
<head>
<title>Happy Holi</title>
<style>
body {
  margin: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  font-family: Arial, sans-serif;
  background: linear-gradient(-45deg, #ff512f, #dd2476, #24c6dc, #5433ff);
  background-size: 400% 400%;
  animation: gradient 8s ease infinite;
  overflow: hidden;
  color: white;
  text-align: center;
}

@keyframes gradient {
  0% {background-position: 0% 50%;}
  50% {background-position: 100% 50%;}
  100% {background-position: 0% 50%;}
}

h1 {
  font-size: 60px;
  text-shadow: 0 0 20px rgba(255,255,255,0.8);
}

h3 {
  margin-top: -10px;
  font-weight: normal;
}

.quote {
  margin-top: 30px;
  font-size: 20px;
  animation: fade 3s infinite alternate;
}

@keyframes fade {
  from {opacity: 0.5;}
  to {opacity: 1;}
}

.dot {
  position: absolute;
  width: 15px;
  height: 15px;
  background: white;
  border-radius: 50%;
  opacity: 0.6;
  animation: float 6s infinite ease-in-out;
}

@keyframes float {
  0% {transform: translateY(0);}
  50% {transform: translateY(-50px);}
  100% {transform: translateY(0);}
}
</style>
</head>

<body>

<h1>Happy Holi 🌈</h1>
<h3>by Aman</h3>

<div class="quote">May your life be filled with colors, joy & success ✨</div>

<div class="dot" style="top:20%; left:10%;"></div>
<div class="dot" style="top:70%; left:80%;"></div>
<div class="dot" style="top:50%; left:30%;"></div>
<div class="dot" style="top:30%; left:70%;"></div>

</body>
</html>
