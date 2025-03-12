# 📌 ImageEmbedder: AI-Powered Object Embedding
[![Open in Streamlit by Eesha Tariq](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://image-embedder-using-deeplearning.streamlit.app/)


## 🌟 Overview
**ImageEmbedder** is a Streamlit-based web app that allows users to seamlessly embed objects into images using AI. It utilizes **CLIP (ViT-L/14) from Hugging Face** to intelligently determine the **best placement** for objects based on semantic similarity.


## 🛠 Features
✅ Upload a **background image** and an **object image**
✅ Uses **CLIP model** to find the **optimal placement** for the object
✅ Supports **manual adjustments** (X, Y position & scaling)
✅ **Seamless blending** using OpenCV & PIL
✅ Web-based interface using **Streamlit**

---

## 🚀 Technologies Used
- **Python 3.x**
- **Hugging Face Transformers** (CLIP model: `openai/clip-vit-large-patch14`)
- **OpenCV** (for image processing)
- **NumPy** (for numerical operations)
- **PIL (Pillow)** (image manipulation)
- **Streamlit** (for UI)

---

## 📥 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/ImageEmbedder.git
cd ImageEmbedder
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

---

## 🎯 Usage

### 🔹 Run the Streamlit App
```sh
streamlit run app.py
```

### 🔹 Steps
1. **Upload a background image**
2. **Upload an object image (PNG with transparency recommended)**
3. Click **"Find Best Placement with CLIP"**
4. AI suggests the **best position** based on context
5. Optionally **adjust manually** & save the final image

---

## 🔬 How CLIP is Used
1. **Extracts features** from the background & object images.
2. **Computes similarity scores** across different regions.
3. **Finds the most contextually relevant area** to place the object.
4. **Blends the object** seamlessly into the background.

---

## 📌 Example Output
![Example](assets/example_output.jpg)

---

## 📌 Future Enhancements
🚀 Add **text-based placement** (e.g., "Place near the tree")
🚀 Improve **adaptive scaling** for different image sizes
🚀 Support **multiple object embeddings**

---

## 📜 License
This project is **open-source** under the MIT License.

👨‍💻 Built with ❤️ by **Eesha Tariq** during Research Internship at **University of Sharjah**
