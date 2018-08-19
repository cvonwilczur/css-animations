#Transform
Lets you move, warp, rotate and scale elements.


#Translation
Translate will shift something across the screen using X and Y axes. s

```css
div:hover {
  transform: translateX(100px);
}

div:active {
  transform: translateY(100px);
}

div:focus {
  transform: translate(20px, 20px);
}
```

#Scaling
Altering the size of an element. The example below would double the size of the div. It's important to note that the origin of the scale is from the center point. We can alter that origin using transform-origin.

```css
div:hover {
  transform: scale(2,5);
}

div:hover {
  transform: scaleX(2);
}

div:hover {
  transform: scaleY(2);
  transform-origin: 0 0;
}
```

#Rotations
Using CSS to perform rotations. Could be an animated loader, for instance.

```css
div:hover {
  transform: rotate(45deg);
}
```
