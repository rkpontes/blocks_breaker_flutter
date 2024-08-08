# Blocks Breaker

Blocks Breaker is a retro-style arcade game built using the Flutter framework and the Flame game engine. The game challenges players to break all the blocks by controlling a paddle and bouncing a ball, with the goal of clearing the screen to advance to the next level.


## Table of Contents

- Features
- Installation
- How to Play
- Project Structure
- Contributing
- License


## Features

- **Retro Arcade Feel**: Inspired by classic block-breaking games.
- **Responsive Design**: Works seamlessly on different screen sizes.
- **Customizable Theme**: Integrated with Google Fonts for a retro look and feel.
- **Multiple Game States**: Different overlays for game start, game over, and winning states.
- **Easy Controls**: Control the paddle using arrow keys or swipe gestures.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/rkpontes/blocks_breaker_flutter.git
cd blocks_breaker
```

2. Install dependencies:

```bash
flutter pub get
```

3. Run the app:

```bash
flutter run
```

Make sure you have Flutter installed. If not, you can follow the official [Flutter installation guide](https://docs.flutter.dev/get-started/install).

## How to Play

- **Start the Game**: Tap the screen or press any key to start.
- **Control the Paddle**: Use the arrow keys or swipe left and right to control the paddle.
- **Win the Game**: Break all the blocks on the screen to win the game.
- **Game Over**: If the ball falls below the paddle, the game is over. Tap to restart.


## Project Structure

Here's a brief overview of the project's structure:

```plaintext
lib/
├── main.dart                   # Entry point of the app
├── src/
│   ├── components/             # Directory containing game components
│   │   ├── ball.dart           # Ball component logic
│   │   ├── bat.dart            # Bat (paddle) component logic
│   │   ├── brick.dart          # Brick component logic
│   │   ├── components.dart     # Combined components logic and helpers
│   │   └── play_area.dart      # Play area setup and management
│   ├── widgets/                # Directory containing UI widgets
│   │   ├── game_app.dart       # Main game app widget
│   │   ├── overlay_screen.dart # Overlay screens for different game states
│   │   └── score_card.dart     # Widget to display the current score
│   ├── blocks_breaker.dart     # Game logic and configuration
│   └── config.dart             # Game configuration like dimensions and settings
```

## Contributing

Contributions are welcome! If you want to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for more details.