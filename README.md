Hague ML Prep

This repository contains all necessary files for preparing for the Artificial Intelligence: Machine and Statistical Learning course. It includes environment setup files and dependencies to ensure a smooth setup on a Mac.
Setup Instructions
1. Clone the Repository

   
        git clone https://github.com/eireye/hague_ml_prep.git
        cd hague_ml_prep
   
3. Activate the Existing .venv Environment

Since the virtual environment is already created, simply activate it:

    source .venv/bin/activate

3. Install Dependencies (If Needed)

If any packages are missing, install them:

    pip install -r requirements.txt
    
4. Verify Installation

        python -c "import numpy; import pandas; import sklearn; print('Setup successful!')"
    

5. Deactivating the Environment

To deactivate the environment:

    deactivate

Notes
If you install additional packages, update the requirements.txt:

    pip freeze > requirements.txt


