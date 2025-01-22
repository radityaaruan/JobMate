# JobMate: AI-Powered Job Search Assistant

**JobMate** is an AI-powered job search assistant designed to simplify the job hunting process by delivering personalized job recommendations. This project combines intelligent data processing, interactive user interfaces, and exploratory data analysis (EDA) to create a seamless experience for job seekers.

## Key Features

1. **Job Search Assistant**:
   - Interactive chatbot interface to collect user preferences and deliver job recommendations.
   - Leverages OpenAI's GPT to analyze preferences and extract insights from user conversations and resumes.
   - Integrates MongoDB to store and query job-related data.

2. **Resume Parsing**:
   - Extracts skills from uploaded resumes (PDF format) using OpenAI's GPT.
   - Combines parsed skills with user-provided inputs for accurate job matching.

3. **Job Categorization and Analysis**:
   - Categorizes job listings into key domains like Data Analyst, Data Scientist, Data Engineer, and Freelance.
   - Analyzes job demand trends, top skills required, and the most active hiring companies.

4. **Exploratory Data Analysis (EDA)**:
   - Visualizes job distributions, demand for specific roles, and location-based opportunities using Matplotlib and Seaborn.
   - Identifies top companies hiring and most in-demand skills in the tech industry.

5. **Streamlit-based Interface**:
   - Clean, intuitive web interface with a sidebar navigation menu for switching between JobMate and EDA features.
   - Displays dynamic visualizations and allows user interaction for a personalized experience.

---

## File Structure

- **`app.py`**: Main entry point for the application, managing navigation between JobMate and EDA.
- **`chatme.py`**: Implements the AI-powered job search assistant with chat-based interaction and resume parsing.
- **`eda.py`**: Handles the EDA functionality, providing visual insights into job trends and data.
- **`job_data.csv`**: Contains job listing data used for analysis and recommendations.

---

## Getting Started

### Prerequisites
- Python 3.9 or higher.
- Libraries: `streamlit`, `openai`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `pymongo`, `PyPDF2`, `plotly`.

### Installation
1. Clone the repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
