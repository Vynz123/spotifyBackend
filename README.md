# Spotify Clone 🎧

## Description

This project is a simplified clone of Spotify, designed to allow users to browse, play, and manage their music library. It incorporates a full-stack development approach using Flask for the backend, HTML/CSS for the frontend, JavaScript for client-side interactivity, and SQLite for database management.

## Technologies Used

- **Backend**: Flask
- **Frontend**: HTML, CSS
- **Client-Side**: JavaScript
- **Database**: SQLite

## Features

- **User Authentication**: Register, login, and manage user profiles.
- **Music Streaming**: Browse, play, and manage songs.
- **Playlist Management**: Create, update, and delete playlists.
- **Search Functionality**: Search for songs and artists.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/vynx1/spotifyBackend
    git clone https://github.com/vynx1/spotifyFrontend
    cd spotifyBackend
    Open another window
    cd spotifyFrontend
    ```

2. **Create a virtual environment**:
    ```bash
    On backend 
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4.
Backend
 Run python3 main.py

Frontend:

Run Make/Jekyll Serve on home.html

5. Enjoy


## Usage

- **Homepage**: Browse featured songs and choose ones to play.
- **Play Screeny**: A redirected dyanmic webpage to play your song and display its details
- **Create**: Add songs to the SQLITe Database.


## Project Structure

- **/templates**: Containes the frontend html files.
- **/Songs**:  Contains the predownloaded songs. Databse songs are Ommited for copyright reasons
- **/models**: Stores PYthon3 Flask Models
- **/api**: Stores/Creates the API's using the models and deploys them on the backend


## Contributing

Feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
