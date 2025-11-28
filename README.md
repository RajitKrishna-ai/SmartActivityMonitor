
---

## 🛠️ How to Run, Use VidSense

1. **Clone this repository**  
2. **Install dependencies*** 
3. Follow notebooks sequentially (or start from your last checkpoint):  
   - Generate or add raw videos  
   - Extract frames → features → build dataset → train model → evaluate → inference  
4. To test on new video: place video in `new_videos/`, then run `inference_Predict.ipynb → predicted activity will be printed.

---

## 📊 Results & Performance

- Successfully recognizes activities: walking, running, sitting, falling.  
- Provides confusion matrix & classification report for model evaluation (see `evaluation and confusion matrix.ipynb`).  
- Pipeline is modular — you can retrain or extend with more data, new classes, or real‑world videos.

---

## 📚 Tech Stack

- Python  
- TensorFlow (CNN + LSTM)  
- OpenCV (video processing)  
- NumPy, scikit‑learn (data handling, splitting, evaluation)  
- Jupyter Notebook (step‑by‑step workflow)  

---

## 🌍 Why it’s Relevant here for UAE Employers / Recruiters

- Works for **safety, surveillance, smart buildings, elder care** — all highly relevant in UAE’s growing smart‑city and healthcare/retail sectors.  
- Shows **full‑stack ML skills** — not just models, but end-to-end data processing, engineering discipline, reproducible code.  
- Clear project structure and documentation — easy for future collaborators or stakeholders to understand and build upon.  

---

## 🚀 Next Steps (Future Work)

- Add support for **real‑time webcam / CCTV input** for live activity detection.  
- Extend to **multi-person tracking or more activity classes**.  
- Integrate **alert/notification systems** (e.g., for falls or hazardous activities).   
