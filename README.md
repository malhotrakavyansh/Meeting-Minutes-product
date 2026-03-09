# Meeting-Minutes-product

Automated pipeline to transcribe meeting audio and generate structured minutes using **Gemini** for ASR and **LLaMA-3 Instruct** for summarization, built and executed in **Google Colab**.

##  Automated Meeting Minutes Generator (Audio → Insights)

This project demonstrates an **end-to-end AI pipeline** for converting meeting audio recordings into structured minutes of meetings using modern Large Language Models.

It is designed to run seamlessly in **Google Colab** and showcases how to combine:

-  Audio transcription (ASR)
-  LLM-based analysis & summarization
-  Real-world municipal meeting data

---

##  What This Project Does

-  Takes **Denver council meeting MP3 audio**
-  Transcribes the audio using the **Gemini API**
-  Analyzes the transcript using **LLaMA-3.1 Instruct**
-  Produces **Minutes of Meeting** in clean Markdown, including:
  - Summary
  - Discussion points
  - Key takeaways
  - Action items with owners

## 🏗️ Project Structure

```text
.
├── Meeting_Minutes_product.ipynb   # Main Google Colab notebook (end-to-end pipeline)
├── README.md                       # Project documentation
└── sample_audio/                   # (Optional) Example Denver meeting MP3 files


---
`````
## Note on Notebook Rendering

 This notebook is intended to be run in **Google Colab**.  
 GitHub may not render the notebook preview correctly due to Colab widget metadata.  
 Please open it directly in Colab for the best experience.
