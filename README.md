# Sudoku Game

This is a simple interactive Sudoku game built with HTML, CSS, and JavaScript. It features a dynamically generated 9x9 Sudoku grid and provides functionality to solve the puzzle using a backtracking algorithm, as well as reset the grid. The design is enhanced using Tailwind CSS for modern UI styling and smooth animations......

## Features

- **Sudoku Grid**: A 9x9 grid where players can enter numbers to solve the puzzle.
- **Solve**: Solves the Sudoku puzzle using a backtracking algorithm.
- **Reset**: Resets the grid to its initial empty state.
- **Responsive UI**: Built with Tailwind CSS to ensure a responsive and visually appealing design.
- **Animations**: Cells fade in with an animation for smooth transitions.

## Technologies Used

- **HTML**: The structure of the Sudoku game interface.
- **CSS**: Styling is handled using Tailwind CSS and custom animations.
- **JavaScript**: Logic for generating the grid, solving the Sudoku puzzle, and resetting the grid.

## How to Use

1. Open the `index.html` file in any modern web browser.
2. Start by filling in the Sudoku grid with your own numbers.
3. Use the **Solve** button to let the program automatically solve the puzzle for you.
4. Use the **Reset** button to clear the grid and start over.
5. The solution will be displayed in a separate grid below the original one.

## File Structure

```
/index.html
```

- The `index.html` file contains the entire HTML structure, CSS styles, and JavaScript functionality for the Sudoku game.

## Functionality

- **Sudoku Grid**: The grid is dynamically generated with a 9x9 structure of input fields for user interaction.
- **Solving Sudoku**: The backtracking algorithm checks for the validity of each number and solves the puzzle.
- **Reset**: Clears the grid and hides the solution grid.

## Sudoku Solver Algorithm

The Sudoku solver uses a **backtracking algorithm** that:
1. Attempts to place numbers from 1 to 9 in an empty cell.
2. Checks if the number is valid by ensuring it does not repeat in the current row, column, or 3x3 subgrid.
3. Recursively solves the grid by attempting further placements.
4. If a conflict arises, it backtracks to the previous step and tries the next possible number.

## Customization

You can modify the design and functionality by editing the following:

- **Grid size**: Modify the HTML structure if you wish to support a larger or smaller grid.
- **Styling**: Customize the CSS classes to adjust the colors, sizes, and animations according to your preferences.
- **Algorithm**: Modify the backtracking algorithm for performance optimizations or to add different solving methods.

## License

This project is licensed under the MIT License. Feel free to use and modify it as per your needs.

## Acknowledgements

- **Tailwind CSS**: For providing a utility-first CSS framework that makes styling faster and more efficient.
- **JavaScript**: For handling the logic to generate the grid, solve the puzzle, and reset the game.

Enjoy solving Sudoku!
