# CLIP Semantic Difference — Understanding Changes Between Images

This project demonstrates how **OpenAI’s CLIP model** can capture the semantic difference between two images — not just what they are, but what changed.

When you subtract two image embeddings (for example, *a man with a cap* − *a man without a cap*), the resulting vector aligns with **text concepts** like “cap” or “hat”.  
This behavior shows how CLIP learns meaningful visual–semantic relationships.

---

## Overview

CLIP (Contrastive Language–Image Pretraining) learns a shared embedding space for both images and text.  
This experiment tests whether the *difference* between two image embeddings corresponds to a meaningful text concept representing the visual change between them.


## Project Structure

CLIP-Embedding-Model/
│
│
├── CLIP_Embedding_Model.ipynb
├── requirements.txt
└── README.md


---

## Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/<your-username>/clip-semantic-difference.git
cd clip-semantic-difference
pip install -r requirements.txt



