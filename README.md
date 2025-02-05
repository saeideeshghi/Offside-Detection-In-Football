# Offside Detection GUI - Partial Field 🚀

A desktop application that performs offside detection in football images using advanced image processing techniques, including player detection with Mask R-CNN, team classification via color clustering, and homography for perspective transformation. The user interface is built with Tkinter and supports both English and Persian languages.

## ✨ Key Features
- **Player Detection:** Utilizes Mask R-CNN for detecting players in football images.
- **Team Classification:** Uses KMeans clustering on detected players' colors to classify teams.
- **ROI Selection:** Allows users to select regions of interest and reference points for homography.
- **Offside Line Visualization:** Computes and draws the offside line based on player positions and field perspective.
- **Interactive GUI:** User-friendly interface built with Tkinter, with controls for zoom, offset adjustment, and line customization.
- **Multilingual Support:** Switch between English and Persian easily.

## 📊 Sample Output
Below are some sample outputs from the application:

#### Processed Image
![Processed Image](Offside-Detection-In-Football/01-(Inp).jpg)

#### Offside Line Visualization
![Offside Line](Offside-Detection-In-Football/01-(Out).jpg)
---

*Note: Replace `sample_outputs/sample_original.jpg` and `sample_outputs/sample_offside.jpg` with the actual paths or URLs of your output images.*

## 🛠 Installation & Setup

### Prerequisites
- Python 3.8+
- GPU (optional; CPU is sufficient for basic usage)

### Required Libraries

Create a file named `requirements.txt` with the following content:

```txt
opencv-python
numpy
torch
torchvision
Pillow
scikit-learn
tkinter

```
Then install the dependencies via pip:

```txt
pip install -r requirements.txt
```
# ▶️ Running the Application
Run the main script:
```txt
python Final11.py
```
# 📂 Project Structure

```txt
.
├── main.py                 # Main application script (OffsideGUI and related classes)
├── requirements.txt        # List of required libraries
├── sample_outputs/         # Folder containing sample output images
└── README.md               # Project documentation (this file)
```

# 🔗 References

- Mask R-CNN Documentation: https://pytorch.org/vision/stable/models.html#object-detection
- OpenCV Documentation: https://docs.opencv.org/
- Tkinter Documentation: https://docs.python.org/3/library/tkinter.html
- Scikit-learn Documentation: https://scikit-learn.org/
---

# 🤝 Contributing
Contributions are very welcome! To contribute:

- 1.Fork the repository.
- 2.Create a new branch (e.g., git checkout -b feature/YourFeature).
- 3.Commit your changes (e.g., git commit -m 'Add Your Feature').
- 4.Push to your branch (git push origin feature/YourFeature).
- 5.Open a Pull Request.

#📜 License
---
This project is licensed under the MIT License.

