# Vague API ideas

````javascript
var $cubelet = $('.cubelet');
$cubelet.cubeletInit();

var coords = $cubelet.cubeletGetCoords();
console.log(coords); // { x: 0, y: 0, z: 0 }

// Shows drag handles
$cubelet.cubeletEnableEdit();

// Hides drag handles
$cubelet.cubeletDisableEdit();
````