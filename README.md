<!DOCTYPE html>
<html>
<head>
  <title>Web AR Example with Hiro Marker</title>
  <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/AR-js-org/AR.js/aframe/build/aframe-ar.min.js"></script>
  <style>
    body { margin: 0; overflow: hidden; }
  </style>
</head>
<body>
  <a-scene embedded arjs>
    <a-marker preset="hiro">
      <a-box position="2 2 0" rotation="0 45 0" color="#800000"></a-box>
      <a-sphere position="5 0.20 0" radius="1.25" color="#CA8EFF"></a-sphere>
      <a-cylinder position="1 0.75 0" radius="0.5" height="2.6" color="#FF0000"></a-cylinder>
      <a-plane position="0 0 0" rotation="-90 0 0" width="5" height="5" color="#ffff00"></a-plane>
    </a-marker>
    <a-entity camera></a-entity>
  </a-scene>
</body>
</html>
