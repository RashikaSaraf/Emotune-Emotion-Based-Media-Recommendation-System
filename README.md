# 🎭 Emotune: Emotion-Based Media Recommendation System

Emotune is a real-time emotion recognition system that recommends personalized media content based on your facial expressions. Leveraging deep learning and computer vision, it detects your current mood and serves up mood-aligned videos or songs, creating a truly adaptive and empathetic user experience.

---

## 🧠 Features

* 🎥 Real-time facial emotion recognition using OpenCV and Haar cascades.
* 🤖 Deep learning inference with a trained model in `.json` format.
* 📺 Dynamic media recommendations (music/videos) based on detected emotions.
* 🌐 Streamlit Web Interface for quick deployment and interaction.

---

## 🚀 Live Demo

(Optional: Add a Streamlit Cloud, Hugging Face, or AWS link here if deployed)

---

## 📸 Emotion Detection Categories

| Emotion      | Media Recommendation Type       |
| :----------- | :------------------------------ |
| Happy 😀     | Upbeat songs, motivational videos |
| Sad 😢       | Relaxing or feel-good content   |
| Angry 😠     | Calming music, mindfulness clips|
| Neutral 😐   | Popular or trending picks       |
| Surprise 😮  | Exciting or humorous media      |
| Fear 😨      | Gentle, comforting videos       |

---

## 🧰 Tech Stack

* **Frontend**: Streamlit
* **Backend**: Python
* **Computer Vision**: OpenCV, Haar Cascades
* **Model Inference**: Keras (JSON format)
* **Media Handling**: Web links mapped to emotion categories

---

---

## 🔧 Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/emotune.git](https://github.com/yourusername/emotune.git)
    cd emotune
    ```

2.  **Create a virtual environment and install dependencies**
    ```bash
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
    pip install -r requirements.txt
    ```

3.  **Run the app**
    ```bash
    streamlit run app.py
    ```

4.  **To use webcam emotion detection:**
    ```bash
    python real_time_tester.py
    ```

---

## 🧪 Sample Use Cases

* 🎧 Mental health & wellness apps
* 📺 Smart TVs recommending content
* 🤖 Companion bots with emotion-awareness
* 🎓 Educational tools adapting to student mood

---

## 🧠 Model Training (Coming Soon)

Currently, the model is pre-trained and included as `emotiondetector.json`. Future versions may include:

* Custom dataset integration
* Real-time retraining
* Emotion intensity detection

---

## ✨ Showcase Highlights

* ⚡ Real-time feedback loop
* 💡 Emotion-aware user experience
* 🌍 Simple interface deployable anywhere

---

## 📩 Contact

Feel free to reach out for collaboration, feedback, or hiring!

**Rajas Samse**
* 📧 [samserajas@gmail.com](mailto:samserajas@gmail.com)
* 🔗 [LinkedIn](https://www.linkedin.com/in/rajas-samse-a09b4724a/)


---

## 🪪 License

MIT License. See `LICENSE` for more information.