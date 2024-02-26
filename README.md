<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Emoji Rotation</title>
<style>
@keyframes blink {
0% {
opacity: 1;
}
50% {
opacity: 0;
}
100% {
opacity: 1;
}
}

.blink {
animation: blink 1s infinite;
color: green;
}
@keyframes rotate {
from {
transform: rotate(0deg);
}
to {
transform: rotate(360deg);
}
}

.emoji {
animation: rotate 5s linear infinite; /* Adjust the duration as needed */
display: inline-block;
font-size: 2rem; /* Adjust the size as needed */
}
</style>
<script>
setTimeout(function() {
// Change the message after 3 seconds
document.getElementById('message').innerHTML = "";
}, 3000); // 3000 milliseconds = 3 seconds
</script>
</head>
<body>
<h1 color="green" id="message">Initializing Secure Connection...<span class="emoji">⚙</span></h1>
</body>
</html>
