# AI_Blog_Gen

✍️ AI Blog Content Assistant
A Streamlit-based web application that leverages LangChain and Meta Llama 3.1 (via Hugging Face) to automate the blog creation process. This tool helps users brainstorm catchy titles and generate high-quality, SEO-friendly blog content in seconds.

🚀 Features: 
* Title Generation: Input a topic and receive 10 creative, attention-grabbing title suggestions.
* Full Blog Generation: Generate structured blog posts with an introduction, body, and conclusion.
* Keyword Integration: Add custom keywords to ensure your content is optimized for search engines.
* Adjustable Length: Use a slider to define the exact word count for your post (50 to 1000 words).

🛠️ Tech Stack: 
- Frontend: Streamlit
- LLM Framework: LangChain
- Model: Meta Llama-3.1-8B-Instruct
- Hosting: Hugging Face Inference Endpoints

📋 Prerequisites
Before running the app, ensure you have:
  A Hugging Face API Token (with access to Llama 3.1).
  Python 3.9+ installed.

⚙️ Installation & Setup
Clone the repository:
  git clone https://github.com/your-username/AI_Blog_Gen.git
  cd AI_Blog_Gen

Create a virtual environment:
  python -m venv .venv
  source .venv/bin/activate  # On Windows: .venv\Scripts\activate

Install dependencies:
  pip install streamlit langchain langchain-huggingface langchain-community

Set up your API Key:
Create a file named secret_api_keys.py in the root directory and add your key:
  huggingface_api_key = "your_hf_token_here"
  (Note: Ensure this file is added to your .gitignore!)

🏃 How to Run
Run the following command in your terminal:
  streamlit run app.py
