🛠️ Tech Stack
Python
LangChain
OpenAI API
Streamlit
JSON

▶️ Local Setup 

1️⃣ Clone the Repository
git clone https://github.com/dearnidhi/MCQ-Quiz-Generator-Langchain-OpenAI.git
cd MCQ-Quiz-Generator-Langchain-OpenAI

2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate     # Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Configure OpenAI API Key
Create a .env file in the root directory:
OPENAI_API_KEY=your_api_key_here

▶️ Run the Application
streamlit run StreamlitAPP.py
The app will be available at:
http://localhost:8501

☁️ Deployment (AWS EC2 – Optional)
Launch an Ubuntu EC2 instance
Update system packages
sudo apt update && sudo apt upgrade -y
Install dependencies
sudo apt install git python3-pip -y
Clone the repository and install requirements
Allow inbound traffic on port 8501
Run Streamlit app

⚠️ Notes

Intended for educational and demo purposes
Requires a valid OpenAI API key
Output quality depends on prompt design
Not optimized for large-scale quiz generation
