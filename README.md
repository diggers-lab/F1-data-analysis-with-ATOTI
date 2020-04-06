# F1-data-analysis-with-ATOTI
Tutorial project with ATOTI, analyzing historical Formula1 data to understand the impact of different scoring systems in F1 history on championship results  

All details and prerequisites are described in the jupyter notebook.  

## Before starting: install your local jupyter environment
Steps for a Windows installation  
1. Install conda (for example using MiniConda, a light distribution:  https://docs.conda.io/en/latest/miniconda.html )  
  Be careful to correclty selection the 64 bits version and Python 3.7  
  After installation, you should find a new application called "Anaconda Prompt"  
2. Add conda-forge channel to your conda environment  
  Launch the Anaconda prompt, and from the command line, execute:  
  $ conda config --add channels conda-forge  
3. Create  dedicated envrionment for your ATOTI project  
  $ conda create --name atoti  
  $ conda activate atoti  
4. In your ATOTI environment, launch the following command:  
  $ conda install jupyterlab nodejs openjdk python=3.7.4 pywin32  
5. Finally, launch Jupyter lab  
  $ jupyter lab  

## Install and configure Atoti
Please refer to the atoti official documentation page  

David  
http://diggers-consulting.com
