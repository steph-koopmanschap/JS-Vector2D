# JS-Vector2D
A Vector2D class I use in my personal projects

Use the class in the following way

import Vector2D from './Vector2D.js'

let x = 5;
let y = 10;

myVector = new Vector2D(x, y);
myVector2 = new Vector2D(5, 10);
let addedVector = myVector.add(myVector2);
let absVector = Vector2D.abs(addedVector);
