# sss
<!DOCTYPE html>
<html>
  <head>
    <title>GitHub Hareketli Efekti</title>
    <style>
      /* Temel stiller */
      body {
        margin: 0;
        padding: 0;
        background-color: #1f1f1f;
      }
      .container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      .github-logo {
        width: 100px;
        height: 100px;
        fill: white;
      }
      /* Animasyon stilleri */
      @keyframes move {
        0% {
          transform: translateY(0);
        }
        50% {
          transform: translateY(-30px);
        }
        100% {
          transform: translateY(0);
        }
      }
      .github-logo {
        animation-name: move;
        animation-duration: 2s;
        animation-iteration-count: infinite;
        animation-timing-function: ease-in-out;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <svg
        class="github-logo"
        viewBox="0 0 16 16"
        version="1.1"
        aria-hidden="true"
      >
        <path
          fill-rule="evenodd"
          d="M8 .5a7.5 7.5 0 0 0-2.37 14.63c.37.07.51-.16.51-.36v-1.26c-2.09.45-2.53-1.01-2.53-1.01-.34-.86-.83-1.09-.83-1.09-.68-.46.05-.45.05-.45.75.05 1.15.77 1.15.77.67 1.15 1.76.82 2.19.63.07-.46.26-.82.47-1.01-1.65-.19-3.39-.82-3.39-3.68 0-.81.29-1.47.77-1.99-.07-.19-.33-.94.07-1.96 0 0 .62-.2 2.03.76.59-.16 1.22-.24 1.85-.24s1.26.08 1.85.24c1.41-.96 2.03-.76 2.03-.76.4 1.02.14 1.77.07 1.96.48.52.77 1.18.77 1.99 0 2.87-1.74 3.49-3.39 3.68.27.23.51.68.51 1.37v2.03c0 .2.14.43.52.36A7.5 7.5 0 0 0 8 .5"
        />
      </svg>
    </div>
  </body>
</html>
