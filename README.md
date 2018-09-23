# Grahlab-Installation-

 Steps Required for graphlab Installation
 
# steps required to install the graphlab in linux

I have been try alot for installation but got import graph lab error 

1.steps:-goto this
           
           link https://turi.com/download/install-graphlab-create.html
2.steps:-there is two option of installation 

Option 1: Install into Anaconda Python Environment (recommended)
     
     1.1:Step 1: Download Anaconda2 v4.0.0
      

Step 2: Install Anaconda

# Run Anaconda2 v4.0.0 installer.
    
    bash /path to download file/Anaconda2-4.0.0-Linux-x86_64.sh

Step 3: Create conda environment

# Create a new conda environment with Python 2.7.x
       
       export PATH=~/anaconda/bin:$PATH                          // to check other steps available if then type this 
   
     conda create -n gl-env python=2.7 anaconda=4.0.0

# Activate the conda environment
    
    source activate gl-env

Step 4: 
      
      Ensure pip version >= 7

# Ensure pip is updated to the latest version
# miniconda users may need to install pip first, using 'conda install pip'
    
    conda update pip

Step 5: Install GraphLab Create

# Install your licensed copy of GraphLab Create
     pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/your registered email address here/your product      key here/GraphLab-Create-License.tar.gz

Step 4: Ensure installation of IPython and IPython Notebook

# Install or update IPython and IPython Notebook
      conda install ipython-notebook


Upgrade to GraphLab Create with GPU Acceleration

GraphLab Create on Linux can be upgraded to support multiple NVIDIA GPUs. Applying GPUs to computation can significantly improve performance of the Neural Network Classifier.



Option 2:
              
              Install in Python environment using virtualenv
The below instructions assume an existing Python 2.7.x (64-bit) environment and virtualenv is already installed on your machine. GraphLab Create installation requires pip version >= 7. IPython Notebook is recommended for getting the most out our code samples.


Execute the following shell commands:

Step 1: Create and activate a new virtual environment (recommended)

# Create a virtual environment named e.g. gl-env
      virtualenv gl-env

# Activate the virtual environment
       source gl-env/bin/activate

Step 2: Ensure pip version >= 7

# Make sure pip is up to date
       pip install --upgrade pip

Step 3: Ensure installation of IPython and IPython Notebook

# Install IPython Notebook (optional)
      pip install "ipython[notebook]"

Step 4: Ensure pip version >= 7

# Ensure pip is updated to the latest version
# miniconda users may need to install pip first, using 'conda install pip'
    conda update pip

Step 5: Install GraphLab Create

# Install your licensed copy of GraphLab Create
     pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/your registered email address here/your product key here/GraphLab-Create-License.tar.gz

Step 4: Ensure installation of IPython and IPython Notebook

# Install or update IPython and IPython Notebook
      conda install ipython-notebook
     ------------------------------2 ways of installation --------------------------
     
Option 2: 
      Install in Python environment using virtualenv
The below instructions assume an existing Python 2.7.x (64-bit) environment and virtualenv is already installed on your machine. GraphLab Create installation requires pip version >= 7. IPython Notebook is recommended for getting the most out our code samples.


Execute the following shell commands:

Step 1: Create and activate a new virtual environment (recommended)

# Create a virtual environment named e.g. gl-env
       virtualenv gl-env

# Activate the virtual environment
     source gl-env/bin/activate

Step 2: Ensure pip version >= 7

# Make sure pip is up to date
     pip install --upgrade pip

Step 3: Ensure installation of IPython and IPython Notebook

# Install IPython Notebook (optional)
      pip install "ipython[notebook]"

Step 4: 
      Install GraphLab Create

# Install your licensed copy of GraphLab Create
      pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/your registered email address here/your product key here/GraphLab-Create-License.tar.gz

--------------------------------------------------------------------------------------------------------------------------------------------

      
