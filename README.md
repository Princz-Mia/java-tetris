# Java Tetris

Java Tetris is a simple implementation of the classic Tetris game written in Java. It provides a graphical user interface using Swing components and allows players to enjoy the addictive gameplay of arranging falling blocks to form complete lines.

## Background

During the third semester at Budapest University of Technology and Economics, as part of the requirements for the Programming 3 course, I undertook a homework project. For this project, I decided to create a simple implementation of the classic Tetris game, marking it as my first Java endeavor. Throughout the development process, I primarily relied on the course's presentation slides and supplemented my knowledge with help of the Internet.

## Features

- Colorful and intuitive graphical interface.
- Block shapes: I, J, L, O, S, T, Z.
- Controls:
  - Arrow keys: Move the block left, right, down or rotate.
  - Spacebar: Hard-drop block.
- Scoring:
  - Points are earned for each completed line. The game use the classic Tetris [point calculation](https://tetris.fandom.com/wiki/Scoring).
  - The game speed increases as the score increases.
- Leaderboard:
  - Tracks and displays the top scores of players.
  - Allows players to enter their names after a game over.
  - Leaderboard data is saved, therefore your accomplishments will not disappear.
- Settings in :
  - You can change the volumne of the game sounds and music.
- Settings in game:
  - Pause
  - Restart
  - Mute

## Getting Started

To run the Java Tetris game on your machine, follow these steps:

1. Ensure you have Java Development Kit (JDK) installed.
2. Clone the repository or download the source code.
3. Compile the Java source files using the following command:
   ```
   javac mia_princz/tetris/*.java mia_princz/tetrisblocks/*.java
   ```
4. Run the game using the following command:
   ```
   java mia_princz.tetris.Tetris
   ```

## How to Play

1. Launch the game using the instructions mentioned in the "Getting Started" section.
2. The menu window will open. Click on the "Start Game" button.
3. The menu window will close and game window will open, displaying the game grid.
4. Use the arrow keys to move the falling block left, right, or down.
5. Use the 'up' arrow to rotate the block.
6. Press space to hard-drop the block.
7. Try to arrange the falling blocks to form complete horizontal lines.
8. When a line is completed, it will be cleared, and you will earn points.
9. As you score more points, the game speed will increase.
10. If the stack of blocks reaches the top of the grid, the game ends.
11. After a game over, enter your name when prompted to save your score to the leaderboard.
* Click on the "Pause" button to pause the game or "Restart" button to restart the game at any time.
*  Click on the "Mute" button to mute the game sounds and music, click on the "Unmute" button to turn back on the sounds and music.
* Clcik on the "Return to Menu" button to close game window and open the menu window.

## Graphical Interface
<a href="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2x5ZXFxZ3JxY2p5cGJwMHp1NGpwc29uYWxxMDVibGpzbWI0eDZkaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LVhV26px9wDJ5ceFTe/giphy-downsized-large.gif"><img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2x5ZXFxZ3JxY2p5cGJwMHp1NGpwc29uYWxxMDVibGpzbWI0eDZkaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LVhV26px9wDJ5ceFTe/giphy-downsized-large.gif" style="width: 385px; max-width: 100%; height: 480px" title="Click to download picture" />
<a href="https://media.giphy.com/media/rPqJugLMa1pWDdl0Yh/giphy.gif"><img src="https://media.giphy.com/media/rPqJugLMa1pWDdl0Yh/giphy.gif" style="width: 385px; max-width: 100%; height: 480px" title="Click to download picture" />
<a href="https://drive.google.com/uc?export=download&id=1DDtybKzMgpPq4TsxJJLOozZRj9WruG8Q"><img src="https://drive.google.com/uc?export=download&id=1DDtybKzMgpPq4TsxJJLOozZRj9WruG8Q" style="width: 385px; max-width: 100%; height: 480px" title="Click to download picture" />
<a href="https://drive.google.com/uc?export=download&id=1hH8OenIpP3x0fI9RbGjeWuYeRTMpbT0X"><img src="https://drive.google.com/uc?export=download&id=1hH8OenIpP3x0fI9RbGjeWuYeRTMpbT0X" style="width: 385px; max-width: 100%; height: 480px" title="Click to download picture" />

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

This project is based on the work of [Mia Princz](https://github.com/Princz-Mia). The original repository can be found [here](https://github.com/Princz-Mia/java-tetris).

## Contributions

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to contact me.

## Disclaimer Regarding Images, Music, and Sounds

Please note that the images, music, and sounds used in this project may be subject to copyright and other intellectual property rights held by their respective owners. I do not claim ownership of these assets, and I have used them for demonstration purposes only.
It's important to respect the rights of asset creators and obtain proper permissions or licenses before using their work in your own projects. I encourage you to replace these assets with your own or use assets that are properly licensed for your specific use case.
If you are the creator or owner of any of the images, music, or sounds used in this project and would like them to be removed or credited differently, please contact me, and I will promptly address your concerns.
Thank you for understanding and respecting the rights of asset creators.
