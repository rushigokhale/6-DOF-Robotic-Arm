# 6-DOF Robotic Arm Simulation
A Python simulation of a 6-joint robotic arm that computes the gripper's position from joint angles, 
solves for joint angles from a target position, and animates a pick-and-place demo in 3D. To run it, 
create a virtual environment (`python3 -m venv .venv`), activate it (`source .venv/bin/activate`), 
install the libraries (`pip install numpy matplotlib`), then run `python RoboticArm.py` 
(add `--save arm.gif` to save a GIF instead). Change the arm size in the DH table inside 
`Arm6DOF.__init__` and the waypoints in `build_demo()`.
