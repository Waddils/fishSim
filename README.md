# Welcome to the Aquarium Project

This project is meant for the Software Engineering Course at UNF.
A boid simulation featuring prey and predator boids with dynamic interactions, obstactles, and a pygame GUI. 

## How to run

- Install python (at least ver.3.12.4)
- Install pygame ('pip install pygame')
- Run main.py with 'python main.py'

## Controls

### Title Screen

- Start Sim : Begin a new simulation
- Load : Load a saved state
- Exit : Quit the program

### Simulation UI

- Spawn boid : This displays another menu for you to select how many prey/predators and a button to spawn them
- Pause : Pauses the simulation
- Reset : Resets the simulation, removes all boids and randomizes obstacles
- Save : Prompts a file manager to save your boid data to a file
- Load : Prompts a file manager to load in a boid data file

## File Structure

- main.py : Handles the initial launch of the program
- gui.py (deprecated): Handles the gui of the simulation and the visual aspects of the program
- simulation.py : Handles core simulation logic
- prey.py : Defines prey behavior, food-seeking, and predator avoidance
- predator.py : Implements predator logic for chasing prey and hunger mechanics
- boid.py : Base class for boid physics, grouping rules, and obstacle avoidance
- food.py : Manages food spawning, decay, and collision detection
- obstacles.py : Defines obstacle properties and collision checks
- config_manager.py: Handles save/load functionality and logging
- textures folder : Holds visual assets of the simulation

## Deviations
- deviations from the original proposal and the reasons

## Design patterns
- what design patterns were used specifically naming them and why they were used

## Test case design
- How did you design your test cases--discuss what specific test design methods you used 

## Additional Notes

- If you wish to do unit test coverage use the module 'coverage' (Install using terminal: 'pip install coverage')
- Run ('python -m coverage run -m unittest discover Code/tests/') to generate coverage
- Run ('python -m coverage report') to see the report
