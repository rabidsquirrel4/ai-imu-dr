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