Week0-bhavatarini
The following tools were installed for RTL synthesis, simulation, circuit analysis, and layout design. Below are the installation steps and verification commands.
# 1. Yosys – RTL Synthesis Tool
Purpose: Converts RTL code into gate-level representations.
Yosys
code:
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys 
$ sudo apt install make # (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make 
$ sudo make install

![yosys](https://github.com/user-attachments/assets/34a8ac24-55ac-4f65-b73c-599ea5bb176a)




# 2. Iverilog – Verilog Simulator
Purpose: Compiles and simulates Verilog designs for functional verification.
code:
$ sudo apt-get install iverilog


![iverilog](https://github.com/user-attachments/assets/2d83a4eb-e37f-4e62-a3f1-0aeb1050e761)




# 3.GTKWave – Waveform Viewer
Purpose: Analyzes and visualizes simulation waveforms for debugging.
code:
$ sudo apt update
$ sudo apt install gtkwave



![gtkwave](https://github.com/user-attachments/assets/b0a652e6-ffe8-4d3b-9db7-1cc981073879)



# 4.Ngspice – Circuit Simulator
Purpose: Performs analog and mixed-signal circuit simulation.
code:
$ sudo apt update
$ sudo apt install ngspice


![ngspice](https://github.com/user-attachments/assets/233c0c9a-881f-436b-9df2-fc447ef5a7a9)


# 5.Magic VLSI – Layout Tool
Purpose: Creates, edits, and analyzes VLSI layouts with DRC capabilities.
Magic VLSI Installation
Magic VLSI is an open-source VLSI layout tool widely used for IC design, DRC, and visualization.
CODE:
# Install required dependencies
sudo apt-get install m4
sudo apt-get install tcsh
sudo apt-get install csh
sudo apt-get install libx11-dev
sudo apt-get install tcl-dev tk-dev
sudo apt-get install libcairo2-dev
sudo apt-get install mesa-common-dev libglu1-mesa-dev
sudo apt-get install libncurses-dev

# Clone Magic repository
git clone https://github.com/RTimothyEdwards/magic
cd magic

# Configure build
./configure

# Build Magic
make

# Install system-wide
sudo make install


![magic](https://github.com/user-attachments/assets/eb33bf5c-87c1-44f6-acfe-ef726edf5888


OPENlane:

![open](https://github.com/user-attachments/assets/552f25b9-ca3d-4d60-ab0c-d92ffef78648)











