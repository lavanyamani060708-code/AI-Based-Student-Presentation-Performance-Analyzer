# 🎤 AI-Based Student Presentation Performance Analyzer

## 📌 Project Overview

The **AI-Based Student Presentation Performance Analyzer** is a Text and Speech Analysis (TSA) application developed using **Python, Speech Recognition, NLP, and Gradio**.

The system analyzes a student's presentation audio and provides useful performance metrics such as:

* Speech-to-text transcription
* Speaking speed
* Vocabulary usage
* Filler word detection
* Fluency analysis
* Overall presentation score
* Performance level
* Personalized improvement suggestions

The project runs completely in **Google Colab** and generates a public **Gradio URL** for accessing the application.

---

## 🎯 Objectives

* Analyze student presentation speech automatically.
* Convert speech into text using an AI speech recognition model.
* Calculate speaking speed in Words Per Minute (WPM).
* Identify commonly used filler words.
* Analyze vocabulary usage.
* Generate an overall presentation score.
* Provide suggestions to improve presentation skills.

---

## ✨ Features

### 🎙️ Speech Input

Users can upload or record presentation audio.

### 📝 Speech-to-Text

The system converts the student's speech into readable text.

### ⏱️ Speaking Speed Analysis

The system calculates WPM and checks whether the speaking speed is appropriate.

### 🔤 Vocabulary Analysis

The system analyzes total words and unique words used by the speaker.

### 🗣️ Filler Word Detection

Common filler words such as:

* Um
* Uh
* Erm
* Like
* Actually
* Basically
* You know

are detected.

### 📊 Performance Score

The system generates scores for:

* Speaking Speed
* Vocabulary
* Fluency

and calculates an overall presentation score.

### 💡 Improvement Suggestions

The system provides recommendations based on the detected weaknesses.

---

## 🛠️ Technologies Used

* Python
* Faster-Whisper
* Natural Language Processing
* Speech Recognition
* Gradio
* Google Colab

---

## 🔄 System Workflow

```text
Student Speech
      ↓
Audio Input
      ↓
Speech Recognition
      ↓
Speech-to-Text
      ↓
Text Preprocessing
      ↓
NLP Analysis
      ↓
 ┌───────────────┐
 │ Speed Analysis│
 │ Vocabulary    │
 │ Filler Words  │
 │ Fluency       │
 └───────────────┘
      ↓
Performance Score
      ↓
Suggestions
      ↓
Final Report
```

---

## ▶️ How to Run

### Step 1: Open Google Colab

Open:

https://colab.research.google.com/

### Step 2: Create a New Notebook

Create a new Python notebook.

### Step 3: Paste the Complete Code

Copy the provided project code and paste it into **one Colab cell**.

### Step 4: Run the Cell

Click the **Run** button.

The required libraries and Whisper model will be installed automatically.

### Step 5: Open the Gradio URL

After execution, you will get a URL similar to:

```text
https://xxxx.gradio.live
```

Open the URL in your browser.

### Step 6: Upload Audio

Upload or record your presentation speech.

### Step 7: View Results

The system displays:

* Transcript
* Duration
* Word count
* Speaking speed
* Vocabulary score
* Filler words
* Fluency score
* Overall score
* Performance level
* Suggestions

---

## 📊 Example Output

```text
Presentation Analysis

Duration: 65 seconds
Total Words: 135
Speaking Speed: 124 WPM

Vocabulary Score: 82/100
Filler Word Score: 90/100
Speed Score: 100/100

Overall Score: 91/100

Performance Level:
Excellent

Suggestions:
✓ Maintain the current speaking speed.
✓ Continue using varied vocabulary.
✓ Reduce unnecessary filler words.
```

---

## 🎓 TSA
