# 🎨 Neural Style Transfer - CODTECH Task 3

This project allows users to apply famous artistic styles to their photos using Neural Style Transfer techniques, combining the content of one image with the style of another. Users can upload their own content and style images or choose from a rich set of preset styles such as *Starry Night*, *Picasso*, *Sketch*, and many more.

## ✨ Features

- Upload your own content and style images.
- Choose from **20+ preset styles** (e.g., Starry Night, Picasso, Gothic, Watercolor).
- Real-time image preview.
- Style transfer processing with animated progress feedback.
- One-click download of the stylized result.
- Fully responsive and visually enhanced UI built with **Tailwind CSS**.
- Lightweight, client-side TensorFlow.js integration (placeholder for future backend).

## 📸 How It Works

1. Upload your **content image** (photo you want to stylize).
2. Upload your **style image** or choose a **preset style**.
3. Click **Apply Style Transfer** to process.
4. View and **download** your stylized image.

## 🛠 Tech Stack

- **HTML/CSS/JS**
- **Tailwind CSS**
- **TensorFlow.js** (setup placeholder)
- Client-side rendering and canvas manipulation

## Technologies Used:-

    HTML5: Structure of the web page.

    CSS3 (Tailwind CSS): For modern, responsive, and visually appealing styling.

    JavaScript (ES6+): Core logic for image handling, style application, and UI interactions.

    TensorFlow.js (Simulated): The code includes tf.min.js for potential future deep learning integration, though current style transfer for custom images is handled with client-side image manipulation techniques for simplicity and performance. Preset styles use custom canvas drawing functions to simulate artistic effects.

## How to Use

    Open NeuralStyleTransfer.html: Open the NeuralStyleTransfer.html file in your web browser.

    Upload Content Image: Click "Choose Content Image" and select an image from your device.

    Select Style:

        Preset Style: Click on any of the provided style buttons (e.g., "Starry Night", "Picasso").

        Custom Style: Click "Choose Style Image" and upload your own artwork or image whose style you want to transfer.

    Apply Style Transfer: Once both images (or content image and a preset style) are selected, the "🚀 Apply Style Transfer" button will become active. Click it to begin processing.

    View Results & Download: After a brief simulated processing time, the original and stylized images will be displayed. Click "📥 Download Result" to save your transformed image.

## Project Structure

.
├── NeuralStyleTransfer.html    # The main web application file
├── 6.gif                       # Background image used in the CSS (assumed)
└── README.md                   # This file

## Local Development

To run this project locally:

    Clone this repository or download the NeuralStyleTransfer.html file.

    Ensure 6.gif (or any other background image you prefer) is in the same directory as the html file, or update the background URL in the CSS.

    Open NeuralStyleTransfer.html in your preferred web browser.

## Contributing:-
Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, feel free to open an issue or submit a pull request.

## 🔧 Future Improvements

- Integrate a real **TensorFlow model** for deep style transfer.
- Add drag-and-drop support.
- Improve performance with WebGL/WebAssembly.

## 👨‍🎨 Created By

**Anmol Singh ❤️**  

---

