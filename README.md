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

setTimeout(function() {
document.getElementById('message').innerHTML = "";
}, 3000);
<h1 class="blink" id="message">Initializing Secure Connection...<span class="emoji">⚙</span></h1>
