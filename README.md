# egm722_assignment
A GitHub repository documenting work for the EGM722 assignment.

## Code Setup 
The Jupyter Notebook containing the code, and the data required for map building, are hosted on GitHub: https://github.com/haniaparzych/egm722_assignment.git

The datasets provided are, at the time of writing, the most up-to-date versions. 
The code should remain compatible with future updates to the data, provided that naming conventions are maintained as used in the current notebook.

### 1.	Clone Repository
To begin, clone the GitHub repository and navigate to its new directory on your local machine. To do this, open the terminal or command prompt and run:

`git clone https://github.com/haniaparzych/egm722_assignment.git`

`cd egm722_assignment`

The following files should be present in the directory:

•	Interactive_Database_Mapping.ipynb Jupyter Notebook containing the code;

•	environment.yml file to define the main dependencies for the code;

•	LICENSE licensing terms for code usage; and,

•	Data folder containing REPD data and spatial overlays.


### 2.	Set Up the Environment
To install the necessary dependencies for the code, create a new Conda environment using the provided environment.yml file:

`conda env create -f environment.yml`

This will install the following main dependencies: 

•	Python ≥3.9 - base language version;

•	Pandas - for working with tabular data;

•	NumPy – for numerical operations;

•	GeoPandas - for geospatial data handling;

•	Folium - to create interactive web map; and,

•	Requests - for web data requests.



Once the dependencies are installed successfully, activate the new environment:

`conda activate egm722_assignment`

Finally, launch JupyterLab (recommended interface) and open `Interactive_Database_Mapping.ipynb` to begin running the code step by step.
