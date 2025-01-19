
<html>
<head>
<title>Valentine's Day Letter</title>
<style>
body {
  background-color: #ffc0cb;
  font-family: 'Times New Roman', sans-serif;
}

.container {
  width: 500px;
  height: 600px;
  margin: 50px auto;
  perspective: 800px;
}

.letter {
  width: 100%;
  height: 100%;
  background-color: #fff;
  border: 2px solid #c0c0c0;
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.2);
  position: relative;
  transform-style: preserve-3d;
  transform-origin: 50% 100%; /* Corrected transform origin */
  animation: openLetter 1s ease-in-out forwards;
}

.letter-front {
  position: absolute;
  backface-visibility: hidden;
  transform: rotateY(0deg);
  width: 100%;
  height: 100%;
  background-color: #fff;
  padding: 20px;
  text-align: center;
}

.letter-back {
  position: absolute;
  backface-visibility: hidden;
  transform: rotateY(180deg);
  width: 100%;
  height: 100%;
  background-color: #fff;
  padding: 20px;
  text-align: center;
}

.heart {
  width: 50px;
  height: 50px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  animation: beat 1s infinite ease-in-out;
  z-index: 1; /* Ensure heart is on top */
}

.heart::before, .heart::after {
  content: "";
  position: absolute;
  background-color: red;
  border-radius: 500%;
}

.heart::before {
  width: 50px;
  height: 50px;
  top: 0;
  left: 0;
  transform: rotate(100deg);
}

.heart::after {
  width: 50px;
  height: 50px;
  top: 0;
  left: 0;
  transform: rotate(50deg);
}

@keyframes openLetter {
  0% { transform: rotateY(0deg); }
  100% { transform: rotateY(-180deg); } /* Adjusted rotation */
}

@keyframes beat {
  0% { transform: translate(-50%, -50%) scale(1); }
  50% { transform: translate(-50%, -50%) scale(1.1); }
  100% { transform: translate(-50%, -50%) scale(1); }
}
</style>
</head>
<body>
<div class="container">
  <div class="letter">
    <div class="letter-front">
      <div class="heart"></div>
    </div>
    <div class="letter-back">
      <h1>Hi lovey Marie! ❤️</h1>
      <h1>Will you be my valentine this coming february 14? mwehehehe </h1> ❤️ YES❤️ or ❤️YES❤️
  
      
      
    
