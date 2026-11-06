# 7899X · Over Under (2023–24)

Competition code for team 7899X’s VEX V5 robot, written in C++ with the VEX V5 SDK. It includes driver controls, autonomous routines for matches and Programming Skills, and custom PID control for straight drives, turns, and arcs.

## Where to start

| File | What it does |
| --- | --- |
| [`src/main.cpp`](src/main.cpp) | Calibrates the robot, registers the competition callbacks, and runs driver control. |
| [`src/autonomous.cpp`](src/autonomous.cpp) | Selects and runs match and skills routines. |
| [`src/drive.cpp`](src/drive.cpp) | Implements drivetrain primitives and PID motion control. |
| [`src/robotconfig.cpp`](src/robotconfig.cpp) | Maps motors, sensors, and pneumatics to the V5 hardware. |
| [`src/dashboard.cpp`](src/dashboard.cpp) | Displays controller and motor telemetry on the V5 Brain. |

The [makefile](makefile) and [`vex/`](vex) contain the VEXcode build rules and expect the VEX V5 SDK and toolchain.

[Team 7899X robotics showcase](https://www.xingruic.net/works/vex-robotics)
