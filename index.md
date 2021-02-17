<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | topViewShooter</title>
  </head>
  <body style="text-align: center">
    <canvas id="unity-canvas" style="width: 960px; height: 600px; background: #231F20"></canvas>
    <script src="Build/zombi.loader.js"></script>
    <script>
      createUnityInstance(document.querySelector("#unity-canvas"), {
        dataUrl: "Build/zombi.data.br",
        frameworkUrl: "Build/zombi.framework.js.br",
        codeUrl: "Build/zombi.wasm.br",
        streamingAssetsUrl: "StreamingAssets",
        companyName: "DefaultCompany",
        productName: "topViewShooter",
        productVersion: "1.0",
      });
    </script>
  </body>
</html>
