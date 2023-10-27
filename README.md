# tensorflow_m1_2023


##### 1. Step 1 Install Miniconda Apple M1 64-bit
  - https://docs.conda.io/projects/miniconda/en/latest/

#### 2. Download this YML file  and then use the YML file to create an environment named tensorflow.
  - conda env create -f tools.yml -n tensorflow

#### 3. Activate your environment 
  -  conda activate tensorflow

#### 4. Add Jupyter support to your new environment
 - python -m ipykernel install --user --name tensorflow --display-name "Python 3.10 (tensorflow)"

#### 5. Test your environment
 - conda activate tensorflow
 - jupyter notebook


