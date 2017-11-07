
<link rel="shortcut icon" href="TemplateData/favicon.ico">
<link rel="stylesheet" href="TemplateData/style.css">
<script src="TemplateData/UnityProgress.js"></script>  
<script src="Build/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "Build/Builds.json", {onProgress: UnityProgress});
</script>

<div class="webgl-content">
  <div id="gameContainer" style="height: 100%"></div>
  <div class="footer">
    <div class="webgl-logo"></div>
    <div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
    <div class="title">Josh</div>
  </div>
</div>