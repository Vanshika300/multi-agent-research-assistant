🤖 Multi-Agent Research Assistant

A sophisticated Streamlit web application that demonstrates a multi-agent AI system for automating research and report generation. This project orchestrates a team of specialized AI agents (Planner, Researcher, and Writer) powered by Google Gemini to collaboratively produce comprehensive reports on any given topic.

✨ Features

Multi-Agent Architecture: Implements distinct AI agents with specific roles:

Planner Agent: Deconstructs a broad topic into a detailed, step-by-step research plan (a series of questions).

Researcher Agent: Conducts in-depth research to answer each question from the plan.

Writer Agent: Synthesizes all research findings into a cohesive, well-structured, and easy-to-read final report.

Automated Workflow: Streamlines the entire research and report writing process from topic input to final output.

Interactive Progress Tracking: Provides real-time status updates on each agent's activity within the Streamlit UI.

Viewable Intermediate Results: Allows users to inspect the generated research plan and individual findings before the final report.

Generative AI Core: Leverages Google Gemini 2.0 Flash for all AI-driven tasks, demonstrating advanced natural language processing and generation capabilities.

User-Friendly Interface: Built with Streamlit for an intuitive and engaging user experience.

🚀 Technologies Used

Python

Streamlit: For building the interactive web interface.

Google Generative AI (Gemini 2.0 Flash): The core LLM powering all agent functionalities.

python-dotenv: For secure management of API keys.

json: For structured communication (JSON parsing) between agents, especially for the Planner.

📸 Screenshots

Main Interface & Topic Input:
A screenshot showing the initial application interface with the topic input field.

Planning Phase & Research Plan:
A screenshot showing the status of the Planner Agent and the generated research plan.

Researching Phase & Findings:
A screenshot displaying the progress of the Researcher Agent and a view of the individual research findings.

Final Report:
A screenshot of the generated final summary report.

⚙️ How to Run Locally
Follow these steps to set up and run the Multi-Agent Research Assistant on your local machine.

1. Prerequisites
Python 3.8+: Ensure you have Python installed.

Google Gemini API Key: Obtain an API key from Google AI Studio.

2. Clone the Repository
git clone https://github.com/your-username/multi-agent-research-assistant.git
cd multi-agent-research-assistant

(Replace your-username with your actual GitHub username.)

3. Configure API Key
Create a file named .env in the root directory of your project (the same directory as app.py). Add your Google Gemini API key to it:

GOOGLE_API_KEY="YOUR_ACTUAL_GOOGLE_GEMINI_API_KEY"

Important: Replace "YOUR_ACTUAL_GOOGLE_GEMINI_API_KEY" with your real key. This file is ignored by Git and will not be uploaded to GitHub, keeping your key secure.

4. Install Dependencies
It's highly recommended to use a virtual environment:

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install required Python packages
pip install -r requirements.txt

5. Run the Application
Once all dependencies are installed and your .env file is configured, run the Streamlit application from your terminal:

streamlit run app.py

This command will open the application in your web browser, usually at http://localhost:8501.

📧 Contact

Feel free to reach out if you have any questions or feedback!

Email: vanshikashukla065@gmail.com

LinkedIn: linkedin.com/in/vanshika-shukla30
