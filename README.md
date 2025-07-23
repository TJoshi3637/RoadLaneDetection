# 🛣️ Road Lane Detection System using OpenCV (Jupyter Notebook)

This project aims to design and implement a **Road Lane Detection System** capable of identifying lane markings in **real-time** from video feeds or images. Such a system is a foundational component of **Advanced Driver-Assistance Systems (ADAS)**, helping vehicles stay within lanes and aiding drivers during lane changes.

---

## 🎯 Project Objective

To build a computer vision-based system that:
- Detects lane lines on roads using static images or video
- Works in real-time (or near real-time)
- Uses basic image processing techniques (no deep learning)
- Can be a foundational prototype for autonomous vehicles or ADAS systems

---

## 🧠 Technologies Used

| Tool/Library     | Purpose                        |
|------------------|--------------------------------|
| Python           | Programming language           |
| Jupyter Notebook | Interactive development        |
| OpenCV           | Image/video processing         |
| NumPy            | Numerical operations           |
| Matplotlib       | Visualization of results       |

---

## 📁 Project Structure

road-lane-detection/
│
├── LaneDetection.ipynb # Main notebook with all code
├── test_images/ # Sample road images
├── test_videos/ # Sample road videos (MP4)
├── output_videos/ # Output videos with lane detection
└── README.md # Project documentation


---

## 🧪 Features & Workflow

1. **Image Preprocessing**
   - Grayscale conversion
   - Gaussian blur
   - Canny edge detection

2. **Region of Interest (ROI)**
   - Masking irrelevant parts of the image

3. **Hough Line Transform**
   - Detecting lane lines

4. **Line Averaging**
   - Drawing left and right lane lines clearly

5. **Overlaying**
   - Displaying lane lines on the original image/video

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/road-lane-detection.git

2. Open Jupyter Notebook:
cd road-lane-detection
jupyter notebook

3. Run the notebook LaneDetection.ipynb.

)

🚀 Future Improvements
 Add support for curved lane detection

 Handle lane merging or diverging

 Integrate deep learning models (like CNNs)

 Enhance performance for real-time driving

