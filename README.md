# Awesome Robotics System Design (and more)
Stuff I read to learn about robotics system & software design, engineering culture, etc.

## Blogs

- [Airbotics blog](https://www.airbotics.io/blog/)
    - [The landscape of software deployment in robotics](https://web.archive.org/web/20230330175041/https://www.airbotics.io/blog/software-deployment-landscape)
- [Apex.AI Blog](https://www.apex.ai/blog/)
    - [ADE—Ensuring that all developers in a project have a common, consistent development environment](https://www.apex.ai/post/ade-ensuring-that-all-developers-in-a-project-have-a-common-consistent-development-environment)
    - [Performance Testing in ROS 2](https://www.apex.ai/post/ade-ensuring-that-all-developers-in-a-project-have-a-common-consistent-development-environment)
    - [AUTOSAR and ROS 2 for Software-Defined Vehicle](https://www.apex.ai/post/autosar-and-ros-2-for-software-defined-vehicle)
- [Applied Intuition blog](https://blog.applied.co/)
    - [ISO 26262, SOTIF, and Simulation in Autonomy Systems](https://blog.applied.co/blog-post/iso26262-sotif-simulation)
    - [Quantifying Known and Unknown Metrics in ADAS and AV Development](https://blog.applied.co/blog-post/quantifying-knowns-and-unknowns)
- [Balena.io Blog](https://www.balena.io/blog/)
    - [OpenTelemetry for IoT Metrics](https://blog.balena.io/opentelemetry-for-iot-metrics/)
    - [Scale your Industrial deployment with IIoT Edge Gateways Managed by HiveMQ and balena](https://blog.balena.io/scale-industrial-deployment-iiot-edge-gateway-balena-hivemq/)
- [NVIDIA DEVELOPER Blog](https://developer.nvidia.com/blog)
    - [Design Your Robot on Hardware-in-the-Loop with NVIDIA Jetson](https://developer.nvidia.com/blog/design-your-robot-on-hardware-in-the-loop-with-nvidia-jetson/)
    - [Create Realistic Robotics Simulations with ROS 2 MoveIt and NVIDIA Isaac Sim](https://developer.nvidia.com/blog/create-realistic-robotics-simulations-with-ros-2-moveit-and-nvidia-isaac-sim/)
- [comma.ai blog](https://blog.comma.ai/)
    - [End-to-end lateral planning](https://blog.comma.ai/end-to-end-lateral-planning/)
    - [How openpilot works in 2021](https://blog.comma.ai/openpilot-in-2021/)
    - [Development speed over everything](https://blog.comma.ai/dev-speed/)
- [Cruise news](https://getcruise.com/news/)
    - [Cruise's Continuous Learning Machine Predicts the Unpredictable on San Francisco Roads](https://getcruise.com/news/blog/2020/cruises-continuous-learning-machine-predicts-the-unpredictable-on-san/)
    - [Building continuous integration & continuous delivery for autonomous vehicles on Google Cloud](https://cloud.google.com/blog/products/containers-kubernetes/how-cruise-tests-its-avs-on-a-google-cloud-platform)
- [PICKNIK blog](https://picknik.ai/blog/)
  - [Packaging ROS with GitHub Actions](https://picknik.ai/ros/debian/packaging/2023/02/27/packaging-ros-with-github-actions.html)
  - [Real-Time Programming: Priority Inversion](https://picknik.ai/real-time/priority%20inversion/roscon/2024/01/31/Real-Time_Programming_Priority_Inversion.html)
- [Foxglove blog](https://foxglove.dev/blog/)
    - [MCAP vs ROS 1 Bag Index Performance](https://foxglove.dev/blog/mcap-vs-ros1-bag-index-performance)

## Conferences

- [ROSCon](https://roscon.ros.org/)
    - [Physical Continuous Integration — CI on Real Robots!](https://vimeo.com/187705231), 2016
    - [Determinism in ROS – or when things break sometimes and how to fix it](https://www.youtube.com/watch?v=II8yCw5tPE0), 2017
    - [Concurrency in ROS 1 and ROS 2](https://vimeopro.com/osrfoundation/roscon-2019/video/379127709), 2019
    - [Tracing ROS 2 with ros2_tracing](https://vimeo.com/652633418), 2021
    - [Rosbag2 for Power Users](https://vimeo.com/649655219/75630c8cff), 2021
- [COMMA_CON](https://commacon.splashthat.com/)
    - [How We Test openpilot](https://youtu.be/vc6q9yIz6Ys?si=iJu4wZI87WTl37m5), 2021
- [Amazon re:MARS](https://remars.amazonevents.com/)
    - [Functional safety product development for autonomous mobile robots](https://youtu.be/0MV5fVxhM9M?si=tdXxzqkZzZH3T1X1), 2022 
- [BazelCon](https://roscon.ros.org/)
    - [Building Self Driving Cars with Bazel](https://youtu.be/fjfFe98LTm8?si=ekcExfMAgI7-GZDG), 2019
- [CppCon](https://cppcon.org/)
    - [Efficiency with Algorithms, Performance with Data Structures](https://www.youtube.com/watch?v=fHNmRkzxHWs)
    - [An Introduction to Tracy Profiler in C++](https://www.youtube.com/watch?v=ghXk3Bk5F2U), 2023
    - [BehaviorTree.CPP: Task Planning for Robots and Virtual Agents](https://www.youtube.com/watch?v=7MZDBihsR_U), 2023

## Design Docs

- [ROS2 Design](http://design.ros2.org/)
    - [ROS on ZeroMQ and Friends](https://design.ros2.org/articles/ros_with_zeromq.html)
    - [ROS on DDS](https://design.ros2.org/articles/ros_on_dds.html)
    - [Clock and Time](https://design.ros2.org/articles/clock_and_time.html)
    - [Managed nodes](https://design.ros2.org/articles/node_lifecycle.html)
    - [ROS 2 Launch System](https://design.ros2.org/articles/roslaunch.html)
    - [ROS 2.0 rosbags](https://github.com/ros2/design/blob/ros2bags/articles/rosbags.md)
- [Autoware's Design](https://autowarefoundation.github.io/autoware-documentation/main/design/)
    - [Planning component design](https://autowarefoundation.github.io/autoware-documentation/main/design/autoware-architecture/planning/)
- [openpilot](https://github.com/commaai/openpilot)

## Articles by Topics

### CI/CD

- [CI for Embedded Systems](https://jamesmunns.com/blog/hardware-ci-overview/)
- [Improving Embedded Software Development through CI/CD](https://medium.com/@tom_80522/improving-embedded-software-development-through-ci-cd-00e9628d0a12)

### Safety, Metrics, Standards

- [Amazon re:MARS 2022 - Functional safety product development for autonomous mobile robots](https://youtu.be/0MV5fVxhM9M?si=tdXxzqkZzZH3T1X1)
- [Functional Safety Assessment of an Automated Lane Centering System | NHTSA](https://www.nhtsa.gov/sites/nhtsa.gov/files/documents/13498a_812_573_alcsystemreport.pdf)
- [ISO 26262, SOTIF, and Simulation in Autonomy Systems](https://blog.applied.co/blog-post/iso26262-sotif-simulation)
- [Safety Performance Indicators (SPIs) for Autonomous Vehicles](https://users.ece.cmu.edu/~koopman/lectures/L124_SPI_vs_KPI.pdf)
- [A Safety Standard Approach for Fully Autonomous Vehicles](https://users.ece.cmu.edu/~koopman/pubs/Koopman19_WAISE_UL4600.pdf)
- [A Literature Review of Performance Metrics of Automated Driving Systems for On-Road Vehicles](https://www.frontiersin.org/articles/10.3389/ffutr.2021.759125)
- [Title Key performance indicators for assessing the impacts of automation in road transportation Results of the Trilateral key performance](https://www.connectedautomateddriving.eu/wp-content/uploads/2018/03/KPS-for-Assessing-Impact-CAD_VTT.pdf)
- [Quantifying Known and Unknown Metrics in ADAS and AV Development](https://blog.applied.co/blog-post/quantifying-knowns-and-unknowns)
- [ISO 26262-1:2018 - Road vehicles — Functional safety — Part 1: Vocabulary](https://www.iso.org/standard/68383.html)
- [ISO 11270:2014 - Intelligent transport systems — Lane keeping assistance systems (LKAS) — Performance requirements and test procedures](https://www.iso.org/standard/50347.html)

### Testing

- [Testing robotics systems in fast-paced startups](https://mjyc.github.io/2020/12/16/testing.html)
- [How Lessons From Self-Driving Can Improve LLMs](https://www.tidepool.so/2023/11/08/how-lessons-from-self-driving-can-improve-llms/)

### C/C++

- [An introduction to C++'s SFINAE concept: compile-time introspection of a class member](https://jguegant.github.io/blogs/tech/sfinae-introduction.html)
- [The C++ Bestiary](http://videocortex.io/2017/Bestiary/)
- [Reflection in C++ Part 1: The Present](https://gracicot.github.io/reflection/2018/04/03/reflection-present.html)
- [Challenge your performance intuition with C++ magic squares](https://wordsandbuttons.online/challenge_your_performance_intuition_with_cpp_magic_squares.html)
- [Brain Unrolling](http://videocortex.io/2019/Brain-Unrolling/)
- [C++ medley](https://docs.google.com/presentation/d/1syD-vSwfrGoRZXi8uybnP6qfU8tjcht0vJAdmrRU0_Y/edit)
- [Async stack traces in folly: Improving debugging in the developer lifecycle](https://developers.facebook.com/blog/post/2021/10/21/async-stack-traces-folly-improving-debugging-developer-lifecycle/)
- [The Danger of Atomic Operations](https://abseil.io/blog/01222022-atomic-operations)
- [In Defense Of Linked Lists](https://www.rfleury.com/p/in-defense-of-linked-lists)
- [coffeeintobugs](https://github.com/dallison/coffeeintobugs)
- [Coffee Into Bugs: Life After Threads, Coroutines](https://www.linkedin.com/pulse/coffee-bugs-life-after-threads-coroutines-dave-allison)
- [An easy-to-implement, arena-friendly hash map](https://nullprogram.com/blog/2023/09/30/)


## Resources

### Mindmaps & Diagrams

- [roadmap.sh](https://roadmap.sh/) - [Backend](https://roadmap.sh/backend) | [DevOps](https://roadmap.sh/devops)
- [scikit-learn - Choosing the right estimator](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)
- [The Map of Control Theory](https://engineeringmedia.com/)
- [Software Architecture Styles](https://images.app.goo.gl/YQPSrKNV8d7MeW176)

### University Courses 

with publically available slides and/or homeworks (problems).

- [University of Washington CSE 478: Autonomous Robotics](https://courses.cs.washington.edu/courses/cse478/20wi/)
- [University of Washington CSE 451: Operating Systems](https://courses.cs.washington.edu/courses/cse451/20au/)
- [University of California, Berkely CS 287 Advanced Robotics](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/)
- [University of Washington CSE 599g1: Introduction to Deep Learning](https://courses.cs.washington.edu/courses/cse599g1/19au/)
- [University of Washington CSE P576: Computer Vision](https://courses.cs.washington.edu/courses/csep576/18sp/)
- [MIT 6.4210/6.4212 - Robotic Manipulation](https://manipulation.csail.mit.edu/)

### System Design

- [The System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview)
- [Preparing for the Systems Design and Coding Interview](https://blog.pragmaticengineer.com/preparing-for-the-systems-design-and-coding-interviews/)
    - [How to best prepare for system design interviews | Top Tips for system design interviews preparation](https://www.youtube.com/watch?v=aht20iQXfRY)
    - [System Design Interview – Step By Step Guide](https://www.youtube.com/watch?v=bUHFg8CZFws)
    - [Systems Design Interview Guide](http://patrickhalina.com/posts/systems-design-interview-guide/?ref=blog.pragmaticengineer.com)

### Software Architecture

- [Software Architecture Guide](https://martinfowler.com/architecture/)
- [Refactoring.Guru](https://refactoring.guru/)

### Hands-on Exercise

- [LeetCode](https://leetcode.com/)
- [SadServers](https://sadservers.com/)

### Engineering in Organization

- [Spotify Engineering Culture - Part 1](https://youtu.be/Yvfz4HGtoPc)
- [The Scrum Guide](https://scrumguides.org/index.html)
- [Why you should stop using product roadmaps and try the GIST Framework](https://itamargilad.com/gist-framework/)
    - [GIST Planning](https://www.productplan.com/glossary/gist-planning/)
- [The Glue Engineer](https://noidea.dog/glue)
- [project-checklist by amilajack](https://github.com/amilajack/project-checklist)
- [Going from Junior -> Senior engineer in 2 years](https://careercutler.substack.com/p/going-from-junior-senior-engineer)
- [How to Lead a Project - as a Software Engineer](https://blog.pragmaticengineer.com/how-to-lead-a-project-in-software-development/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
