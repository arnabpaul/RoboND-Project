# Robotics-Autonomous-Navigation-Project
This project is modeled after the NASA sample return challenge and it focuses on three essential elements of robotics:
perception, decision making and actuation. The project is carried out in a simulator environment built with the Unity game engine.

Project dependencies:
Python 3 and Jupyter Notebook

At first, the simulator is used to record camera pictures and telemetry data(.csv file) in a folder named "Roversim_folder"

Then, a jupyter notebook named "Rover-Project-Test-Notebook.ipynb" is used to expalin and execute different steps that helped 
creating "deceision.py", "perception.py" and "supporting_functions.py" code. 

Finally, drive_rover.py is written that uses all the above python code to drive the rover autonomously in the simulated environment and collect sample rocks.

The video file "test_mapping.mp4" shows how the robot navigate in the simulated environment and explore the map against a ground truth map. 
