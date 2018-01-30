# Awesome Robotics Libraries

A curated list of open source robotics simulators and libraries. 

#### Table of Contents
* [Simulators](#simulators)
* [Libraries](#libraries)
  * [Dynamics Simulation](#dynamics-simulation)
  * [Machine Learning](#machine-learning)
  * [Motion Planning](#motion-planning)
  * [Optimization](#optimization)
  * [Robot Modeling](#robot-modeling)
  * [Robot Platform](#robot-platform)
  * [SLAM](#slam)
  * [Vision](#vision)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

## [Simulators](#awesome-robotics-libraries)

###### Free or Open Source

* AirSim ([github](https://github.com/Microsoft/AirSim) ![AirSim](https://img.shields.io/github/stars/Microsoft/AirSim.svg?style=flat&label=Star&maxAge=86400)) - Open source simulator based on Unreal Engine for autonomous vehicles from Microsoft AI & Research
* [Gazebo](http://www.gazebosim.org/) ([bitbucket](https://bitbucket.org/osrf/gazebo)) - A dynamic multi-robot simulator from [Open Robotics](https://www.osrfoundation.org/).
* [GraspIt!](http://graspit-simulator.github.io/) ([github](https://github.com/graspit-simulator/graspit) ![graspit](https://img.shields.io/github/stars/graspit-simulator/graspit.svg?style=flat&label=Star&maxAge=86400)) - A simulator for grasping research that can accommodate arbitrary hand and robot designs developed by [the Columbia University Robotics Group](http://www.cs.columbia.edu/robotics/)
* [Isaac](https://www.nvidia.com/en-us/deep-learning-ai/industries/robotics/) - Nvidia's virtual simulator for robots
* [MORSE](http://morse-simulator.github.io/) ([github](https://github.com/morse-simulator/morse) ![morse](https://img.shields.io/github/stars/morse-simulator/morse.svg?style=flat&label=Star&maxAge=86400)) - The Modular OpenRobots Simulation Engine.
* [V-REP](http://www.coppeliarobotics.com/) - Virtual robot experimentation platform.

###### Commercial

* [Virtual Robotics Toolkit](https://www.virtualroboticstoolkit.com/)
* [Webots](http://www.cyberbotics.com/) - A commercial robot simulator used in more than 1200 companies, universities and research centers worldwide for R&D, education and research.

## [Libraries](#awesome-robotics-libraries)

### [Dynamics Simulation](#awesome-robotics-libraries)

> :warning: The following table is not complete. Please feel free to report if you find something incorrect or missing.

| Name | Models | Features | Languages | Licenses | Code | Popularity |
|:----:| ------ | -------- | --------- | -------- | ---- | ---------- |
| [Bullet](http://bulletphysics.org) | rigid, soft | ik, id | C++, Python | Zlib | [github](https://github.com/bulletphysics/bullet3) | ![bullet3](https://img.shields.io/github/stars/bulletphysics/bullet3.svg?style=flat&label=Star&maxAge=86400) |
| [CHRONO::ENGINE](http://chronoengine.info/) | rigid, soft, granular, fluid | ik, urdf | C++, Python | BSD-3-Clause | [github](https://github.com/projectchrono/chrono) | ![chrono](https://img.shields.io/github/stars/projectchrono/chrono.svg?style=flat&label=Star&maxAge=86400) |
| [DART](http://dartsim.github.io/) | rigid, soft | ik, id, plan, urdf, sdf | C++, Python | BSD-2-Clause | [github](https://github.com/dartsim/dart.git) | ![dart](https://img.shields.io/github/stars/dartsim/dart.svg?style=flat&label=Star&maxAge=86400) |
| [Drake](http://drake.mit.edu/) | rigid, aero, fluid | ik, trj-opt, plan | C++, Matlab | BSD-3-Clause | [github](https://github.com/RobotLocomotion/drake) | ![drake](https://img.shields.io/github/stars/RobotLocomotion/drake.svg?style=flat&label=Star&maxAge=86400) |
| [Flex](https://developer.nvidia.com/flex) | rigid, soft, particle, fluid  | | C++ | | [github](https://github.com/NVIDIAGameWorks/FleX) | ![NVIDIAGameWorks/FleX](https://img.shields.io/github/stars/NVIDIAGameWorks/FleX.svg?style=flat&label=Star&maxAge=86400) |
| [IBDS](http://www.interactive-graphics.de/index.php/downloads/12-ibds) | rigid, particle | | C++ | Zlib | | |
| idyntree | rigid | id | C++, Python, Matlab, Lua | LGPL-2.1 | [github](https://github.com/robotology/idyntree) | ![idyntree](https://img.shields.io/github/stars/robotology/idyntree.svg?style=flat&label=Star&maxAge=86400) |
| [KDL](http://www.orocos.org/kdl) | rigid | ik | C++ | LGPL-2.1 | [github](https://github.com/orocos/orocos_kinematics_dynamics) | ![orocos_kinematics_dynamics](https://img.shields.io/github/stars/orocos/orocos_kinematics_dynamics.svg?style=flat&label=Star&maxAge=86400) |
| kindr | rigid | (todo) | C++, Matlab | BSD-3-Clause | [github](https://github.com/ethz-asl/kindr) | ![kindr](https://img.shields.io/github/stars/ethz-asl/kindr.svg?style=flat&label=Star&maxAge=86400) |
| [Klampt](http://motion.pratt.duke.edu/klampt/) | (todo) | (todo) | C++, Python | BSD-3-Clause | [github](https://github.com/krishauser/Klampt) | ![Klampt](https://img.shields.io/github/stars/krishauser/Klampt.svg?style=flat&label=Star&maxAge=86400) |
| [LibrePilot](http://www.librepilot.org/site/index.html) | uav, vehicles | (todo) | C++ | GPL-3.0 | [bitbucket](https://bitbucket.org/librepilot/librepilot), [github](https://github.com/librepilot/LibrePilot) | ![LibrePilot](https://img.shields.io/github/stars/librepilot/LibrePilot.svg?style=flat&label=Star&maxAge=86400) |
| [MARS](http://rock-simulation.github.io/mars/) | (todo) | (todo) | C++, Python | LGPL-3.0 | [github](https://github.com/rock-simulation/mars) | ![mars](https://img.shields.io/github/stars/rock-simulation/mars.svg?style=flat&label=Star&maxAge=86400) |
| [MBDyn](https://www.mbdyn.org/) | (todo) | (todo) | C++ | GPL-2.1 | [download](https://www.mbdyn.org/?Software_Download) | |
| [MBSim](mbsim-env/mbsim) | (todo) | (todo) | C++ | (not specified) | [github](https://github.com/mbsim-env/mbsim) | ![mbsim-env/mbsim](https://img.shields.io/github/stars/mbsim-env/mbsim.svg?style=flat&label=Star&maxAge=86400) |
| [MBSlib](http://www.sim.informatik.tu-darmstadt.de/res/sw/mbslib) | (todo) | (todo) | C++ | LGPL-3.0 | [github](https://github.com/SIM-TU-Darmstadt/mbslib) | ![mbslib](https://img.shields.io/github/stars/SIM-TU-Darmstadt/mbslib.svg?style=flat&label=Star&maxAge=86400) |
| metapod | (todo) | (todo) | C++ | LGPL-3.0 | [github](https://github.com/laas/metapod) | ![metapod](https://img.shields.io/github/stars/laas/metapod.svg?style=flat&label=Star&maxAge=86400) |
| [Moby](http://physsim.sourceforge.net/index.html) | rigid | id | C++ | GPL-2.0 | [github](https://github.com/PositronicsLab/Moby) | ![Moby](https://img.shields.io/github/stars/PositronicsLab/Moby.svg?style=flat&label=Star&maxAge=86400) |
| [mrpt](http://www.mrpt.org/) | vehicle | slam, cv | C++, Python, Matlab | BSD-3-Clause | [github](https://github.com/MRPT/mrpt) | ![mrpt](https://img.shields.io/github/stars/MRPT/mrpt.svg?style=flat&label=Star&maxAge=86400) |
| [MuJoCo](http://www.mujoco.org/index.html) | (todo) | id | C++, Python | [licenses](https://www.roboti.us/license.html) | closed source | |
| [Newton Dynamics](http://newtondynamics.com/) | (todo) | (todo) | C++ | Zlib | [github](https://github.com/MADEAPPS/newton-dynamics) | ![newton-dynamics](https://img.shields.io/github/stars/MADEAPPS/newton-dynamics.svg?style=flat&label=Star&maxAge=86400) |
| [ODE](http://www.ode.org/) | rigid | | C++ | LGPL-2.1 or BSD-3-Clause | [bitbucket](https://bitbucket.org/odedevs/ode) | |
| [OpenRAVE](http://www.openrave.org) | (todo) | (todo) | C++, Python | LGPL-3.0 | [github](https://github.com/rdiankov/openrave) | ![openrave](https://img.shields.io/github/stars/rdiankov/openrave.svg?style=flat&label=Star&maxAge=86400) |
| [pinocchio](http://stack-of-tasks.github.io/pinocchio/) | rigid | ik, id | C++, Python | LGPL-3.0 | [github](https://github.com/stack-of-tasks/pinocchio) | ![pinocchio](https://img.shields.io/github/stars/stack-of-tasks/pinocchio.svg?style=flat&label=Star&maxAge=86400) |
| PositionBasedDynamics | (todo) | (todo) | C++ | MIT | [github](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics) | ![PositionBasedDynamics](https://img.shields.io/github/stars/InteractiveComputerGraphics/PositionBasedDynamics.svg?style=flat&label=Star&maxAge=86400) |
| [PyDy](http://www.pydy.org/) | (todo) | (todo) | Python | BSD-3-Clause | [github](https://github.com/pydy/pydy) | ![pydy](https://img.shields.io/github/stars/pydy/pydy.svg?style=flat&label=Star&maxAge=86400) |
| [RBDL](http://rbdl.bitbucket.org/) | rigid | ik | C++, Python | LGPL-3.0 | [bitbucket](https://bitbucket.org/rbdl/rbdl) | |
| RBDyn | rigid | (todo) | C++, Python | LGPL-3.0 | [github](https://github.com/jrl-umi3218/RBDyn) | ![RBDyn](https://img.shields.io/github/stars/jrl-umi3218/RBDyn.svg?style=flat&label=Star&maxAge=86400) |
| [ReactPhysics3d](http://www.reactphysics3d.com/) | (todo) | (todo) | C++ | Zlib | [github](https://github.com/DanielChappuis/reactphysics3d) | ![reactphysics3d](https://img.shields.io/github/stars/DanielChappuis/reactphysics3d.svg?style=flat&label=Star&maxAge=86400) |
| [Robotics Library](http://www.roboticslibrary.org/) | (todo) | (todo) | C++ | GPL-3.0 or BSD-2-Clause | [github](https://github.com/roboticslibrary/rl) | ![rl](https://img.shields.io/github/stars/roboticslibrary/rl.svg?style=flat&label=Star&maxAge=86400) |
| [RobWork](http://www.robwork.dk/apidoc/nightly/rw/index.html) | (todo) | (todo) | C++ | Apache-2.0 | [SVN](https://svnsrv.sdu.dk/svn/RobWork/trunk) (id/pw required) | |
| [siconos](http://siconos.gforge.inria.fr) | (todo) | (todo) | C++, Python | Apache-2.0 | [github](https://github.com/siconos/siconos) | ![siconos](https://img.shields.io/github/stars/siconos/siconos.svg?style=flat&label=Star&maxAge=86400) |
| [Simbody](https://simtk.org/home/simbody/) | rigid, molecules | id, urdf | C++ | Apache-2.0 | [github](https://github.com/simbody/simbody.git) | ![simbody](https://img.shields.io/github/stars/simbody/simbody.svg?style=flat&label=Star&maxAge=86400) |
| [SOFA](https://www.sofa-framework.org/) | medical | (todo) | C++ | LGPL-2.1 | [github](https://github.com/sofa-framework/sofa) | ![sofa](https://img.shields.io/github/stars/sofa-framework/sofa.svg?style=flat&label=Star&maxAge=86400) |
| [trep](http://murpheylab.github.io/trep/) | rigid | dm, trj-opt | C, Python | GPL-3.0 | [github](https://github.com/MurpheyLab/trep) | ![trep](https://img.shields.io/github/stars/MurpheyLab/trep.svg?style=flat&label=Star&maxAge=86400) |
| qu3e | rigid | - | C++ | Zlib | [github](https://github.com/RandyGaul/qu3e) | ![qu3e](https://img.shields.io/github/stars/RandyGaul/qu3e.svg?style=flat&label=Star&maxAge=86400) |

For simplicity, shortened names are used to represent the supported models and features as

* Supported Models
  * rigid: rigid bodies
  * soft: soft bodies
  * aero: aerodynamics
  * granular: granular materials (like sand)
  * fluid: fluid dynamics
  * vehicles
  * uav: unmanned aerial vehicles (like drones)
  * medical
  * molecules
  * parallel: parallel mechanism (like Stewart platform)

* Features on Simulation, Analysis, Planning, Control Design
  * dm: [discrete mechanics](https://www.cambridge.org/core/journals/acta-numerica/article/div-classtitlediscrete-mechanics-and-variational-integratorsdiv/C8F45478A9290DEC24E63BB7FBE3CEB5)
  * ik: [inverse kinematics](https://en.wikipedia.org/wiki/Inverse_kinematics) solvers
  * id: [inverse dynamics](https://en.wikipedia.org/wiki/Inverse_dynamics)
  * slam: [simultaneous localization and mapping](https://en.wikipedia.org/wiki/Simultaneous_localization_and_mapping)
  * trj-opt: trajectory optimization
  * plan: motion planning algorithms
  * cv: computer visionn
  * urdf: [urdf](http://wiki.ros.org/urdf) parser
  * sdf: [sdf](http://sdformat.org/) parser

### [Machine Learning](#awesome-robotics-libraries)

  * [OpenAI Gym](https://gym.openai.com/) ([github](http://github.com/openai/gym) ![gym](https://img.shields.io/github/stars/openai/gym.svg?style=flat&label=Star&maxAge=86400)) - A toolkit for developing and comparing reinforcement learning algorithms. It supports teaching agents everything from walking to playing games like Pong or Go.
  * OpenAI Gym with DART ([github](http://github.com/DartEnv/dart-env) ![dart-env](https://img.shields.io/github/stars/DartEnv/dart-env.svg?style=flat&label=Star&maxAge=86400))

### [Motion Planning](#awesome-robotics-libraries)

* [Aikido](https://github.com/personalrobotics/aikido) ([github](https://github.com/personalrobotics/aikido) ![aikido](https://img.shields.io/github/stars/personalrobotics/aikido.svg?style=flat&label=Star&maxAge=86400)) - A C++ library for solving robotic motion planning and decision making problems.
* [CuiKSuite](http://www.iri.upc.edu/people/porta/Soft/CuikSuite2-Doc/html) - A set of applications to solve position analysis and path planning problems with applications mainly to robotics, but also to molecular biology
* [HPP](https://humanoid-path-planner.github.io/hpp-doc/) ([github](https://github.com/humanoid-path-planner)) - Humanoid Path Planner: a C++ Software Developement Kit implementing path planning for kinematic chains in environments cluttered with obstacles.
* [MoveIt!](http://moveit.ros.org/) ([github](https://github.com/ros-planning/moveit) ![moveit](https://img.shields.io/github/stars/ros-planning/moveit.svg?style=flat&label=Star&maxAge=86400)) - State of the art software for mobile manipulation, incorporating the latest advances in motion planning, manipulation, 3D perception, kinematics, control and navigation.
* [OMPL](http://ompl.kavrakilab.org/) ([bitbucket](https://bitbucket.org/ompl/ompl), [github](https://github.com/ompl/ompl) ![ompl](https://img.shields.io/github/stars/ompl/ompl.svg?style=flat&label=Star&maxAge=86400)) - The Open Motion Planning Library.

###### Motion Optimizer

* [trajopt](http://rll.berkeley.edu/trajopt/doc/sphinx_build/html/) ([github](https://github.com/joschu/trajopt) ![joschu/trajopt](https://img.shields.io/github/stars/joschu/trajopt.svg?style=flat&label=Star&maxAge=86400)) - A software framework for generating robot trajectories by local optimization.

###### Nearest Neighbor

* [Cover-Tree](http://hunch.net/~jl/projects/cover_tree/cover_tree.html) ([github](https://github.com/DNCrane/Cover-Tree) ![Cover-Tree](https://img.shields.io/github/stars/DNCrane/Cover-Tree.svg?style=flat&label=Star&maxAge=86400)) - A well-documented C++ implementation of the cover tree datastructure for quick k-nearest-neighbor search
  * [Faster cover tree](http://machinelearning.wustl.edu/mlpapers/paper_files/icml2015_izbicki15.pdf) by Mike Izbicki et al., ICML 2015.
* [FLANN](http://www.cs.ubc.ca/research/flann/) ([github](https://github.com/mariusmuja/flann) ![flann](https://img.shields.io/github/stars/mariusmuja/flann.svg?style=flat&label=Star&maxAge=86400)) - Fast Library for Approximate Nearest Neighbors
* [nanoflann](http://www.cs.ubc.ca/research/flann/) ([github](https://github.com/jlblancoc/nanoflann) ![nanoflann](https://img.shields.io/github/stars/jlblancoc/nanoflann.svg?style=flat&label=Star&maxAge=86400)) - C++ header-only library for Nearest Neighbor (NN) search wih KD-trees

###### 3D Mapping

* [OctoMap](http://octomap.github.io/) ([github](https://github.com/OctoMap/octomap) ![octomap](https://img.shields.io/github/stars/OctoMap/octomap.svg?style=flat&label=Star&maxAge=86400)) - An Efficient Probabilistic 3D Mapping Framework Based on Octrees. Contains the main OctoMap library, the viewer octovis, and dynamicEDT3D.

* voxblox ([github](https://github.com/ethz-asl/voxblox) ![voxblox](https://img.shields.io/github/stars/ethz-asl/voxblox.svg?style=flat&label=Star&maxAge=86400)) - A library for flexible voxel-based mapping, mainly focusing on truncated and Euclidean signed distance fields.

### [Optimization](#awesome-robotics-libraries)

###### Nonlinear Programming

* [CasADi](https://github.com/casadi/casadi/wiki) ([github](https://github.com/casadi/casadi) ![casadi](https://img.shields.io/github/stars/casadi/casadi.svg?style=flat&label=Star&maxAge=86400)) - A symbolic framework for algorithmic (a.k.a. automatic) differentiation and numeric optimization
* [Ceres Solver](http://ceres-solver.org/) ([github](https://github.com/ceres-solver/ceres-solver) ![ceres-solver](https://img.shields.io/github/stars/ceres-solver/ceres-solver.svg?style=flat&label=Star&maxAge=86400)) - A large scale non-linear optimization library . Ceres Solver has been used in production at Google for more than four years now. It is clean, extensively tested and well documented code that is actively developed and supported.
* [Ipopt](https://projects.coin-or.org/Ipopt) ([github](https://github.com/coin-or/Ipopt) ![Ipopt](https://img.shields.io/github/stars/coin-or/Ipopt.svg?style=flat&label=Star&maxAge=86400)) - Ipopt (Interior Point OPTimizer, pronounced eye-pea-Opt) is a software package for large-scale ​nonlinear optimization.
* [NLopt](http://ab-initio.mit.edu/wiki/index.php/NLopt) ([github](https://github.com/stevengj/nlopt) ![nlopt](https://img.shields.io/github/stars/stevengj/nlopt.svg?style=flat&label=Star&maxAge=86400)) - NLopt is a free/open-source library for nonlinear optimization, providing a common interface for a number of different free optimization routines available online as well as original implementations of various other algorithms.
* [SCS](http://web.stanford.edu/~boyd/papers/scs.html) ([github](https://github.com/cvxgrp/scs) ![scs](https://img.shields.io/github/stars/cvxgrp/scs.svg?style=flat&label=Star&maxAge=86400)) - SCS (Splitting Conic Solver) is a numerical optimization package for solving large-scale convex cone problems, based on our paper [Conic Optimization via Operator Splitting and Homogeneous Self-Dual Embedding](http://www.stanford.edu/~boyd/papers/scs.html).

### [Robot Modeling](#awesome-robotics-libraries)

###### Robot Model Description Format
* [SDF](http://sdformat.org/) - XML format that describes objects and environments for robot simulators, visualization, and control. ([bitbucket](https://bitbucket.org/osrf/sdformat))
* [urdf](http://wiki.ros.org/urdf) - XML format for representing a robot model. ([github](https://github.com/ros/urdfdom))

###### Utility to Build Robot Models
* phobos - An add-on for Blender allowing to create URDF and SMURF robot models in a WYSIWYG environment. ([github](https://github.com/rock-simulation/phobos) ![phobos](https://img.shields.io/github/stars/rock-simulation/phobos.svg?style=flat&label=Star&maxAge=86400))

### [Robot Platform](#awesome-robotics-libraries)

* [ROS](http://www.ros.org/) ([github repos](http://wiki.ros.org/Tickets)) - A set of software libraries and tools that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project.
* [YARP](http://www.yarp.it/) ([github](https://github.com/robotology/yarp)) - A library and toolkit for communication and device interfaces, used on everything from humanoids to embedded devices.

### [SLAM](#awesome-robotics-libraries)

* Cartographer ([github](https://github.com/googlecartographer/cartographer) ![cartographer](https://img.shields.io/github/stars/googlecartographer/cartographer.svg?style=flat&label=Star&maxAge=86400)) - A system that provides real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms and sensor configurations.
* [DSO](https://vision.in.tum.de/research/vslam/dso) ([github](https://github.com/JakobEngel/dso) ![dso](https://img.shields.io/github/stars/JakobEngel/dso.svg?style=flat&label=Star&maxAge=86400)) - DSO is a novel direct and sparse formulation for Visual Odometry.
* ElasticFusion ([github](http://github.com/mp3guy/ElasticFusion) ![ElasticFusion](https://img.shields.io/github/stars/mp3guy/ElasticFusion.svg?style=flat&label=Star&maxAge=86400)) - Real-time dense visual SLAM system capable of capturing comprehensive dense globally consistent surfel-based maps of room scale environments explored using an RGB-D camera.
* Kintinuous ([github](http://github.com/mp3guy/Kintinuous) ![Kintinuous](https://img.shields.io/github/stars/mp3guy/Kintinuous.svg?style=flat&label=Star&maxAge=86400)) - Real-time dense visual SLAM system capable of producing high quality globally consistent point and mesh reconstructions over hundreds of metres in real-time with only a low-cost commodity RGB-D sensor.
* [LSD-SLAM](https://vision.in.tum.de/research/vslam/lsdslam) ([github](http://github.com/tum-vision/lsd_slam) ![lsdslam](https://img.shields.io/github/stars/tum-vision/lsd_slam.svg?style=flat&label=Star&maxAge=86400)) - LSD-SLAM is a novel approach to real-time monocular SLAM. It is fully direct (i.e. does not use keypoints / features) and creates large-scale, semi-dense maps in real-time on a laptop.
* ORB-SLAM2 ([github](http://github.com/raulmur/ORB_SLAM2) ![ORB_SLAM2](https://img.shields.io/github/stars/raulmur/ORB_SLAM2.svg?style=flat&label=Star&maxAge=86400)) - A real-time SLAM library for Monocular, Stereo and RGB-D cameras that computes the camera trajectory and a sparse 3D reconstruction (in the stereo and RGB-D case with true scale).
* [SRBA](http://mrpt.github.io/srba/) ([github](http://github.com/MRPT/srba) ![srba](https://img.shields.io/github/stars/MRPT/srba.svg?style=flat&label=Star&maxAge=86400)) - Sparser Relative Bundle Adjustment (SRBA) is a header-only C++ library for solving SLAM/BA in relative coordinates with flexibility for different submapping strategies and aimed at constant time local graph update. BSD 3-Clause License.

### [Vision](#vision)
* [ViSP](http://visp.inria.fr/) ([github](https://github.com/lagadic/visp) ![lagadic/visp](https://img.shields.io/github/stars/lagadic/visp.svg?style=flat&label=Star&maxAge=86400)) - A cross-platform library that allows prototyping and developing applications using visual tracking and visual servoing technics at the heart of the researches done by Inria Lagadic team.

## [Other Awesome Lists](#awesome-robotics-libraries)

* [Awesome Robotics](https://github.com/Kiloreux/awesome-robotics) - This is a list of various books, courses and other resources for robotics. It's an attempt to gather useful material in one place for everybody who wants to learn more about the field.
* [Awesome Robotics](https://github.com/ahundt/awesome-robotics) - Awesome links and software libraries that are useful for robots.
* [Awesome Artificial Intelligence](https://github.com/owainlewis/awesome-artificial-intelligence)
* [Awesome Collision Detection](https://github.com/jslee02/awesome-collision-detection)
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
* [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
* [Awesome Gazebo](https://github.com/fkromer/awesome-gazebo)

### added by Mark
* [another rob list](https://github.com/mithi/robotics-coursework)

## [Contributing](#awesome-robotics-libraries)

Contributions are very welcome! Please read the [contribution guidelines](https://github.com/jslee02/awesome-robotics-libraries/blob/master/CONTRIBUTING.md) first. Also, please feel free to report any error.

## [License](#awesome-robotics-libraries)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
