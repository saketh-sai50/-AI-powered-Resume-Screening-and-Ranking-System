# AI Resume Screening & Candidate Ranking System  

## 📌 Project Overview  
The **AI Resume Screening & Candidate Ranking System** is a web-based application that helps recruiters efficiently screen and rank resumes based on job descriptions. It uses **Natural Language Processing (NLP)** techniques, such as **TF-IDF Vectorization** and **Cosine Similarity**, to match resumes against job descriptions and rank candidates accordingly.

## 🚀 Features  
✅ Upload multiple resumes in **PDF format**  
✅ Enter a **job description** for matching  
✅ Automatically **extract text** from resumes  
✅ Use **TF-IDF & Cosine Similarity** for ranking  
✅ Display ranked resumes with similarity scores  

## 🛠️ Technologies Used  
- **Python**  
- **Streamlit** (for UI)  
- **PyPDF2** (for extracting text from PDF resumes)  
- **Scikit-learn** (for TF-IDF and similarity calculation)  
- **Pandas** (for data handling)  
## 🏃‍♂️ How to Run the Project  
### 1️⃣ Install Dependencies  
First, install the required libraries using:  
```bash
pip install -r requirements.txt
2️⃣ Run the Streamlit App
streamlit run Screening_app.py
3️⃣ Upload Resumes & Rank Candidates
Enter a job description in the text area.
Upload PDF resumes of candidates.
View ranked resumes based on matching scores.
📌 How It Works
Extract Text: The app extracts text from uploaded PDF resumes.
Vectorize Data: It converts job descriptions & resumes into numerical vectors using TF-IDF.
Compute Similarity: Uses Cosine Similarity to compare resumes with the job description.
Rank Candidates: Resumes are sorted based on relevance scores.
📧 Contact
For any issues or improvements, feel free to reach out! 
