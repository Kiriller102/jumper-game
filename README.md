## README

## Project Description

This is a simple game developed in the Kotlin programming language using Jetpack Compose for UI and coroutine for asynchronous operations. The game includes the following basic features:
- The game is controlled using the device's tilt sensor.
- The player jumps on platforms while avoiding falling.
- The game uses the OpenWeatherMap API to get current weather conditions that affect the background of the game.
- Records are kept, which are stored in a SQLite database.

## Requirements

- Android Studio
- Device with tilt sensor
- Internet connection to get weather data

## Installation

1. Clone the repository:
    ```bash
    git clone <URL of your repository>
    ```

2. Open the project in Android Studio.

3. Synchronize the project with Gradle to load all dependencies.

## Usage.
1. Start the project in Android Studio.
2. From the menu, select "Start Game" to start the game.3. Control the character by tilting the device.4. Jump on the platforms, trying not to fall.
5. Your record will be saved in the database and you will be able to see it in the "Records" section.

## Project Structure- `MainActivity.kt` - the main activity file containing the game logic and menus.
- `GameScreen.kt` - the file with the implementation of the main game screen.
- `PauseMenu.kt` - file with the implementation of the pause menu.- `HighScoreDialog.kt` - file with dialog for displaying records.- `AddHighScoreDialog.kt` - file with dialog for adding a new record.- `TiltSensor.kt` - file with implementation of tilt sensor operation.
- `RecordDatabaseHelper.kt` - file with implementation of the assistant for working with the records database.
  
## Support

If you have any questions or suggestions on how to improve the project, please create an issue in the repository or contact the developer directly.



