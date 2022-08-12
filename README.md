# CS4243 (Miniconda Environment Setup)
National University of Singapore, CS4243: Computer Vision and Pattern Recognition


### For Mac OS (M1 & M2)

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
   conda env create -f environment_mac.yml
   
   # Activate the environment
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook
   ```


### For Windows 

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


### Verify the installation
```sh
   # Activate the conda env
   conda activate CS4243

   # Run the notebooks in Chrome
   jupyter notebook

   # Run the test.ipynb
   
   ```