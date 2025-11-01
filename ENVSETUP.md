# CONDA
conda create -n aiimu python=3.5 matplotlib numpy termcolor scipy pytorch

nvcc --version

<!-- pip install torch torchvision --index-url https://download.pytorch.org/whl/cu126 -->
pip install NavPy

# Download datasets
wget "https://github.com/user-attachments/files/17930695/data.zip"
unzip data.zip -d ai-imu-dr
rm data.zip
mkdir ai-imu-dr/results




# Test
cd ai-imu-dr/src
## If data directory not already there, mkdir:
mkdir ../data
python3 main_kitti.py


# Attempting to switch VSCode Python Extension Version
version 2020.9.114305
- no signiture associated with this version
I have no idea how to work this starting over

# Installing extension Debugpy Old
- did not activate

# Trying another environment with python 3.13
conda create -n aiimucurr matplotlib numpy termcolor scipy pytorch
pip install NavPy