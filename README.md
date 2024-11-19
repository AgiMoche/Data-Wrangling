Data Wrangling (247) 
For raw project instructions see: http://syllabus.africacode.net/projects/data-science-specific/data-wrangling/

## Project Setup

### 1. Cloning the Repository:
In the instructions below, information is provided to clone the repository of the project. Cloning the repository pulls down a full copy of all the repository data associated with the GitHub.com uploads:
- A command prompt can be used in Windows Terminal or Command Prompt as follows to clone the project repository: 
~~~
git clone https://github.com/Umuzi-org/Oageng-Moche-247-data-wrangling-python.git
~~~

### 2. Environment Setup:
In the instructions below, information is provided to install the necessary tools needed to run the notebook and its dependencies on any capable machine:
- Command prompts can be used in Windows Terminal or Command Prompt as follows:
  1. Create a new virtual environment to run the project by using the following command in the terminal window: 
  ~~~
  python -m venv <virtual_environment_name>
  ~~~
  2. Activate the new virtual environment that you just created using the following command in the Windows Terminal or Command Prompt:
  ~~~
  <virtual_environment_name>\Scripts\activate
  ~~~
  
### 3. Installing the Required Python Packages:
Once the repository has been cloned and the virtual environment has been set up:
1. Navigate to the directory where the project repository was cloned and then navigate to the project folder by using the following command in the virtual environment Command Terminal or Windows Terminal:
~~~
cd Oageng-Moche-247-data-wrangling-python
~~~
2. In the Windows Terminal or Command Prompt of the virtual environment, type in the following command to install the modules required to run the files for the project:
~~~
python -m pip install -r requirements.txt 
~~~

### 4. Running the Data Wrangling project:
- To run the project, ensure that Jupyter Notebook is installed on your machine. If you are unsure that Jupyter Notebook is installed on your machine, use the following command in the virtual environment Command Terminal or Windows Terminal to install it:
~~~
pip install jupyter notebook
~~~
- A kernel within the virtual environment for the Jupyter Notebook will be installed from the requirements.txt file. Use the following commands to create and provide a name for the kernel installed in the virtual environment:
~~~
ipython kernel install --user --name=name_of_kernel_environment
~~~
~~~
python -m ipykernel install --user --name=name_of_kernel_environment
~~~
- Once the kernel and Jupyter Notebook have been installed on your machine, to run the project on Jupyter Notebook, use the following command in the virtual environment Command Terminal or Windows Terminal to launch Jupyter Notebook:
~~~
jupyter notebook
~~~
- In the Jupyter Notebook dashboard, navigate to the notebook directory
- Click on the _data_wrangling.ipynb_ file to open the notebook
- Click on _Kernel_ and then select _Restart Kernel & Run All Cells..._ OR Click on _Run_ and then select _Restart Kernel & Run All Cells..._

### 5. Deactivating environment setup:
Once the necessary tasks have been completed, stop and shut down the running notebook and then deactivate the virtual environment that was set up to run the tasks by typing the following command in the Windows Terminal or Command Prompt of the virtual environment:
~~~
deactivate
~~~
