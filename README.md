# project-11
<div class="project-heading">
  <h1 class="title">Image Slider</h1>
  <div class="subtitle">Click the buttons to change the image!</div>
</div>

<div id="slider">
  <img src="https://picsum.photos/id/1005/500/400" alt="Image 1">
  <img src="https://picsum.photos/id/1012/500/400" alt="Image 2">
  <img src="https://picsum.photos/id/1015/500/400" alt="Image 3">
  <img src="https://picsum.photos/id/1024/500/400" alt="Image 4">
  <button id="prev">&lt;</button>
  <button id="next">&gt;</button>
</div>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="app.js"></script>
    <title>Document</title>
</head>
<body>
    <div class="project-heading">
        <h1 class="title">Image Slider</h1>
        <div class="subtitle">Click the buttons to change the image!</div>
      </div>
      
      <div id="slider">
        <img src="https://picsum.photos/id/1005/500/400" alt="Image 1">
        <img src="https://picsum.photos/id/1012/500/400" alt="Image 2">
        <img src="https://picsum.photos/id/1015/500/400" alt="Image 3">
        <img src="https://picsum.photos/id/1024/500/400" alt="Image 4">
        <button id="prev">&lt;</button>
        <button id="next">&gt;</button>
      </div>
</body>
</html>
<title>light Dark mode</title>
</head>
<body>
  <div id=""element"light and dark mode">element</div>

  <title>Animation</title>
</head>
</body>
div id ="element"Animation">element</div>
  
let currentIndex = 0;

function reset() { for (let i = 0; i < images.length; i++) { images[i].classList.remove('active'); } }

function initializeSlider() { reset(); images[currentIndex].classList.add('active'); }

function slideLeft() { reset(); currentIndex--; if (currentIndex < 0) { currentIndex = images.length - 1; } images[currentIndex].classList.add('active'); }

function slideRight() { reset(); currentIndex++; if (currentIndex >= images.length) { currentIndex = 0; } images[currentIndex].classList.add('active'); }

initializeSlider();

previousImage.addEventListener('click', function() { slideLeft(); });

nextImage.addEventListener('click', function() { slideRight(); });

const element = document.getElementById("element")
    
const section = document.getElementById("section")
const button = document.getElementById("button")
​
​
​
​
const Dark light  = () => {
    console.log("Dark light mode")
    element.classList.toggle("light")
    section.classList.toggle("dark")
   
}
button.addEventListener("dark light mode")

const = Animation 
console.log (Animation)
button.getAnimations{}
