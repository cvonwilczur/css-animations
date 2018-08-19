#Keyframes
Allow for more complicated transitions and animations as a series.

#Step 1: Define
Initially, you must define the animation itself.

```css
@keyframes rainbowtext {
  0%{
    color: red;
    font-size: 20px;
  }
  25%{
    color: orange;
  }
  50%{
    color: yellow;
    font-size: 40px;
  }
  75%{
    color: green;
  }
  100%{
    color: blue;
    font-size: 20px;
  }
}
```

#Step 2: Apply the animation
Once defined, you must apply the animations
```css
p {
  animation-name: rainbowtext;
  animation-duration: 3s;
  animation-timing-function: linear;
  animation-delay: 0s;
  animation-iteration-count: infinite;
}
```

#Other Animation properties

#animation-iteration-count
Establishes how many times the animation applies

```css
p {
  animation-iteration-count: infinite;
}
```

#animation-direction
Determines the direction of the animations
```css
p {
  animation-direction: reverse;
}
```

#animation-fill-mode
Specifies how the animation should apply styles before and after the animations

```css
p {
  animation-fill-mode: backwards;
}
```

#animation-play-state
Allows you to do things like pause the animation

```css
p:hover {
  animation-play-state: paused;
}
```
