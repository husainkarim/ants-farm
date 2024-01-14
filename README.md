# ANTS-FARM

This project challenges you to create a virtual ant farm and navigate its inhabitants through the most efficient paths. Get ready to test your coding skills and explore algorithm optimization!

## Project Overview

- Program: Develop a program named lem-in that simulates ant movement within a colony.
- Input: The program reads a file describing the colony's structure and ants.
- Output: Upon successful pathfinding, it displays:
    - The input file contents
    - Each ant's movement between rooms

## Colony Mechanics

- Rooms and Tunnels: The colony consists of interconnected rooms and tunnels.
- Ant Placement: All ants start in the ##start room.
- Goal: Guide ants to the ##end room using the quickest possible path.

## Challenges and Considerations

- Pathfinding: Implement efficient algorithms to find the shortest routes for multiple ants.
- Input Validation: Handle various invalid input scenarios gracefully, providing informative error messages:
    - Incorrect ant count
    - Missing ##start or ##end rooms
    - Duplicate rooms
    - Invalid room coordinates
    - Links to unknown rooms
- Edge Cases: Account for colonies with:
    - No solvable path
    - Rooms linked to themselves

## Usage:

Compile the Program: Follow the provided instructions to build the lem-in executable.
Run the Program: Execute it, providing a valid colony description file as an argument:
```
./lem-in <colony_file>
```

## Get Ready to Explore the Ant Farm!

Set your coding skills in motion and create an efficient ant colony simulator. Embrace the challenges and enjoy the journey!