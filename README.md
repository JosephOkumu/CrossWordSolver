# Crossword Solver

## Description
The `crosswordSolver` function is designed to solve an empty crossword puzzle by filling it with a list of provided words. The puzzle is represented as a string with specific rules, and the function outputs the filled puzzle or an error message if the puzzle cannot be solved uniquely.

## Documentation
This section provides details on how to use the `crosswordSolver` function.

### Installation
To use the `crosswordSolver` function, you need to have Node.js installed on your system. You can download and install the latest version of Node.js from [here](https://nodejs.org/).

### Usage
1. Clone this repository to your local machine using the following command:
    ```bash
    git clone https://learn.zone01kisumu.ke/git/mombewa/crossword.git
    ```
2. Navigate into the project directory:
    ```bash
    cd crossword
    ```
3. Run the function using Node.js:
    ```bash
    node crosswordSolver.js
    ```
    Provide the empty puzzle string and the list of words as inputs. The function will print the solved puzzle.

    Example:
    ```bash
    const emptyPuzzle = `2001
    0..0
    1000
    0..0`;
    const words = ['casa', 'alan', 'ciao', 'anta'];

    crosswordSolver(emptyPuzzle, words);
    ```

### Features
- The function fills an empty crossword puzzle based on specific rules.
- It checks for the uniqueness of the solution and handles errors appropriately.
- The solution is displayed as a filled puzzle string.


### Contributions
Pull requests are welcome. You can contribute to this project by adding new features, optimizing the algorithm, or fixing bugs.

For major changes, please open an issue first to discuss what you would like to change.

### Author
[JosephOkumu](https://github.com/JosephOkumu)

### License
[LICENSE](./LICENSE)


### Credits
[Zone01Kisumu](https://www.zone01kisumu.ke/)