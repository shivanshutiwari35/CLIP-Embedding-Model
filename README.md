#  CLIP Semantic Difference — Understanding Changes Between Images

This project demonstrates how **OpenAI’s CLIP model** can capture the *semantic difference* between two images — not just what they are, but **what changed**.

It shows that when you subtract two image embeddings (e.g., *a man with a cap* − *a man without a cap*), the resulting vector aligns with **text concepts** like “cap” or “hat”.

---

##  What’s Inside
- **CLIP EMBEDDING MODEL.ipynb** → main Python script performing the experiment  
- **requirements.txt** → minimal dependencies  
- **README.md** → this file  

---

##  Setup & Run

### 1️ Clone and Install
```bash
git clone https://github.com/shivanshutiwari35/CLIP-Embedding-Model.git
cd CLIP-Embedding-Model
pip install -r requirements.txt

cap        → 0.45
hat        → 0.39
helmet     → 0.06
glasses    → 0.03

The model identifies “cap” and “hat” as the top matches — proving that the difference between the two image embeddings corresponds to the concept that changed.

Conceptual Insight

This project explores visual-semantic arithmetic in CLIP’s shared embedding space.

Just like:

King – Man + Woman ≈ Queen

…we now have:

(Man with Cap) – (Man without Cap) ≈ Cap

Referenced in:

ZeroCap: Zero-Shot Image-to-Text Generation for Visual-Semantic Arithmetic (CVPR 2021)

Embedding Arithmetic of Multimodal Queries for Image Retrieval (CVPR 2022)

Visualization

Run inside Jupyter/Colab to view both images side-by-side and similarity scores plotted.
