# Create a project with miniconda steps

1. Open miniconda shell 
2. Go to working directory
3. run commamd
    - conda create --prefix env *arg 
    *arg = numpy matplotlib jupyter pandas etc ...
    -- prefix : specify where to create the env folder, by default it will read the path to the working directory
4. run commamd following command to activate the working environment
    - conda activate path/to/env
5 to deactivate the working environment, run commamd:
    - conda deactivate 


# Work with jupiter notebook
1. add jupyter to the environment if not already present
    - conda install jupyter
2- launch jupyter with command
    - jupyter notebook
--------
conda create -n conda-env
conda activate ./env