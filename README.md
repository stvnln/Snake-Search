# Snake-Search
Drawing upon what we learned this semester (Spring 2023), we developed an AI-powered Snake game that incorporates advance search techniques. More specifically, we implemented the A* search algorithm. Additionally, we added a visual element to view the different paths explored offering an insightful view of the algorithm.

Collaboration with:
Osaid Zeyad: https://www.linkedin.com/in/osaid-zeyad-a49094210/ 
Andres Cortes: https://www.linkedin.com/in/andres-c-a10908111/




## Requirements

    Python 3.x
    Pygame

## Installation

    Install Python 3.x if you haven't already.
    Install Pygame by running the following command:
    
    pip install pygame
    
 ## Running the Program

    Clone or download the repository.
    Navigate to the directory containing the program file snake_astar.py.
    Run the following command:
    
    python snake_astar.py
    
    The Snake A* game window will open. Watch the snake controlled by the A* algorithm to find the shortest path to the apple.

How It Works

The program consists of the following main components:

    Node: A class representing a grid cell on the board.
    Algorithm: A base class for search algorithms.
    A_STAR: A class that implements the A* search algorithm, inheriting from the Algorithm class.
    Snake: A class that represents the snake, handles its movement, and draws the game elements.
    main: The main function that runs the game loop.

The A* algorithm calculates the shortest path from the snake's head to the apple. The snake updates its direction and moves accordingly. The game is over if the snake collides with the walls or its body. A "Game Over" screen is displayed with a restart button to play the game again.
Customization

You can customize the game by changing the following constants in the code:

    size_of_board: Adjust the size of the game board.
    size_of_square: Change the size of each square on the board.
    height: Modify the height of the header area.

You can also change the colors of the game elements by modifying the relevant pygame.draw function calls in the Snake class.
