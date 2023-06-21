HTML
<!DOCTYPE html>
<html>
<head>
<title>My First JavaScript App</title>
<link rel="stylesheet" href="index.css">
</head>
<body>
<div id="app"></div>
<script src="index.js"></script>
</body>
</html>
JAVA SCRIPT
const app = document.getElementById("app");

function changeColor() {
  app.style.color = "red";
}

app.addEventListener("click", changeColor);
