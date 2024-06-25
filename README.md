# Grid Navigation

## Objective

Create a simple text-based game in C++ where the player navigates a 2D grid by entering directions (up, down, left, right). The game will check for out-of-bounds movements and update the player's position on the grid.

## Requirements

### Game Grid Representation

The game should use a 5x5 two-dimensional array to represent the grid.

### Player Movement

The program should:
- Allow the player to input directions (up, down, left, right).
- Move the player in the chosen direction.
- Validate moves to ensure the player does not move out of bounds.
- Update the player's position on the grid.

### Display

The program should display:
- The current state of the grid after each move.
- Instructions for the player on how to input their moves.
- The player's current position on the grid.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>` for keyboard input.

### 2. Define Variables

- Define a 5x5 two-dimensional array to represent the grid.
- Define variables to keep track of the player's position.

### 3. Initialize the Game Grid

- Create a function to initialize the game grid with empty spaces.

### 4. Display the Game Grid

- Create a function to display the current state of the game grid.

### 5. Player Movement Input

- Create a function to handle player input for controlling the player's direction.

### 6. Move the Player

- Create a function to move the player in the chosen direction and update the game grid.

### 7. Check for Out-of-Bounds

- The move_player function should include checks to ensure the player's move is within the bounds of the grid.

### 8. Game Loop

- Implement the game loop to continuously update the game state, display the grid, and handle player movement.

## Example User Interaction

```plaintext
*******************************
*       Grid Navigation       *
*******************************

Controls: W (Up), S (Down), A (Left), D (Right)

  _ _ _ _ _
  _ _ _ _ _
  _ _ P _ _
  _ _ _ _ _
  _ _ _ _ _

Move (WASD): w

  _ _ _ _ _
  _ _ P _ _
  _ _ _ _ _
  _ _ _ _ _
  _ _ _ _ _

Move (WASD): a

  _ _ _ _ _
  _ P _ _ _
  _ _ _ _ _
  _ _ _ _ _
  _ _ _ _ _
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
