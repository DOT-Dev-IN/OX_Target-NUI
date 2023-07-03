# Ox_Target NUI with Five different Animations

> Now You Can replace this Html code to = ``\ox_target\web\Index.Html``
   Or 
> Rename the files name to index.Html and paste in =  ``\ox_target\web``


https://i.imgur.com/Mdbmtpp.gif


https://i.imgur.com/N5fc4tw.gif
```Html
<html>
  <head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free/css/all.min.css" />
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div id="eye">
      <svg id="eyeSvg" xmlns="http://www.w3.org/2000/svg" height="36px" viewBox="0 0 448 512" width="36px" fill="#000000"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M32 32C14.3 32 0 46.3 0 64v96c0 17.7 14.3 32 32 32s32-14.3 32-32V96h64c17.7 0 32-14.3 32-32s-14.3-32-32-32H32zM64 352c0-17.7-14.3-32-32-32s-32 14.3-32 32v96c0 17.7 14.3 32 32 32h96c17.7 0 32-14.3 32-32s-14.3-32-32-32H64V352zM320 32c-17.7 0-32 14.3-32 32s14.3 32 32 32h64v64c0 17.7 14.3 32 32 32s32-14.3 32-32V64c0-17.7-14.3-32-32-32H320zM448 352c0-17.7-14.3-32-32-32s-32 14.3-32 32v64H320c-17.7 0-32 14.3-32 32s14.3 32 32 32h96c17.7 0 32-14.3 32-32V352z"/></svg>
    </div>
    <div id="options-wrapper"></div>
    <script defer type="module" src="js/main.js"></script>
  </body>
</html>
<style>
  #eyeSvg {
    animation: spin 2s linear infinite, colorchange 1s infinite;
    transform-origin: center;
  }

  @keyframes spin {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(360deg);
    }
  }
</style>
```
