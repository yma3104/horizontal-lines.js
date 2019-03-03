# horizontal-lines.js

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
	
  for (var x = 10; x <= 390; x = x + 10) {
    line(x, 10, x, x + 100);
  }
}
