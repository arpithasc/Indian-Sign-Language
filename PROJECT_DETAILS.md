## Indian Sign Language Translator – Detailed Project Description

## 🧩 Problem Statement

Millions of people in India rely on Indian Sign Language (ISL) to communicate, but most of the population is not trained in ISL. This creates a communication barrier between deaf individuals and the hearing community. This project aims to reduce that gap using speech recognition and visual gesture mapping.

---

## 🎯 Objectives

- Convert spoken English sentences to corresponding ISL signs.
- Provide an easy-to-use application for real-time communication.
- Promote inclusivity using AI-powered assistive tech.

---

## 🏗️ System Architecture

1. **Speech Recognition Module**  
   - Uses Google Speech API to transcribe spoken English.

2. **Text Processing Unit**  
   - Filters keywords and removes stopwords.
   - Maps words to corresponding ISL gesture images.

3. **Gesture Display Engine**  
   - Displays pre-stored sign images or animations for each mapped word.
   - Can be extended to avatar-based animations.

4. **Frontend Interface**  
   - Built using Tkinter or Streamlit.
   - Takes voice input and displays gesture sequence.
  
   ## 🧠 Challenges Faced

- Lack of standardized ISL datasets
- Dealing with ambiguous or grammatically complex spoken input
- Mapping grammar-free ISL order from English grammar
