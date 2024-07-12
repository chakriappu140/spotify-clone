# 🎵 Spotify Clone

## Overview

This Spotify Clone is a web application designed to replicate some of the core functionalities of Spotify, including user registration, login, music browsing, and playlist creation. It is built using HTML, CSS, and PHP, and utilizes a MySQL database for storing user and music data.

## Features

1. **🆕 User Registration**: Allow new users to register for an account.
2. **🔐 User Login**: Authenticate existing users.
3. **🔍 Search Music**: Search for songs and artists.
4. **🎶 Browse Music**: Browse music by genres, albums, and artists.
5. **📂 Create Playlist**: Users can create and manage their playlists.
6. **▶️ Play Music**: Play selected songs and control playback.

## Requirements

- 🌐 Web Server (e.g., Apache, Nginx)
- 🐘 PHP 7.4 or higher
- 🐬 MySQL 5.7 or higher

## Installation

### Clone the Repository

```sh
git clone https://github.com/yourusername/spotify-clone.git
cd spotify-clone
```

### Setup Database

1. **🗄️ Import the Database**: Import the `spotify.sql` file into your MySQL database.
2. **🔧 Configure Database**: Update the database configuration in `config.php` file.

```php
// config.php
$servername = "your_servername";
$username = "your_username";
$password = "your_password";
$dbname = "spotify";
```

### Run the Application

1. **🌐 Start the Web Server**: Ensure your web server and MySQL server are running.
2. **🖥️ Access the Application**: Open your web browser and navigate to the application URL.

## Folder Structure

- **📁 assets**: Contains images, stylesheets, and other static assets.
- **📁 includes**: Contains PHP scripts for database connection and other utilities.
- **📁 pages**: Contains main pages like home, search, and playlists.
- **📁 config.php**: Configuration file for database connection.
- **📁 spotify.sql**: SQL file for setting up the database.

## Usage

### Register

1. Navigate to the registration page.
2. Fill in the required details.
3. Submit the form to create an account.

### Login

1. Navigate to the login page.
2. Enter your credentials.
3. Submit the form to log in.

### Search and Browse Music

1. Use the search bar to find your favorite songs or artists.
2. Browse music by genre, album, or artist from the home page.

### Create and Manage Playlists

1. Navigate to the playlist section.
2. Create a new playlist or select an existing one.
3. Add or remove songs from your playlists.

### Play Music

1. Select a song to play.
2. Use the playback controls to play, pause, or skip tracks.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- 🎨 Design inspiration from Spotify.
- 💻 Built with love using HTML, CSS, and PHP.

---

### Note

This project is for educational purposes and may not cover all real-world scenarios or include all functionalities of the actual Spotify application.
```
