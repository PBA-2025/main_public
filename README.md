# Physics-based Animation 4860-1081 2025S

[![Rust CI](https://github.com/PBA-2025/main/actions/workflows/CI.yml/badge.svg)](https://github.com/PBA-2025/main/actions/workflows/CI.yml)

![teaser](doc/rep_image.png)

Lecture at graduate school of information science and technology in the university of Tokyo, spring semester, 2025

#### ITC-LMS 

For Zoom link, Slack, and GitHub Classroom invitations

- https://utol.ecc.u-tokyo.ac.jp/lms/course?idnumber=2025_4886_4860-1081_01

#### Instructor
Dr. Nobuyuki Umetani 
- email: n.umetani@gmail.com
- url: http://www.nobuyuki-umetani.com/
- lab's website: https://cgenglab.github.io/en/

- Teaching assistants: Kenji Tojo (https://kenji-tojo.github.io/), Yuhan Wu (https://yoharol.github.io/pages/myself/)

#### Time
- Monday 2rd period, 10:25pm - 12:10pm

#### Course Description

Computer-generated images are everywhere in movies, video games, and VR. This course is an introduction to the techniques to animate objects in computer graphics based on the law of physics. The aim of the course is to get familiar with applied mathematics such as linear algebra, vector analysis, partial differential equations, tensor mechanics, variational principle, optimization, and numerical analysis through the animation techniques for particle systems, rigid bodies, and elastic bodies. There are C#/Rust/Python programming assignments to acquire research-oriented graphics programming skills. The students also learn basics use of the computer graphics software Unity and Blender.

Topics:
- mass-spring simulation
- rigid body simulation
- elastic body simulation
- cloth and hair modeling & simulation
- collision-detection using spatial hashing
- finite boundary method



## Lecture Schedule

| Day              | Topic                                                                                                          | Assignment       | Slide      |
|:-----------------|:---------------------------------------------------------------------------------------------------------------|:-----------------|------------|
| (1)<br> Apr. 7   | **Introduction**<br>Data structure for simulation, Explicit/implicit shape representation                      |                  | [1,2]      |
| (2)<br> Apr. 21  | **Programming 1**<br>Introduction to Rust language, GitHub                                                     | [task00](task00) | [3,4]      |
| (3)<br> Apr. 28  | **Time Integration**<br>Backward & forward Euler method, particle system, Barnes–Hut method                    | [task01](task01) | [5,6]      |
| (4)<br> May 8    | **Newtonian Mechanics**<br/>                                                                                   | [task02](task02) | [7]        |
| (5)<br> May 12   | **Collision Detection**<br/>principal component analysis<br>sort & sweep method, bounding volume hierarchy<br> | [task03](task03) | [8,9]      |
| (6)<br> May 19   | **Linear System**<br/>matrix data structure, Conjugate gradient method                                         | [task04](task04) | [10,12]    |
| (7)<br> May 26   | **Simple Elastic Energy**<br/>Newton-Raphson method<br>mass-spring system                                      | [task05](task05) | [11,13]    |
| (8)<br> June 9   | **Programming 2**<br>Introduction to Unity & C#                                                                | [task06](task06) | [14,15,16] |
| (9)<br> June 16  | **Dynamic Simulation**<br/>Variational time integration                                                        | [task07](task07) | [17,18]    |
| (10)<br> June 23 | **Optimization with Constraint**<br/> Lagrange multiplier method                                               | [task08](task08) | [19]       |
| (11)<br> June 30 | **Rotation**<br>Rotation representation                                                                        | [task09](task09) | [20]       |
| (12)<br> July 7  | **Rigid Body Dynamics** <br/>inertia tensor, <br/>angular velocity                                             | [task10](task10) | [21,22]    |
| (13)<br> July 14 | **Continuum Mechanics**<br> tensor,<br> finite element method                                                  |                  |            |

#### Slides

- [1] [Introduction](http://nobuyuki-umetani.com/pba2025s/introduction.pdf)
- [2] [Data Structure](http://nobuyuki-umetani.com/pba2025s/data_structure.pdf)
- [3] [Rust](http://nobuyuki-umetani.com/pba2025s/rust.pdf)
- [4] [Git & GitHub](http://nobuyuki-umetani.com/pba2025s/git_wo_link.pdf) 
- [5] [Time Integration](http://nobuyuki-umetani.com/pba2025s/time_integration.pdf)
- [6] [Floating Point Number](http://nobuyuki-umetani.com/pba2025s/floating_point_number.pdf)
- [7] [Newtonian Mechanics](http://nobuyuki-umetani.com/pba2025s/newtonian_mechanics.pdf)
- [8] [Jagged Array](http://nobuyuki-umetani.com/pba2025s/jagged_array.pdf)
- [9] [Collision Detection](http://nobuyuki-umetani.com/pba2025s/collision_detection.pdf)
- [10] [Matrix Data Structure](http://nobuyuki-umetani.com/pba2025s/matrix_data_structure.pdf)
- [11] [Linear System Solver](http://nobuyuki-umetani.com/pba2025s/linear_system_solver.pdf)
- [12] [Jacobian & Hessian](http://nobuyuki-umetani.com/pba2025s/jacobian_hessian.pdf)
- [13] [Grid & Mesh Interpolation](http://nobuyuki-umetani.com/pba2025s/grid_mesh_interpolation.pdf)
- [14] [Unity](http://nobuyuki-umetani.com/pba2025s/unity.pdf)
- [15] [Mass Spring System](http://nobuyuki-umetani.com/pba2025s/mass_spring_system.pdf)
- [16] [Vector Differentiation](http://nobuyuki-umetani.com/pba2025s/vector_differentiation.pdf)
- [17] [Optimization](http://nobuyuki-umetani.com/pba2025s/optimization.pdf)
- [18] [Variational Integration](http://nobuyuki-umetani.com/pba2025s/variational_integration.pdf)
- [19] [Optimization with Constraints](http://nobuyuki-umetani.com/pba2025s/optimization_with_constraints.pdf)
- [20] [Rotation](http://nobuyuki-umetani.com/pba2025s/rotation.pdf)
- [21] [Angular Velocity](http://nobuyuki-umetani.com/pba2025s/angular_velocity.pdf)
- [22] [Rigid Body Approximation](http://nobuyuki-umetani.com/pba2025s/rigid_body_approximation.pdf)

## Grading

- 20% lecture attendance
  - Attendance is counted based on writing a secret keyword on LMS. The keyword is announced for each lecture.  
- 80% small assignments
  - see below

#### Assignments

There are many small programming assignments. To do the assignments, you need to create your own copy of this repository through **GitHub Classroom**.  These assignements needs to be submitted using **pull request** functionality of the GitHub. Look at the following document. 

[How to Submit the Assignments](doc/submit.md)

| Task ID          | Language | Title (tentative)                                                   | Thumbnail                 |
|:-----------------|:---------|:--------------------------------------------------------------------|:--------------------------|
| [task00](task00) | Rust     | Building Rust project & submitting GitHub pull request              | ![](task00/thumbnail.gif) |
| [task01](task01) | Rust     | Implicit Time Integration                                           | ![](task01/thumbnail.gif) |
| [task02](task02) | Rust     | Linear Momentum Conservation                                        | ![](task02/thumbnail.gif) |
| [task03](task03) | Rust     | Acceleration of N-body Simulation                                   | ![](task03/thumbnail.gif) |
| [task04](task04) | Rust     | Accelerated nearest search using Kd-Tree                            | ![](task04/thumbnail.gif) |
| [task05](task05) | Rust     | Solving Laplace equation with Gauss-Seidel Method                   | ![](task05/thumbnail.gif) |
| [task06](task06) | C#       | Gradient Descent for Mass-Spring Simulation                         | ![](task06/thumbnail.gif) |
| [task07](task07) | C#       | Dynamic Mass-spring System using Variational Euler Time Integration | ![](task07/thumbnail.gif) |
| [task08](task08) | C#       | Controlling Volume of a Mesh using Lagrange-Multiplier Method       | ![](task08/thumbnail.gif) |
| [task09](task09) | C#       | Rotation and Energy Minimization                                    | ![](task09/thumbnail.gif) |
| [task10](task10) | C#       | Simulation of Rigid Body Precession                                 | ![](task10/thumbnail.gif) |


#### Policy

- Do the assignment by yourself. Don't share the assignments with others.
- Don't post the answers of the assignment on Slack 
- Late submission of an assignment is subject to grade deduction
- Score each assignment will not be open soon (instructor needs to adjust weights of the score later)
- You can use AIs tool for coding.



## Reading Material

- [Ten Min Physics (Youtube channel)](https://www.youtube.com/@TenMinutePhysics/videos)
- [Physically Based Modeling: Principles and Practice, Siggraph '97 Course notes by Dr. Baraff](http://www.cs.cmu.edu/~baraff/sigcourse/index.html)
- [Physics-Based Animation  by Kenny Erleben et al. (free textobook about rigid body dynamics)](https://iphys.wordpress.com/2020/01/12/free-textbook-physics-based-animation/)
- [Dynamic Deformables: Implementation and Production Practicalities, SIGGRAPH 2020 Courses](http://www.tkim.graphics/DYNAMIC_DEFORMABLES/)
- [Awesome Computer Graphics (GitHub)](https://github.com/luisnts/awesome-computer-graphics)
- [Skinning: Real-time Shape Deformation SIGGRAPH 2014 Course](https://skinning.org/)


#### My Past Lectures
- [Applied Computer Graphics 2024S](https://github.com/nobuyuki83/Applied_Computer_Graphics_2024S)
- [Physics-based Animation 2023S](https://github.com/nobuyuki83/Physics-based_Animation_2023S)
- [Applied Computer Graphics 2022S](https://github.com/nobuyuki83/Applied_Computer_Graphics_2022S)
- [Physics-based Animation 2021S](https://github.com/nobuyuki83/Physics-based_Animation_2021S)
