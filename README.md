# Introducing PlaylistPhantom!
A new way to find new music through simply saying what's on your mind!

![image](https://github.com/danielhuynh0/PlaylistPhantom/assets/101992027/32a123a4-ee59-4e07-8e2a-2d415e88172a)

Building upon a project I previously created (_nlp-playlistgen_) which generated playlists using a translation from text into song embeddings, and used different machine learning algorithms to generate playlists based on Euclidean distance in song embedding feature space, this new application features a user interface to allow for web interfacing, visualizations, ease of interaction, greater accessibility, as well as a much wider range of features!

**In the works**: A new Spotify API integration is in the works to directly add playlists to your Spotify account!
## Navigation
- Check out my _nlp-playlistgen_ repository, powering the playlist generation logic, by entering into the **_backend_** directoy.
- Check out my Next.JS frontend implementation by viewing the **_frontend_** repository.

## How to run the application
### Requirements:
- Python 3.9 or earlier (Google Gemini API is not compatible with Python 3.10)
- Google Gemini API key (Note: This is completely free with a Google account! This can be found at https://ai.google.dev/)
  - You will need to place it in a .env file following the steps of this tutorial: https://medium.com/@sujathamudadla1213/what-is-the-use-of-env-8d6b3eb94843
  - Simply place it in the required format in the .env file, and you will not have to change anything else!
- Node.js (needed to run npm for Next.JS frontend)
### How to run:
- clone this git repository
- cd into 'backend' in your command line
- create a virtual environment using your Python 3.9 version (refer to the following for help: https://stackoverflow.com/questions/1534210/use-different-python-version-with-virtualenv)
- activate your virtual environment
- run ``` pip install -r requirements.txt ``` to install all required libraries for this program
- then, run ```python -m uvicorn routes:app --reload``` in your command line to start the backend server
- in another terminal, cd into 'frontend/playlistphantom-frontend' in your command line
- run ```npm install``` to install all dependencies
- finally, run ```npm run dev``` in the command line
- use the application by visiting the link 'http://localhost:3000/' in your browser
- HAVE FUN!
![playlist2](https://github.com/danielhuynh0/PlaylistPhantom/assets/101992027/58c0c6e8-fc2f-4355-869f-c779d79283de)
