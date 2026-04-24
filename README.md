# VisionShade
# 😎 Shadeify – Sunglasses Filter using OpenCV

## Project Overview
This project demonstrates how to overlay a sunglasses image onto a human face using **OpenCV** and **NumPy**. It showcases fundamental image processing techniques like masking, blending, and region-based manipulation.

---

## Technologies Used
- Python 3.x  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

---

## Project Structure


---

## How It Works

### 1. Load Images
- Load the face image (`passportpic.jpeg`)
- Load sunglasses image (`sunglass.png`) with alpha channel

### 2. Resize Sunglasses
- Adjust sunglasses size to fit the face

### 3. Extract Channels
- RGB channels (color)
- Alpha channel (mask)

### 4. Apply Overlay
- Use Region of Interest (ROI)
- Blend images using mask:
  - Background × (1 - mask)
  - Foreground × mask

### 5. Generate Output
- Replace ROI with blended result
- Display final image

---

## Output

### 🔹 Original Image
<img width="634" height="776" alt="image" src="https://github.com/user-attachments/assets/0a4ee551-4a1c-4be9-9bfc-1a371638b67d" />

### 🔹 Final Output (With Sunglasses)
<img width="640" height="782" alt="image" src="https://github.com/user-attachments/assets/736da93e-9e8e-45b3-b6e7-51133a07d008" />

---

## Key Concepts Learned
- Image slicing using NumPy  
- Alpha channel masking  
- ROI (Region of Interest)  
- Image blending  
- Basic computer vision workflow  

---

## How to Run

1. Install dependencies:
```bash
pip install opencv-python numpy matplotlib
