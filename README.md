# Packman Animation

Pacman Animation is an animated HTML page with CSS styles.
![Alt Text](https://media.giphy.com/media/GNY2f4TY4n80YsJUUW/giphy.gif)

## Description

This project has a simple and clear HTML structure and CSS styles. CSS variables were used for code optimization. The animation was created with @keyframes rules, animation, and clip-path.

## Example

```css

@keyframes whiteCircle {
  0% {
    right: 0;
  }
  50% {
    right: 8%;
  }
  100% {
    right: 16.2%;
  }
}


.white-circle {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: var(--white);
  position: relative;
  animation-name: whiteCircle;
  animation-duration: 1s;
  animation-iteration-count: var(--infinite);
  animation-timing-function: var(--linear);
}
```
## Status

finished.
