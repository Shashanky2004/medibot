# med-genAi_medical_chatbot
LLM based medical chatbot

## Features
- AI-powered medical information retrieval
- Integration with Google's Gemini model
- Vector storage using Pinecone
- Web interface using Flask

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/med-genAi_medical_chatbot.git
   cd med-genAi_medical_chatbot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file with your API keys:
   ```
   GOOGLE_API_KEY=your_key_here
   PINECONE_API_KEY=your_key_here
   ```

4. Store your medical documents in the `Data/` directory

5. Run the index creation:
   ```bash
   python store_index.py
   ```

6. Start the application:
   ```bash
   python app.py
   ```

## License
Apache License 2.0
