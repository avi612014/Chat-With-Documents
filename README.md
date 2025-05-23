# AI Code Assistant

A powerful AI-powered code assistant built with Streamlit and LangChain.

## Features

- Code Generation and Analysis
- Document Analysis
- YouTube Video Summarization
- Image Analysis
- Code Explanation and Documentation
- Interactive UI with Dark/Light Mode

## Deployment Instructions

### Local Development

1. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file with your API keys:
```
GOOGLE_API_KEY=your_google_api_key
OPENAI_API_KEY=your_openai_api_key
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
```

5. Run the application:
```bash
streamlit run main.py
```

### Deploying to Streamlit Cloud

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and:
   - Sign up/Login with your GitHub account
   - Click "New app"
   - Select your repository
   - Set the main file path as `main.py`
   - Add the following environment variables:
     - GOOGLE_API_KEY
     - OPENAI_API_KEY
     - SUPABASE_URL
     - SUPABASE_KEY
   - Click "Deploy"

3. Your app will be deployed to a URL like: `https://your-app-name.streamlit.app`

## Environment Variables

- `GOOGLE_API_KEY`: Your Google API key for Gemini
- `OPENAI_API_KEY`: Your OpenAI API key
- `SUPABASE_URL`: Your Supabase project URL
- `SUPABASE_KEY`: Your Supabase API key

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
