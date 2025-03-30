# Maze Runner

## Overview
**Maze Runner** is an assembly-based maze exploration game where players navigate through a randomly generated maze, avoiding traps and enemies while collecting valuable items. The goal is to reach the exit while managing resources and overcoming challenges.

## Objective
Players must find their way out of a complex, dynamically generated maze. The game requires strategic movement, resource collection, and quick decision-making to avoid enemies and reach the exit point successfully.

## Features
- **Random Maze Generation**: Procedurally generated mazes ensure a unique gameplay experience each time.
- **Dynamic Enemy Placement**: Enemies are randomly spawned within the maze, making navigation challenging.
- **Collectible Items**:
  - Diamonds
  - Keys
  - Weapons
- **Scoring System**:
  - Score increases with collected items.
  - The score and time elapsed are displayed live on the top left of the screen.
- **Timer Mechanism**:
  - Tracks time taken to complete the maze.
  - Encourages players to optimize their path and escape efficiently.

## Technical Details
- **Developed in Assembly (Intel 8086 architecture)**
- **Optimized for real-time updates**
- **Utilizes memory-efficient data structures for maze storage**
- **Includes direct keyboard input handling for movement controls**
- **Interrupt-driven score and time display updates**

## Controls
- **Arrow Keys**: Move player up, down, left, or right.
- **Spacebar**: Interact with objects or use collected items.
- **Escape Key**: Exit the game.

## Setup Instructions
### Prerequisites
- An x86 emulator (e.g., DOSBox or Emu8086)
- Assembly compiler (e.g., MASM, NASM, TASM)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MazeRunner.git
   cd MazeRunner
   ```
2. Assemble the code:
   ```bash
   masm MazeRunner.asm;
   ```
3. Link the object file:
   ```bash
   link MazeRunner.obj;
   ```
4. Run the executable:
   ```bash
   MazeRunner.exe
   ```

## Contributing
We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m "Add YourCommitMessage"`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

For any issues or suggestions, feel free to open an issue or contact the maintainers. Happy coding! 🎮

