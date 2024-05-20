
# JUKEE - A Simple Music Player Application

## Overview

JUKEE is a simple music player application built using Java. It allows users to enjoy a collaborative music listening experience. In JUKEE, there are two types of users: "Host" and "Visitor". The Host can create and manage a playlist that will be played for everyone, while Visitors can request songs to be added to the playlist managed by the Host.

## Features

- **Host**:
  - Create and manage a playlist.
  - Play, pause, skip songs in the playlist.
  - Approve or reject song requests from Visitors.

- **Visitor**:
  - View the current playlist.
  - Request songs to be added to the playlist.

## Installation

To run JUKEE locally on your machine, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/ChristianLPangestu/Jukee.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd Jukee
   ```
3. **Compile the project:**
   ```sh
   javac -d bin src/**/*.java
   ```
4. **Run the application:**
   ```sh
   java -cp bin com.example.jukee.Main
   ```

## Usage

1. **Starting the Application:**
   - Run the main class to start the application. The Host can create a new playlist and start adding songs.
   - Visitors can connect to the Host's session and request songs.

2. **Host Controls:**
   - Use the provided interface to add songs to the playlist.
   - Control the playback (play, pause, skip) using the player controls.
   - Review and approve/reject song requests from Visitors.

3. **Visitor Controls:**
   - View the current playlist.
   - Use the request feature to suggest new songs to the Host's playlist.

## Contributing

We welcome contributions to enhance JUKEE. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact:

- Christian L Pangestu - [GitHub](https://github.com/ChristianLPangestu)

---

Feel free to customize this README file as needed to better fit your project specifics and requirements.
