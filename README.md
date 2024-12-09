## 🎵 Music Recommender System

This project is a Music Recommender System that suggests songs based on Cosine Similarity and distance metrics. Users can select a song, and the system recommends five similar tracks, complete with album covers fetched from Spotify.

## 🚀 Features
	•	Song Recommendation: Recommends top 5 similar songs to the selected track.
	•	Spotify API Integration: Fetches album covers and song metadata dynamically.
	•	Interactive Interface: Built using Streamlit for a seamless user experience.
	•	Dataset Analysis: Utilizes the Spotify Million Song Dataset for feature-based similarity.

## 🛠 Technologies Used
	•	Python
	•	Streamlit
	•	Spotipy (Spotify Web API)
	•	pandas
	•	nltk

📋 Prerequisites
	1.	Python
	2.	Spotify Developer Account for generating your Client ID and Client Secret.

⚙️ Setup Instructions

Step 1: Clone the Repository

git clone https://github.com/your-username/music-recommender-system.git  
cd music-recommender-system  

Step 4: Download the Dataset

Download the Spotify Million Song Dataset (https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset/code), and place the relevant files (e.g., df.pkl) in the project directory.

Step 5: Run the Application

Launch the app with Streamlit:

streamlit run app.py  

## 📊 Dataset Details

This project uses the Spotify Million Song Dataset, which includes attributes like:
	•	Track Name
	•	Artist
	•	Audio Features: Danceability, energy, loudness, tempo, etc.

Dataset Source: Kaggle.

## 🌟 How It Works
	1.	Input: Select a song from the dropdown list.
	2.	Recommendation: The system calculates song similarity using Cosine Similarity and recommends the top 5 tracks.
	3.	Album Covers: Displays album covers fetched via Spotify’s API.
	4.	Interactive UI: Clean and user-friendly layout for better experience.

## 🚧 Future Enhancements
	•	Incorporate user history for personalized recommendations.
	•	Add more similarity metrics like Euclidean distance.
	•	Enable real-time dataset updates using Spotify API.

## 💡 Libraries Required
	•	pandas: For data analysis.
	•	Streamlit: For the app interface.
	•	pickle: To load preprocessed data.
	•	Spotipy: To interact with Spotify API.
	•	nltk: For any text preprocessing (if needed).

## 🙋 Frequently Asked Questions

1. How do I get Spotify API credentials?
	•	Visit the Spotify Developer Dashboard (https://developer.spotify.com/dashboard/).
	•	Create a new app to get your Client ID and Client Secret.

2. Can I use a different dataset?
	•	Yes, but preprocess it to match the format used in this project.

3. How can I deploy this app?
	•	Use platforms like Streamlit Cloud, Heroku, or AWS for deployment.

👨‍💻 Author

Piyush Kumar Mahato
Aspiring Data Scientist | Tech Enthusiast
