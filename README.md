# Group 7 – Fake News Detection Beyond Source Cues
NLP – Section 3 · Option 4 · Arwa Alqahtani, Jana Algahtani, Mashael Alqahtani

**Question:** Which method — TF-IDF + logistic regression or pretrained MiniLM sentence embeddings + logistic regression — keeps a higher macro F1 when source-identifying cues are removed?

## How to run
1. Open `Group7_Final.ipynb` in Google Colab.
2. Runtime → Change runtime type → **T4 GPU**.
3. Runtime → **Run all**. No upload is needed: the ISOT data are downloaded from Kaggle automatically (about 15–20 minutes).
4. Use the **Try it** cell to classify your own news text.

## Files
- `Group7_Final.ipynb` – final merged notebook (Setup, Data, Method 1, Method 2, Results, Try it, Sources)
- `Group7_Data_Arwa.ipynb` – Arwa's data section (development version)
-  `Group7_Method1_Jana.ipynb` – Jana's Method 1: TF-IDF + logistic regression (development version)
- `Group7_Method2_Mashael.ipynb` – Mashael's Method 2: MiniLM + logistic regression (development version)

Data: ISOT Fake News Dataset – https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
