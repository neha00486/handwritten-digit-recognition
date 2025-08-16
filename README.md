
---

````markdown
# 🖊️ Handwritten Digit Recognition

A simple deep learning project that recognizes handwritten digits (0–9) using the **MNIST dataset** and **TensorFlow/Keras**.  
You can also test the trained model on your own handwritten digit images created in Paint.

---

## 📌 Features
- Trains a neural network on the MNIST dataset.
- Achieves ~97% accuracy.
- Saves the trained model (`handwritten.keras`).
- Loads custom digit images from the `digits/` folder for prediction.
- Uses **TensorFlow, NumPy, OpenCV, and Matplotlib**.

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/neha00486/handwritten-digit-recognition.git
   cd handwritten-digit-recognition
````

2. Install dependencies:

   ```bash
   pip install tensorflow numpy opencv-python matplotlib
   ```

3. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

---

## ▶️ Usage

### 1. Train the model

If you want to retrain:

```bash
python main.py
```

### 2. Test with your own images

1. Open **Paint** (or any drawing tool) and draw digits (0–9).
2. Resize them to **28x28 pixels**.
3. Save them inside the `digits/` folder as:

   ```
   digits/digit1.png
   digits/digit2.png
   digits/digit3.png
   ```
4. Run:

   ```bash
   python main.py
   ```

   The program will load each image, predict the digit, and display it.

---

## 📂 Project Structure

```
handwritten-digit-recognition/
│── main.py              # Training + testing script
│── handwritten.keras    # Saved trained model
│── digits/              # Folder with test digit images
│── README.md            # Project documentation
```

---

## 📊 Example Output

```
this digit is probably a 7
this digit is probably a 2
this digit is probably a 9
```

---