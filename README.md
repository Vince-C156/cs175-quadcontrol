# Installation
git clone https://github.com/NVIDIA-Omniverse/OmniIsaacGymEnvs.git

For Linux: alias PYTHON_PATH=~/.local/share/ov/pkg/isaac_sim-*/python.sh
For Windows: doskey PYTHON_PATH=C:\Users\user\AppData\Local\ov\pkg\isaac_sim-*\python.bat $*
For IsaacSim Docker: alias PYTHON_PATH=/isaac-sim/python.sh

PYTHON_PATH -m pip install -e .
