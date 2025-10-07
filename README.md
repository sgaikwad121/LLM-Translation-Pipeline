⚙️ Setup Instructions

🎥 Demo Video



I have created a short video explaining the goals and final results of this case study. You can watch it here:



🔗 Watch the Demo Video (https://www.loom.com/share/bf4276d232884beb8c33558b099f58ba?sid=0cd85e90-ae5e-4d82-8809-1cd2f11caedf)



1️⃣ Clone the Repository



git clone https://github.com/sgaikwad121/LLM-Translation-Pipeline.git

cd LLM-Translation-Pipeline





2️⃣ Create \& Activate a Virtual Environment (recommended)



python -m venv venv

source venv/bin/activate      # Linux / macOS

venv\\Scripts\\activate         # Windows





3️⃣ Install Dependencies



pip install -r requirements.txt





The requirements.txt file contains all the necessary Python libraries, including:



openai for LLM integration



chromadb for glossary retrieval



pandas and numpy for data processing



moviepy for video handling



transformers and sentencepiece for translation models



4️⃣ Configure Environment Variables

Create a .env file in the root directory:



OPENAI\_API\_KEY=your\_api\_key\_here





💡 Tip: Don’t commit .env to GitHub — keep it private.



5️⃣ Run the Notebook

Open translation\_pipeline.ipynb in Jupyter and run all cells sequentially.



6️⃣ Check Outputs

Translations and metadata are saved in translation\_results.csv.

Console logs display comparisons between baseline and glossary-enhanced translations.

