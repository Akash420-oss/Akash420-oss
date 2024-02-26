<div style="
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
">

This is a <span class="blink">blinking</span> text.
</div>
