# Preliminary_WebVR
 
Modified starter project based on: cassieview
https://github.com/cassieview/Build-First-Web-VR-Game-Absolute-Beginner/

My own code: https://playground.babylonjs.com/#B2FDXD#5

Note 1: in line 26 I replaced
```javascript
spheres[index] = BABYLON.Mesh.CreateIcoSphere("sphere", {radius:0.8, flat:true, subdivisions: 16}, this.scene);
```
with
```javascript
pheres[index] = BABYLON.Mesh.CreateIcoSphere("sphere", {radius:0.8, flat:true, subdivisions: 16}, scene);
```

Since the original code seems not working properly.

Note 2: If you simply clone the project and open the index.html in Chrome, you may encounter security issues that prevent the page from loading properly:
Please access the project via my web server(Working in Progress), or run the html file on localhost: https://stackoverflow.com/questions/38497334/how-to-run-html-file-on-localhost
