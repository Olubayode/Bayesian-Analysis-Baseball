# Bayesian Analysis for Strike Likelihood

## Installation and Dependencies



 **Software Needed:**
These are tools user needs before starting or running the python notebook:
- Git
- Anaconda
- Python 3.10.

To install the dependencies to run the notebook provided in this repository, follow these steps after you have [anaconda](https://www.anaconda.com/products/individual#Downloads) install on your computer: 

1. **Clone the Repository:**
   - Open your command prompt and navigate to the directory where you want to clone the repository:
     ```bash
     cd path/to/your/directory
     ```
   - Clone the repository by running:
     ```bash
     git clone https://github.com/Olubayode/Bayesian-Anaysis-Baseball.git
     ```

   The cloned repository will contain the following major files:
   - `Thesis Code.ipynb` (Jupyter Notebook for the analysis)
   - `environment.yml` (environment specification file i.e  The file defines the environment and dependencies required to run the analysis)
   - `Data not available` (dataset file)

2. **Set Up the Environment:**
   - Open the Anaconda Command Prompt and navigate to the cloned folder:
     ```bash
     cd path/to/Bayesian-Analysis-Baseball
     ```
   - Create the conda environment by running:
     ```bash
     conda env create -f environment.yml
     ```

3. **Activate the Environment:**
   - Activate the newly created environment by running:
     ```bash
     activate stat-rethink2-pymc_v4_env
     ```
   - **Note:** The environment setup process may take some time depending on your system.

4. **Register the Environment for Jupyter Notebooks:**
   - Register your environment as a valid notebook kernel by running:
     ```bash
     python -m ipykernel install --user --name stat-rethink2-pymc4 --display-name "Python 3.10 (Bayesian Analysis Baseball)"
     ```

   #### Explanation of Command:
   1. `--name stat-rethink2-pymc4`:
      - Internally registers the kernel with the name `stat-rethink2-pymc4`. This is how Jupyter identifies the kernel behind the scenes.
   2. `--display-name "Python 3.10 (Bayesian Analysis Baseball)"`:
      - This is the name that will appear in the Jupyter interface, so you can easily recognize and select the kernel when working on your project.


   This command will successfully create a new kernel for your Jupyter notebooks with:
   - Internal name: `stat-rethink2-pymc4`
   - Display name: `Python 3.10 (Bayesian Analysis Baseball)`


5. **Start Jupyter Notebooks or Jupyter Lab:**
   - Start a notebook interface by running:
     ```bash
     jupyter notebook
     ```
     Or use the more modern Jupyter Lab interface:
     ```bash
     jupyter lab
     ```
   - Make sure you run these commands from the root directory of the cloned repository.

6. **Install Additional Python Packages:**
   - Once the Jupyter Lab or Notebook interface opens, install the following additional dependencies, though not require for this project:
     ```bash
     pip install polars
     pip install pyarrow
     ```
   - These packages are necessary to access the datasets provided in the repository.
   - Once all the above steps are completed, you can start running the Thesis Code.ipynb file. Please ensure that the kernel selected for running the notebook is set to "Python 3.10 (Bayesian Analysis Baseball)", unless you used a different name during setup.

---

#
### Additional Resources

For more information about Bayesian analysis and how PyMC works, check out the [Statistical Rethinking materials](https://github.com/pymc-devs/pymc-resources/tree/main/Rethinking_2).

---

## License

**Bayesian Analysis Baseball For Strike Likelihood** © 2025 by Ebenezer Olubayode is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).
