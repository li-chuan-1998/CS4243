# CS4243 (Miniconda/Miniforge Environment Initialisation)
National University of Singapore, CS4243: Computer Vision and Pattern Recognition, lab group B4.


### Verify the installation
```sh
   # Activate the conda env
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook

   # Run the test.ipynb

   ```


### For Mac OS (intel, M1/M2) - without GPU support

```sh
   # Do all of these in the terminal

   # Conda installation
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -o miniconda.sh -J -L -k
   chmod +x miniconda.sh
   ./miniconda.sh

   # Clone GitHub repo
   git clone https://github.com/li-chuan-1998/CS4243.git
   cd CS4243

   # Install python libraries
   conda env create -f environment_mac_x86.yml
   
   # Activate the environment
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook
   ```

#### This script will install the latest compatible packages. If you run into any difficulties in the installation, here is the last tested working versions (for your reference):

```sh
Python 3.9.13 | packaged by conda-forge | (main, May 27 2022, 17:01:00)
[Clang 13.0.1 ]
Tensorflow Version: 2.9.2
Keras Version: 2.9.0
scikit-learn version is 1.1.2.
pandas version is 1.4.3.
OpenCV Version: 4.6.0
```


### For Mac OS (M1/M2) - with GPU support

```sh
   
   # Do all of these in the terminal
   # Miniforge donwload
   curl https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-MacOSX-arm64.sh -O
   chmod +x Miniforge3-MacOSX-arm64.sh
   source ./miniconda.sh

   # Clone GitHub repo
   git clone https://github.com/li-chuan-1998/CS4243.git
   cd CS4243

   # Install python libraries
   conda env create -f environment_mac_arm.yml
   
   # Activate the environment
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook
   ```

#### This script will install the latest compatible packages. If you run into any difficulties in the installation, here is the last tested working versions (for your reference):

```sh
Python 3.9.13 | packaged by conda-forge | (main, May 27 2022, 17:00:52) 
[Clang 13.0.1 ]
Tensorflow Version: 2.9.1
Keras Version: 2.9.0
scikit-learn version is 1.1.2.
pandas version is 1.4.3.
OpenCV Version: 4.6.0
```


### For Windows - without GPU support

```sh
   # Install Anaconda 
   https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

   # Open an Anaconda Terminal 
   Go to Application => Anaconda3 => Anaconda Cmd Prompt 

   # Install git & clone repo: Type in terminal
   conda install git 
   git clone https://github.com/li-chuan-1998/CS4243.git
   cd CS4243

   # Install python libraries
   conda env create -f environment_win10.yml
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook
   ```

#### This script will install the latest compatible packages. If you run into any difficulties in the installation, here is the last tested working versions (for your reference):
```sh
Python 3.9.13 | packaged by conda-forge | (main, May 27 2022, 16:50:36) [MSC v.1929 64 bit (AMD64)]
Tensorflow Version: 2.9.0
Keras Version: 2.9.0
scikit-learn version is 1.1.2.
pandas version is 1.4.3.
OpenCV Version: 4.6.0
```


### For Windows - with GPU support (tested only on RTX 30 series card)

```sh
   # Install Anaconda 
   https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

   # Open an Anaconda Terminal 
   Go to Application => Anaconda3 => Anaconda Cmd Prompt 

   # Install git & clone repo: Type in terminal
   conda install git 
   git clone https://github.com/li-chuan-1998/CS4243.git
   cd CS4243

   # Install python libraries
   conda env create -f environment_win10_gpu.yml
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook
   ```

#### This script will install the latest compatible packages. If you run into any difficulties in the installation, here is the last tested working versions (for your reference):
```sh
Python 3.9.13 | packaged by conda-forge | (main, May 27 2022, 16:50:36) [MSC v.1929 64 bit (AMD64)]
Tensorflow Version: 2.9.0
Keras Version: 2.9.0
scikit-learn version is 1.1.2.
pandas version is 1.4.3.
OpenCV Version: 4.6.0
```