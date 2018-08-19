#Transitions
Lets you move, warp, rotate and scale elements.


#Transition Duration
Controls how long the transition should take. You can pass in multiple durations, which is established by the order properties are listed in.

```css
div:hover {
  transform: translateX(100px);
  transition-duration: 1s;
}
```

#Transition Property
Controls which properties should be transitioned. Can be comma-separated.

```css
div:hover {
  transform: scale(2,5);
  background: red;
  transition-property: background;
}
```

#Transition Timing Function
What's the acceleration curve for the transition?

```css
div:hover {
  transform: rotate(45deg);
  transition-timing-function: ease-in;
  transition-timing-function: ease-out;
  transition-timing-function: linear;
}
```

#Transition Delay
How long of a delay before the transition starts?
```css
div:hover {
  transform: rotate(45deg);
  transition-delay: 5ms;
}
```

#Shorthand Transitions
Property, Duration, Timing Function, Delay. You can string multiple transitions together by separating with commas.

```css
div:hover{
  transition: background 1.5s ease-in 1;
}
```
