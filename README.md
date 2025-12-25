# Perfect PFP

Perfect PFP is a lightweight web tool that converts any image into a clean, circular profile picture while preserving the full image content.

Unlike typical profile picture croppers, this tool does **not** cut off the top or bottom of images, does **not** blur the background, and does **not** distort proportions. Rectangular images are converted into a true 1×1 square using edge extension, then masked into a circle.

## ✨ Features

- Drag & drop image upload
- Converts any aspect ratio into a true square (1×1)
- No cropping, no stretching, no blur
- Edge-extension padding for natural results
- Circular profile picture output
- Transparent PNG export
- Works fully in the browser (no backend)

## 🧠 How It Works

1. The uploaded image is analyzed for its width and height  
2. A square canvas is created based on the largest side  
3. The image is centered in the square  
4. Missing areas are filled by extending edge pixels  
5. The square image is masked into a perfect circle  
6. The final result is exported as a PNG  

## 🛠️ Tech Stack

- HTML
- CSS
- JavaScript (Canvas API)
- No external libraries

## 🚀 Live Demo

