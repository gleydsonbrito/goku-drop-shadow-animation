# goku-drop-shadow-animation

## check it out: https://gleydsonbrito.github.io/goku-drop-shadow-animation/

### How to create shadow in png images

```
:root {
  --yellow: #FAC213;
  --blue: #85F4FF
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--blue);
}

img {
  height: 80%;
  width: auto;
  animation-name: qi;
  animation-duration: 2.5s;
  animation-iteration-count: infinite;
}

@keyframes qi {
  0% {}
  50% {
    -webkit-filter: drop-shadow(5px 5px 5px var(--yellow));
    filter: 
    drop-shadow( 10px -30px 10px var(--yellow)) 
    drop-shadow(-10px -30px 50px var(--yellow)) 
    drop-shadow(10px -30px 150px var(--yellow))
    drop-shadow(-10px -50px 200px var(--yellow));
  }
  100% {}
}

```
