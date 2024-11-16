# **Project Title: Resume Evaluator using Generative AI**

## **Project Description**
This Streamlit application evaluates resumes against job descriptions using Google's Generative AI (`gemini-pro`). The tool acts like an advanced Applicant Tracking System (ATS), offering tailored feedback for improving resumes based on competitive job market requirements.

---

## **Features**
- Upload a PDF resume.
- Input job descriptions for analysis.
- Generates personalized recommendations to improve the resume.
- Powered by Google's Generative AI and integrated with Streamlit.

---

## **Setup Instructions**

### **1. Prerequisites**
Ensure the following tools and libraries are installed:
- Python 3.8+
- Streamlit
- PyPDF2
- `python-dotenv`
- Google Generative AI Python SDK (`google.generativeai`)

### **2. Clone the Repository**
```bash
git clone <repository-url>
cd <repository-folder>
```

### **3. Install Dependencies**
Run the following command to install required libraries:
```bash
pip install -r requirements.txt
```

Create a `requirements.txt` file if it does not exist:
```
streamlit
google-generativeai
PyPDF2
python-dotenv
```

### **4. Set Up Environment Variables**
Create a `.env` file in the root directory and add your Google API key:
```
GOOGLE_API_KEY=your_google_api_key_here
```

### **5. Running the Application**
Launch the Streamlit application:
```bash
streamlit run app.py
```

### **6. How to Use**
1. Open the application in your browser (`http://localhost:8501` by default).
2. Upload your resume in PDF format.
3. Input the job description into the text field.
4. Click the "Evaluate" button to generate feedback.

---

## **Folder Structure**
```
project-folder/
│
├── app.py                # Main application file
├── requirements.txt      # Python dependencies
├── .env                  # Environment variables (not included in the repository)
└── README.md             # Project documentation
```

---

## **Contributing**
Feel free to fork the repository and submit pull requests for enhancements or bug fixes.

---

## **License**
This project is licensed under the MIT License.

