# Book-Recommendation-system-

This repository contains a **Book Recommendation System** that leverages **Natural Language Processing (NLP)**, **LangChain**, **Hugging Face**, and **Gemini AI** to provide personalized book recommendations based on user input. The system uses semantic search, emotional tone analysis, and category filtering to deliver highly relevant recommendations.

## Features

- **Semantic Search**: Uses embeddings from Gemini AI to find books similar to the user's query.
- **Emotional Tone Filtering**: Recommends books based on emotional tones like Happy, Surprising, Angry, Suspenseful, and Sad.
- **Category Filtering**: Allows users to filter recommendations by book categories.
- **Interactive Dashboard**: A user-friendly interface built with Gradio for querying and viewing recommendations.

- ├── .env # Environment variables ├── api.py # Backend API for recommendations ├── app.py # Main application logic ├── books_cleaned.csv # Cleaned book dataset ├── books_with_categories.csv # Dataset with book categories ├── books_with_emotions.csv # Dataset with emotional tone scores ├── cover_not_found.jpg # Placeholder image for missing book covers ├── data_exploration.ipynb # Notebook for data analysis ├── nn.ipynb # Neural network experiments ├── sentiment-analysis.ipynb # Sentiment analysis using Hugging Face ├── tagged_description.txt # Tagged descriptions for semantic search ├── vector-search.ipynb # Semantic search implementation ├── frontend/ # Frontend code for the application │ ├── public/ # Static assets │ ├── src/ # Frontend source code │ ├── package.json # Frontend dependencies │ ├── tsconfig.json # TypeScript configuration │ └── README.md # Frontend-specific documentation └── .idea/ # IDE configuration files

- ## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/book-recommendation-system.git
   cd book-recommendation-system
2.Install the required Python dependencies:
   pip install -r requirements.txt

3. Set up the .env file with your API keys and environment variables:

GOOGLE_API_KEY=your_google_api_key
HUGGING FACE API KEY 

4. Start the backend server:   python app.py

Open the Gradio dashboard in your browser to interact with the recommendation system.

Use the dropdowns to filter by category and emotional tone, and enter a description of the book you're looking for.




Technologies Used
LangChain: For document loading, text splitting, and semantic search.
Hugging Face: For sentiment analysis and emotional tone classification.
Gemini AI: For generating embeddings used in semantic search.
Gradio: For building an interactive user interface.
FastAPI: For serving the backend API.
Pandas & NumPy: For data manipulation and preprocessing.
Notebooks
data_exploration.ipynb: Explore and preprocess the book datasets.
sentiment-analysis.ipynb: Perform sentiment analysis using Hugging Face models.
vector-search.ipynb: Implement and test semantic search using LangChain and Gemini AI.


Datasets
books_with_emotions.csv: Contains book metadata and emotional tone scores.
books_with_categories.csv: Includes book categories for filtering.
tagged_description.txt: Text data used for semantic search.
Contributing
Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve the project.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
LangChain
Hugging Face
Gradio
Gemini AI


