<html>
  <head>
<<<<<<< HEAD
    <style type="text/css">
      .title-word {
	  animation: color-animation 4s linear infinite;
      }
=======

   <link rel="stylesheet" type="text/css" href="main.css" />
>>>>>>> babf16838eccce6e08785cef3d033bab9b13788d

.title-word-1 {
    --color-1: #DF8453;
    --color-2: #3D8DAE;
    --color-3: #E4A9A8;
}

.title-word-2 {
    --color-1: #DBAD4A;
    --color-2: #ACCFCB;
    --color-3: #17494D;
}

.title-word-3 {
    --color-1: #ACCFCB;
    --color-2: #E4A9A8;
    --color-3: #ACCFCB;
}

.title-word-4 {
    --color-1: #3D8DAE;
    --color-2: #DF8453;
    --color-3: #E4A9A8;
}

@keyframes color-animation {
    0%    {color: var(--color-1)}
    32%   {color: var(--color-1)}
    33%   {color: var(--color-2)}
    65%   {color: var(--color-2)}
    66%   {color: var(--color-3)}
    99%   {color: var(--color-3)}
    100%  {color: var(--color-1)}
}

/* Here are just some visual styles. ?? */

.container {
    display: grid;
    place-items: center;  
    text-align: center;
  height: 100vh
}

.title {
    font-family: "Montserrat", sans-serif;
    font-weight: 800;
    font-size: 8.5vw;
    text-transform: uppercase;
}
      
      </style>
  </head>
  <body>

    <div class="container">
  <h2 class="title">
    <span class="title-word title-word-1">This</span>
    <span class="title-word title-word-2">is</span>
    <span class="title-word title-word-3">my</span>
    <span class="title-word title-word-4">text</span>
  </h2>
</div>

  </body>
</html>
