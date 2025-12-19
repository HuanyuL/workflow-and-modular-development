# Team Collaborative Workflow and Modular System Development Guide

Author: [Huanyu Li](https://github.com/HuanyuL)


This is the repository for **MRAC01 25/26 workshop 2.1**. The seminar focuses on the "infrastructure" of a **robotic perception project**. Guide students how to allow multiple members to code simultaneously without conflict. Understand the complexity of hardware + software integration and learn how to use the software tools for developing projects in a standard environment.

---

## Table of Contents
1. [Getting Started](#getting-started)
2. [Workshop Materials](#workflow-instructions)
3. [Troubleshooting](#troubleshooting)
4. [License](#license)

---

## Getting Started
### Prerequisites
Before starting, you must have:
- **A Windows 11 or Linux laptop** (reserve at least 60GB free space in your "C" Disk)
- **Github account**
- **Python installed**(basic knowledge required)
- **VSCode**

You should understand:
- Variables, lists and dictionaries
- Functions and loops
- Reading and writing files in Python
- Navigating the file system using the command line (using `cd`, `ls`,`dir`, `mkdir`, etc. in PowerShell or Command Prompt)

**⚠️ ⚠️ ⚠️ Important ⚠️ ⚠️ ⚠️** 

All workshop tasks must be completed using the **terminal or command prompt**. GUI downloads or clicks are not allowed.  

**🚨 Students who do not have the required Python knowledge or command-line skills will fall behind in the workshop at the very beginning. It is essential to come prepared with these basic skills.**

**🚨 Do NOT attempt to install Linux or set up a dual-boot system if you have never done it before.**  

Installing Linux alongside Windows can be risky: it may accidentally overwrite or delete important Windows files, and recovering your system can be difficult.


### Installation
All necessary software (Git, docker, virtual environments, etc.) will be installed **together with the faculty during the workshop**.  

- [Git](https://git-scm.com/)
- [Anaconda](https://www.anaconda.com/download)
- [WSL2](https://learn.microsoft.com/en-us/windows/wsl/install)
- [Docker](https://docs.docker.com/engine/)

---

## Workshop Materials

All the materials are orgnized by day. Each folder contains:

- `README.md` - overview and instructions
- `doc` - slides and images
- `excercises` - hands-on tasks

You can jump to the worksop material from the following links:
- [Day 1: Introduction & Setup](workshop-materials/DAY1/README.md)
- [Day 2: Github Collabrative Workflow & WSL Basic](workshop-materials/DAY2/README.md)
- [Day 3: Environments, Docker & Advanced Python](workshop-materials/DAY3/README.md)
- [Day 4: Robotic Kinematics & Perception Systems](workshop-materials/DAY4/README.md)
- [Day 5: ROS 2 Tour & Motion Planning with MoveIt](workshop-materials/DAY5/README.md)

## Troubleshooting

Here are some common problems students may encounter during the workshop, and how to fix them.

### 1. No enough space in your C: drive
**Solution**
- Free up space by deleting unnecessary files (temporary files, downloads, old projects).  
- Uninstall heavy softwares that you don't use often, or migrate it to another disk.
- Enlarge your C drive by extending volumns with tools. You can find [tutorials](https://www.youtube.com/watch?v=YtlxeBYxMjQ) here, but make sure you understand risk before you do it.

### 2. GUI Access on WSL2
**Solution**
Windows Subsystem for Linux (WSL) now supports running Linux GUI applications (X11 and Wayland) on Windows in a fully integrated desktop experience.

- You will need to be on Windows 10 Build 19044+ or Windows 11 to access this feature.
- To run Linux GUI apps, you should first install the driver matching your system below. This will enable you to use a virtual GPU (vGPU) so you can benefit from hardware accelerated OpenGL rendering.
    - [Intel GPU driver](https://www.intel.com/content/www/us/en/download-center/home.html)
    - [AMD GPU driver](https://www.amd.com/es.html)
    - [NVIDIA GPU driver](https://www.nvidia.com/en-us/drivers/)

## License
This project is licensed under the MIT License. See the LICENSE file for details.





