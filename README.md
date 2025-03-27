# Cold Email Generator for Services Companies

## Overview
This project is a **Cold Email Generator** designed for **services companies** to automate outreach to potential clients. It utilizes **Groq**, **LangChain**, and **Streamlit** to extract job listings from a company's careers page and generate personalized cold emails. The tool integrates a **vector database** to provide relevant portfolio links, increasing the chances of a successful pitch.

## Use Case Example
Imagine **Nike** is hiring a **Principal Software Engineer**, investing time and resources in recruiting, onboarding, and training. **Atliq**, a software development company, can offer a **dedicated software development engineer** as an alternative. A business development executive (**Mohan**) from **Atliq** can use this tool to reach out to **Nike** with a personalized cold email.

## Features
- Extracts **job listings** from a given **careers page URL**.
- Generates **customized cold emails** targeting specific job postings.
- Integrates a **vector database** to fetch relevant **portfolio links**.
- Uses **Groq API** for AI-powered text generation.
- Built with **LangChain** for efficient data processing.
- Simple **Streamlit UI** for ease of use.

## Getting Started
### 1. Prerequisites
- **Python 3.8+**
- **Groq API Key** (Obtain from [Groq Console](https://console.groq.com/keys))
- **Required dependencies** (see `requirements.txt`)

### 2. Installation
```sh
# Clone the repository
git clone https://github.com/yourusername/cold-email-generator.git
cd cold-email-generator

# Install dependencies
pip install -r requirements.txt
```

### 3. Configure API Keys
1. Get your **Groq API Key** from [here](https://console.groq.com/keys).
2. Update `app/.env` with your **GROQ_API_KEY**:
   ```
   GROQ_API_KEY=your_api_key_here
   ```

### 4. Run the Application
```sh
streamlit run app/main.py
```
### 5. Architecture Diagram
![architecture](https://github.com/user-attachments/assets/681c6156-7152-4cea-8455-d41c46ca0023)

## How It Works
1. **Enter the careers page URL** of the target company.
2. The app **extracts job listings** from the page.
3. It **analyzes the job descriptions** to tailor cold emails.
4. The system fetches **relevant portfolio links** from the vector database.
5. A **personalized cold email** is generated and displayed.
6. Copy the email and use it for outreach!

## Example Output
**Input:** Careers page URL of Nike

**Generated Cold Email:**
![img](https://github.com/user-attachments/assets/cfcd6137-6ab0-4e72-b555-02e1d54e454b)


## Technologies Used
- **Groq API** – AI-powered email generation
- **LangChain** – Job listing extraction and processing
- **Vector Database** – Storing and fetching portfolio links
- **Streamlit** – Interactive UI
- **BeautifulSoup** – Web scraping for job listings



