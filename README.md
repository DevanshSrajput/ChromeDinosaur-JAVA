# ChromeDinosaur-JAVA

A Java recreation of the classic Chrome Dinosaur game. This beginner-friendly project demonstrates game logic, keyboard controls, simple physics, and basic collision detection using Java Swing.

## Features

- Playable Chrome Dinosaur game in Java
- Simple jump mechanic (press SPACE to jump)
- Randomly spawning cactus obstacles
- Score tracking and Game Over screen
- Easy to understand and extend for learning purposes

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher

### How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/DevanshSrajput/ChromeDinosaur-JAVA.git
   ```

2. Compile the code:

   ```bash
   javac App.java ChromeDinosaur.java
   ```

3. Run the game:

   ```bash
   java App
   ```

The game window will appear. Press `SPACE` to jump and avoid the cacti!

## Code Overview

- **App.java**: Entry point. Sets up the JFrame and game panel.
- **ChromeDinosaur.java**: Main game logic, drawing, input handling, and physics.
    - Dinosaur and cactus images loaded from the `img/` directory.
    - Game loop and cactus spawning managed by timers.
    - Collision detection, scoring, and restart functionality.

## Contributing

Feel free to use this code as a base to add features like birds, night mode, sound, or difficulty scaling. Pull requests are welcome! If you improve or extend the game, please share your version and submit a PR so others can learn from your changes.

## License

No license specified. Please contact the repository owner for usage details.

## Credits

Created by [DevanshSrajput](https://github.com/DevanshSrajput).

---

**Happy Coding!**
