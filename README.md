This phase is all about mastering complex kinematics and Transform (TF) trees. Here is the technical breakdown:

The Architecture: Built a clean, hierarchal URDF from scratch, mapping the exact geometric transformations from the mobile base to the robotic end-effector.

The Testing (Shown in Video): Visualizing the mathematical stability of the 6-DOF joints in RViz2 using joint state publishers to verify axes of rotation (Roll, Pitch, Yaw).

The Next Step: Deploying the fully modeled robot into a Gazebo physics environment to test rigid body dynamics and inertia.

This mobile manipulator is the physical foundation for an ongoing application I am developing, which will eventually bridge custom A* path-planning with autonomous object interaction and delivery.
