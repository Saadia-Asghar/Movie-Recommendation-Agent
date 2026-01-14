# 🎬 AI Movie Taste Agent
A personalized movie recommendation engine powered by Google'si AI Studio. This interactive tool analyzes your favorite films to understand your cinematic preferences and suggests new movies you'll love.
## 🚀 Features
- **Personalized Taste Analysis**: Uses advanced AI to write a natural language paragraph describing your specific taste in movies.
- **Smart Recommendations**: Suggests exactly three new movies based on your inputs, providing specific reasons for each choice.
- **Interactive Interface**: Built with `ipywidgets` for a clean, user-friendly experience in Jupyter Notebooks or Google Colab.
- **Powered by Gemini**: Utilizes Google's state-of-the-art Generative AI models for deep understanding of movie themes.
## 📋 Requirements
- Python 3.x
- Jupyter Notebook or Google Colab environment
- A Google AI Studio API Key
## 📦 Installation
Install the necessary Python libraries using pip:
```bash
pip install google-generativeai ipywidgets ipython
⚙️ Setup & Configuration
Get an API Key: Visit Google AI Studio to create your API key.
Update the Script: Open the code and replace the API key line with your own key:
python
# Configure API key
genai.configure(api_key="YOUR_ACTUAL_API_KEY_HERE")
Note: Ensure you are using a valid model version supported by your account (e.g., gemini-pro).

🎮 How to Use
Open the notebook/script in your Jupyter environment.
Run the cell to launch the widget.
Enter three of your favorite movies in the text fields.
Click the Analyze button.
Result: The AI will generate a description of your taste and 3 recommendations instantly!

📋 Example
Input:

Movie 1: Inception
Movie 2: The Matrix
Movie 3: Interstellar
Output:

You seem to enjoy mind-bending science fiction that explores complex philosophical concepts and the nature of reality. You appreciate visually stunning films with high stakes, intellectual depth, and intricate plots that challenge your perception of time and space.

Recommended Movies:

Blade Runner 2049 – It offers a visually immersive and philosophically rich sci-fi experience similar to your favorites.
Arrival – A cerebral sci-fi film that deals with complex themes of time and communication.
Dark City – A stylistic precursor to The Matrix that explores similar themes of reality and memory.
⚠️ Important Note
Security: Never share your API key publicly or commit it to GitHub. Use environment variables for better security.
Model Version: Ensure you have access to the model version specified in the code (models/gemini-1.5-pro or similar).
