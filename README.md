# Garbage Detection using YOLOv8

This project uses YOLOv8 for detecting garbage in images. The model is already trained, and the training results (exp files) are provided.

---

## 📂 Project Structure

Make sure your directory is organized like this:


Garbage_Detection_YOLOv8/
│── dataset/ # Dataset (from Drive)
│── runs/ # Contains trained model (exp folder)
│── test_96.ipynb # Notebook for testing/inference
│── README.md


---

## 🔗 Resources

| Resource              | Link |
|----------------------|------|
| Dataset              | https://drive.google.com/drive/folders/1wboZ4aHr_jfAcwJaR2lDMaQHNQ2TD_23?usp=sharing |
| Trained Model (exp)  | https://drive.google.com/drive/folders/1vCkDaLS-4k8JChqKQxtuvlr88F6atXVI?usp=sharing |

---

## 📊 Model Performance

| Metric         | Score   |
|---------------|--------|
| mAP@0.5       | 0.96986 |
| mAP@0.5:0.95  | 0.87729 |
| Precision     | 0.96789 |
| Recall        | 0.94189 |

---

## ⚙️ Setup Instructions

### 1. Clone the repository

git clone <your-repo-link>
cd Garbage_Detection_YOLOv8


### 2. Install dependencies

pip install ultralytics


### 3. Download required files

Download from Google Drive and place them correctly:

- Dataset → place inside `dataset/`
- Exp folder → place inside `runs/`  
  (e.g., `runs/detect/exp/weights/best.pt`)

⚠️ Important:
- Do NOT change folder names
- Keep directory structure exactly the same as expected by the notebook
- If paths are different, update them in `test_96.ipynb`

---

## ▶️ Usage

### Run Notebook
Open and run:

test_96.ipynb

---

## 📌 Notes

- Model is already trained — no need to retrain
- Large files are hosted on Google Drive due to GitHub limits
- Make sure paths are correct, otherwise inference will fail

---
