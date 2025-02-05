# Offside Detection GUI - Partial Field 🚀

A football offside detection application built with Python, Tkinter, OpenCV, PyTorch, and Torchvision.  
This tool uses Mask R-CNN to detect players, applies color clustering to classify teams, and visualizes the offside line based on a partial field homography.  
The user interface supports both English and Persian.

---

## ✨ Key Features
- **Multilingual Interface:** Easily toggle between English and Persian.
- **Player Detection:** Uses Mask R-CNN (MaskRCNN_ResNet50_FPN_V2) from Torchvision to detect players.
- **Team Classification:** Utilizes KMeans clustering to differentiate teams based on dominant colors.
- **ROI & Homography:** Allows selecting a region of interest and four reference points for partial field calibration.
- **Offside Line Visualization:** Draws the offside line with adjustable offset, thickness, color, and zoom.
- **User Interaction:** Provides GUI elements to load images, select ROI, detect and select players, and adjust offside line parameters.

---

## 📊 Results and Output Images

### Sample Output

#### Processed Image
![Processed Image](Offside-Detection-In-Football/01-(Inp).jpg)

#### Offside Line Visualization
![Offside Line](Offside-Detection-In-Football/01-(Out).jpg)

🛠 Installation & Setup
Prerequisites
Python 3.8+
A GPU is optional (CPU is sufficient for most tasks)
Required Libraries
Create a file named requirements.txt with the following content:
