🧠 LLM-Based Translation Pipeline with Glossary Retrieval
📘 Overview

This project demonstrates an LLM-driven translation system that integrates a glossary-based retrieval mechanism.
It compares translation quality with vs. without glossary enhancement, enabling domain-consistent translation results.

✨ Features

📚 Glossary Vector Storage: Terms are stored and retrieved via embeddings using ChromaDB.

🔍 Automatic Glossary Retrieval: Relevant glossary entries fetched for each input segment.

⚙️ Dual Translation Modes:

Baseline Translation – Standard LLM translation.

Glossary-Enhanced Translation – Contextual translation with glossary guidance.

🌍 Supported Directions: EN → FR, EN → IT, EN → JP (extendable).

💾 Result Logging: Output translations and metadata stored in translation_results.csv.

📂 File Structure
LLM_Translation_Pipeline/
├── translation_pipeline.ipynb      # Main notebook
├── glossary.csv                    # Glossary dataset
├── translation_results.csv          # Saved translation output
├── README.md                       # Project documentation
├── Approach_and_Results.pdf         # Summary of approach and outcomes
├── demo_video.mp4                   # Optional demonstration
├── requirements.txt                 # Python dependencies
├── .env.example                     # Template for API key
└── .gitignore                       # Files to ignore in Git

⚙️ Setup Instructions
1️⃣ Install Dependencies
pip install openai chromadb pandas

2️⃣ Configure Environment

Create a .env file in the root directory with your OpenAI API key:

OPENAI_API_KEY=your_api_key_here


💡 Tip: Don’t commit .env to GitHub — keep it private!

3️⃣ Run the Notebook

Open translation_pipeline.ipynb in Jupyter and run all cells in order.

4️⃣ Check the Outputs

Translations are saved to translation_results.csv

Console logs show comparisons between baseline and glossary-enhanced translations.

🧾 Deliverables

Notebook: translation_pipeline.ipynb

Glossary file: glossary.csv

Results: translation_results.csv

Report: Approach_and_Results.pdf

README.md (this file)

Demo video (optional but recommended)

🧠 Future Enhancements

Add BLEU/COMET scoring for automatic quality evaluation.

Support more languages and dynamic glossary upload.

Integrate UI for live translation demos.

👨‍💻 Author

Shivaji Gaikwad
Client Program Manager – Thebigword India Pvt. Ltd.
🔗 LinkedIn Profile   https://www.linkedin.com/in/shivaji-gaikwad-3821a4a2/