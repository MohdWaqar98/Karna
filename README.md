# 🎙️ Real-Time Speech-to-Text Transcriber (Multi-Indian Language) using Python

This project is a **real-time speech-to-text converter** supporting 10+ Indian languages, built using **Python**, **Jupyter Notebook**, and the **Google Web Speech API**. It provides a professional, clean, and easy-to-use interface without any paid APIs or GUI clutter.

---

## ✅ Features

- 🔴 Real-time voice recognition with Start/Stop control
- 🇮🇳 Supports multiple Indian languages (Hindi, Gujarati, Tamil, etc.)
- 🧠 Built with Python libraries: `speech_recognition`, `ipywidgets`, `pyaudio`
- 📦 No paid keys or cloud services required
- 📓 Runs in Jupyter Notebook (Anaconda compatible)

---

## ⚙️ Setup Instructions

### 🔧 Dependencies (Install in Anaconda Prompt)

```bash
conda create -n transcriber python=3.9 -y
conda activate transcriber

pip install SpeechRecognition
pip install ipywidgets
pip install pipwin
pipwin install pyaudio
````

---

## ▶️ How to Run

```bash
# Step 1: Open Anaconda Prompt
# Step 2: Navigate to project folder
cd path\to\project-folder

# Step 3: Launch Jupyter
jupyter notebook
```

* Open the notebook: `RealTime_Transcriber.ipynb`
* Select the language from dropdown
* Click **Start** and speak, then click **Stop**
* Transcription appears in real time

---

## 🗂️ Project Structure

```
├── RealTime_Transcriber.ipynb     # Main notebook file
├── README.md                      # Project documentation
```

---

## 🧠 Supported Languages

| Language     | Code  |
| ------------ | ----- |
| Hindi        | hi-IN |
| Gujarati     | gu-IN |
| Marathi      | mr-IN |
| Bengali      | bn-IN |
| Punjabi      | pa-IN |
| Tamil        | ta-IN |
| Telugu       | te-IN |
| Kannada      | kn-IN |
| Malayalam    | ml-IN |
| Urdu         | ur-IN |
| English (IN) | en-IN |
| English (US) | en-US |

---

## 🛠️ Troubleshooting

* ❌ **`pyaudio` fails to install**:
  Run:

  ```bash
  pip install pipwin
  pipwin install pyaudio
  ```

* 🎙️ **Mic not working**:
  Make sure your system mic permissions are enabled.

* 📶 **Slow response**:
  Google Web Speech API requires internet. Use stable WiFi.

---

## 🙌 Credits

* Developed using:

  * [Python](https://www.python.org)
  * [Google Web Speech API](https://www.google.com/intl/en/chrome/demos/speech.html)
  * `speech_recognition`, `ipywidgets`, `pyaudio`

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) – free for academic and personal use.
