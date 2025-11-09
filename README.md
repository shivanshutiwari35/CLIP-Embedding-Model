#  CLIP Semantic Difference — Understanding Changes Between Images

This project demonstrates how **OpenAI’s CLIP model** can capture the *semantic difference* between two images — not just what they are, but **what changed**.

It shows that when you subtract two image embeddings (e.g., *a man with a cap* − *a man without a cap*), the resulting vector aligns with **text concepts** like “cap” or “hat”.

---

##  What’s Inside
- **clip_diff.py** → main Python script performing the experiment  
- **requirements.txt** → minimal dependencies  
- **README.md** → this file  

---

##  Setup & Run

### 1️ Clone and Install
```bash
git clone https://github.com/<your-username>/clip-semantic-difference.git
cd clip-semantic-difference
pip install -r requirements.txt
