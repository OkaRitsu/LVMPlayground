# LVMPlayground
## Setup
```
conda create --name lvm python=3.10 -y
conda activate lvm
pip install torch torchvision torchaudio
```
## Data preparation
### SynDrone
refer to: https://github.com/LTTM/Syndrone
```
wget -P data https://lttm.dei.unipd.it/paper_data/syndrone/Town01_Opt_120_color.zip
unzip -d data data/Town01_Opt_120_color.zip
```
### InsPLAD-fault
refer to: https://github.com/andreluizbvs/InsPLAD

Download from [Google Drive](https://drive.google.com/drive/folders/1psHiRyl7501YolnCcB8k55rTuAUcR9Ak?usp=drive_link).
```
 unzip -d data data/InsPLAD-fault-20250329T060058Z-001.zip 
 unzip -d data/InsPLAD-fault/ data/InsPLAD-fault/supervised_fault_classification.zip
```