<html>
<head>
<meta charset="UTF-8">
<title>Test Ảnh</title>
</head>
<body>
<canvas id="gameCanvas" width="800" height="600"></canvas>
<script>
const canvas = document.getElementById('gameCanvas');
const ctx = canvas.getContext('2d');

const bgImage = new Image();
const character = new Image();

bgImage.src = "background.jpg";
character.src = "character_happy.png";

window.onload = function() {
    ctx.drawImage(bgImage, 0, 0, canvas.width, canvas.height);
    ctx.drawImage(character, 330, 120, 150, 150);
};
</script>
</body>
</html>
