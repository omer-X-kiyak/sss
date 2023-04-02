<!DOCTYPE html>
<html>
  <head>
    <title>GitHub Hareketli Efekt</title>
    <style>
      /* GitHub ikonu stili */
      .github-icon {
        width: 100px;
        height: 100px;
        background-color: black;
        border-radius: 50%;
        position: relative;
        animation: github-pulse 2s ease-out infinite;
      }
      
      /* Hareketli efekt animasyonu */
      @keyframes github-pulse {
        0% {
          transform: scale(1);
          opacity: 1;
        }
        50% {
          transform: scale(1.2);
          opacity: 0.7;
        }
        100% {
          transform: scale(1);
          opacity: 1;
        }
      }
    </style>
  </head>
  <body>
    <div class="github-icon"></div>
  </body>
</html>
