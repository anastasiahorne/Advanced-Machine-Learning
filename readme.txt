1.	Anastasia Horne, CWID: 10867499

2.	The program is run in Python (with a PyTorch Dependency) using a ‘.ipynb’  notebook. 
    a.	A list of all the dependencies and their versions can be found in “environment.yml”

3.	Create a Conda Environment from the “environment.yml” file:
    a.	 Open a terminal (or Anaconda Prompt if on Windows).
    b.	Navigate to the directory containing the “environment.yml” file.
    c.	Run the command: “conda env create -f environment.yml”. This will create a new conda environment with all the dependencies specified in the “environment.yml” file.

4.	Activate the New Environment:
    a.	Once the environment is created, activate it using the command: “conda activate environment_name”, where “environment.yml” is the name specified in the “environment.yml” file.

5.	Open the Jupyter Notebook:
    a.	With the environment activated, launch Jupyter Notebook by running “jupyter notebook” in the terminal. This will open Jupyter in a web browser.
    b.	Navigate to and open the ‘.ipynb’ notebook file.

6.	Run the Notebook:
    a.	The Ice Velocity dataset is cloud hosted:
        i.	Create a free account in order to log in within the python notebook:
            1.	https://urs.earthdata.nasa.gov/
            2.	Python code will prompt you for the username and password used above.
            3.	Note to grader: If you would prefer I send you my username and password let me know.
    b.	Open the notebook and edit the directories as needed.
        i.	Navigate to the “Import Datasets” section and change the “Directory” variable in the first code block to fit the directory of the data files on your system.
        ii.	 In “Import Datasets” find code subsections title with a ‘*’ and edit the directories appropriately.
    c.	Run the Notebook!
