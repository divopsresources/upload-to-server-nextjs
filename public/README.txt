
After you have installed conda, close any open terminals you might have. Then open a new terminal and run the following command:

# 1. Create an environment with dependencies specified in env.yml:
    
    conda env create -f env.yml

# 2. Activate the new environment:
    
    conda activate flask

    
# 3. Inside the new environment, instatll IPython kernel so we can use this environment in jupyter notebook: 
    
    python -m ipykernel install --user --name flask


