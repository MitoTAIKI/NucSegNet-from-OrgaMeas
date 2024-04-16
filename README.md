# NucSegNet: A deep learning-based tool for nuclei segmentation
Please find the paper here: [OrgaMeas: A high-throughput image analysis pipeline optimized for effectively measuring organellar dynamics in live cells](URL)

## What is this?
NucSegNet is an user-friendly tool for nuclei segmentation that was developed by utilization of [**the advanced mode of MitoSegNet**](https://github.com/MitoSegNet/MitoS-segmentation-tool).<br>

## How to use
At first, please download our pre-trained model of NucSegNet on [this site](URL).<br>
If you want to download pre-trained model of MitoSegNet, which can precisely segment lysosomes or lipid droplets as well as mitochondria, please visit [this site](https://zenodo.org/record/3539340#.Xd-oN9V7lPY).<br>

### Windows users
To download the MitoS (GPU) for Windows tool visit [this site](https://zenodo.org/record/3549840#.Xd-ol9V7lPY).<br>
To download the MitoS (CPU) for Windows tool visit [this site](https://zenodo.org/record/3553597#.Xd-opNV7lPY).<br>

### Linux users
To download the MitoS (GPU) for Linux tool visit [this site](https://zenodo.org/record/3556431#.XeAHNtV7lPY).<br>
To download the MitoS (CPU) for Linux tool visit [this site](https://zenodo.org/record/3556714#.XeAHUdV7lPY).<br>

### MacOS users
We highly recommend to use Windows or Linux OS because the developer of MitoSegNet has not provided MitoSegNet software, so you should install the code on their local machine and create environment for using MitoSegNet.<br>
If you have to or want to use MacOS, please check the under instruction to implement MitoSegNet yourself on your local PC.<br>

**1.** Install Anaconda on MacOS (https://docs.anaconda.com/free/anaconda/install/mac-os/)<br>
[This web site](https://gpt4jp.com/740/) provides an easy-to-understand instruction in Japanese.

**2.** Install all of codes available on this GitHub site<br>

**3.** Create an environment for using MitoSegNet. Open terminal and run the under code!<br>
<pre>
conda create -n MitoSegNet python==3.7
conda activate MitoSegNet
pip install keras==2.3.0
conda install tensorflow==1.14.0
pip install opencv-python
conda install matplotlib
conda install scikit-image
conda install pandas
conda install seaborn
sudo pip uninstall h5py
sudo pip install h5py==2.10.0
</pre>

**4.** Test your own data. Open terminal, move to a directory, which you save the code (2.Install all of codes available on this GitHub site), and run the under code!<br>
<pre>
conda activate MitoSegNet
python MitoS_Main_GPU.py (or MitoS_Main_CPU.py)
</pre>





