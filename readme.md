# Review Analyst – AI-Powered Customer Review Analysis

## 📌 Project Overview

**Review Analyst** is an AI-powered customer review analysis system that uses **Google Gemini, LangChain, and Pydantic** to analyze customer feedback and generate meaningful insights.

The system processes customer reviews, identifies their sentiment, extracts positive and negative aspects, detects customer emotions, and automatically generates personalized email responses based on the customer's experience.

This project demonstrates how Large Language Models (LLMs) and structured output parsing can automate customer feedback analysis and improve customer relationship management.

## 🚀 Key Features

- **Sentiment Analysis:** Classifies customer reviews into Positive, Negative, or Neutral categories.
- **Review Summarization:** Generates concise summaries of customer experiences.
- **Positive & Negative Feedback Extraction:** Identifies key strengths and weaknesses mentioned in reviews.
- **Emotion Detection:** Identifies emotions expressed by customers, such as satisfaction, frustration, disappointment, and excitement.
- **Automated Email Generation:** Generates professional, context-aware email responses based on customer sentiment.
- **Structured Output:** Uses Pydantic models to ensure consistent and structured AI-generated responses.
- **Batch Processing:** Analyzes multiple customer reviews using LangChain's mapping functionality.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Google Gemini | Large Language Model for review analysis |
| LangChain | LLM orchestration and prompt management |
| LangChain Google GenAI | Integration with Google Gemini |
| Pydantic | Structured output validation |
| Pandas | Data manipulation support |
| Python Dotenv | Environment variable management |
| Google Colab / Jupyter Notebook | Development environment |

## ⚙️ Project Workflow

1. **Input Reviews:** Provide customer reviews as text.
2. **Prompt Engineering:** A custom LangChain prompt instructs the LLM to analyze customer feedback.
3. **LLM Processing:** Google Gemini processes each review and understands its context.
4. **Structured Output:** Pydantic validates and structures the generated response.
5. **Sentiment & Emotion Analysis:** Extracts sentiment, emotions, positive feedback, and negative feedback.
6. **Email Generation:** Generates a professional email tailored to the customer's experience.
7. **Batch Analysis:** Processes multiple reviews and returns individual analysis results.

## 📂 Project Structure

```text
Review_Analyst/
│
├── Review_Analyst.ipynb    # Main Jupyter Notebook
│
└── README.md               # Project documentation
```

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/smiley645/Review_Analyst.git
```

Navigate to the project directory:

```bash
cd Review_Analyst
```

Install the required dependencies:

```bash
pip install -U langchain langchain-core langchain-google-genai pandas python-dotenv
```

## 🔑 API Configuration

This project uses the Google Gemini API.

1. Generate a Google Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey).
2. Open the Jupyter Notebook.
3. Execute the API configuration cell.
4. Enter your API key when prompted.

The notebook uses the API key to configure the Google Generative AI environment.

**Important:** Never share or upload your API key to GitHub. Keep it secure using environment variables or a secret manager.

## ▶️ How to Run

**Option 1: Google Colab**

1. Open the notebook from the repository.
2. Select **Open in Colab** or upload the notebook to Google Colab.
3. Install the required dependencies.
4. Configure your Google Gemini API key.
5. Run all notebook cells.
6. Review the generated analysis and email responses.

**Option 2: Jupyter Notebook**

1. Clone the repository.
2. Install the dependencies.
3. Launch Jupyter Notebook.
4. Open `Review_Analyst.ipynb`.
5. Configure your API key.
6. Execute the cells sequentially.

## 📊 Sample Analysis

**Sample Customer Review:**

"The wireless earbuds I purchased have poor sound connectivity, an uncomfortable fit, and a battery life of barely four hours instead of the advertised twelve hours."

**Expected AI Analysis:**

| Attribute | Result |
|---|---|
| Sentiment | Negative |
| Summary | Customer is dissatisfied with sound connectivity, comfort, and battery performance. |
| Positive Feedback | Timely delivery |
| Negative Feedback | Poor connectivity, uncomfortable fit, low battery life |
| Emotions | Disappointed, Frustrated, Dissatisfied |

**Generated Email:**

The system automatically generates a professional apology email acknowledging the customer's concerns and offering assistance with the return or refund process.

## 🎯 Use Cases

- E-commerce customer feedback analysis
- Customer satisfaction monitoring
- Product quality improvement
- Automated customer support
- Customer relationship management
- Business feedback analytics

## 🔮 Future Enhancements

- Integrate a CSV/Excel review upload feature.
- Build an interactive dashboard for sentiment visualization.
- Add review categorization and topic extraction.
- Generate sentiment distribution charts.
- Integrate a database to store historical customer reviews.
- Develop a web application using Streamlit or Flask.
- Add multilingual customer review analysis.

## 👨‍💻 Author

**Smiley645**

GitHub: [@smiley645](https://github.com/smiley645)

---

⭐ If you find this project useful, consider giving the repository a star!

**Built using Python, LangChain, and Google Gemini.**
