# A simple basic ThreeJS template

This code creates simple black box and renders it using ThreeJS. 

A spotlight and rotation animation are added for effect.

## Run locally

To run this on your own computer, follow these simple commands. 

Clone this repo:
```bash
npx degit https://github.com/numberthink/vite-threejs-template.git
```

Install dependencies:
```bash
npm install
```

Run:
```bash
npm run dev
```

The ThreeJS scene is created and rendered `src/script.js`. 

## Basic features/opinions

Leave them be or remove these at your leisure.

 - Renderer uses `THREE.ACESFilmicToneMapping` for more cinematic feel
 - Orbit controls (changes the camera angle when you click and drag)
 - Updates canvas size and camera aspect ratio on window resize
 - Pauses/plays animation when you press the "f" key
 - Can update rotation speeds by setting the `boxParams`

 ```js
 // speed is rotations per second
const boxParams = {
    xRotationSpeed: .05,
    yRotationSpeed: .1,
    zRotationSpeed: .1,
}
 ```

