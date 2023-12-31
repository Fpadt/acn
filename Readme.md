# ACN

## Installation overview

### Python environment and GitHub repo's

Copy the code below by clicking the icon on the far right and paste this code in a terminal.  
After execution   
- a new Workspace will be opened
- a new folder structure will be in the home directory
- a new Python environment will be available.

```
git clone https://gist.github.com/bc46a03309c1d3ceaefd680f6962d415.git acn_setup && source acn_setup/acn-setup.sh && cd ~ && rm -rf ~/acn_setup
```

#### Folder structure

The following folder structure will be in your home-folder  

~/acn  
 |- acn_calt     (this is the original repository for reference, changes CAN NOT be pushed to GIT)  
 |- acn_jads  
 |- exp_calt     (this is the original repository for reference, changes CAN NOT be pushed to GIT)  
 |- exp_jads  

#### Python Environment
A new python environment will be availble called ```env_acn```.  
Execute ```mamba env list``` to see if it exists.

### API-KEY

In the new Workspace 2 .env files will e open in which you need to populate the API_KEY.  

The API key for this project is stored in file [API_KEY.txt][API_KEY], additional info can be found here: [ACN - Data Client][acn_api]  

### MOSEK license

In your home directory you will have an emtpy folder called mosek.  
Download the license file called [mosek.lic][mosek_lic] and save it in this folder. 

### Sim results from OneDrive

In order to save 12-13 hours you can load the previous simulation results.  
Download the file [sims.zip][sim_results]. Next, unzip and copy the folder ``sims`` it into: 
``~/acn/exp_jads/examples/2-Algorithm-Comparison/2.1-Comparing-Algorithms-with-Constrained-Infrastructure/results``

1. In VSC right click the folder ``results`` (as mentioned above) in the VSC Explorer and select ```Reveal in File Explorer```, Shift+Alt+R. 
1. Download the file [sims.zip][sim_results] to a temporary folder
1. UnZip this file in a folder called ``sims`` in the temporary folder (<60 secs.)
1. Copy the folder ``sims`` to the folder ``results`` in the file Explorer opened at the first step (337 files, 122 MB)
1. Execute the next Python Cell to load the events (<4 minutes.)

## Run jupyter notebook

Open a jupyter note book, e.g. ACN-sim_L0x.ipynb
    1. Select kernel env_acn (python 3.8.18)
    1. Clear All Outputs 
    1. Restart
    1. Run All

Try to execute the following ACN notebook:  
~/  
..acn/  
....exp_jads/  
......examples/  
........2-Algorithm-Comparison/  
..........2.1-Comparing-Algorithms-with-Constrained-Infrastructure/  
............2.1-comparing-algorithms-with-constrained-infrastructure.ipynb  

## Links

- [EV Research @ Caltech][def]  
- [ACNportal on GitHub][acnportal]  
- [ACM-sim Documentation][ACM-sim]  
- [ACNportal on PyPi][acn_portal_pypi]  

[def]:             https://ev.caltech.edu/index
[acnportal]:       https://github.com/zach401/acnportal
[ACM-sim]:         https://acnportal.readthedocs.io/en/latest/
[acn_portal_pypi]: https://pypi.org/project/acnportal/
[conda_yml]:       https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file
[API_KEY]:         https://1drv.ms/t/s!AiogHeTeve1hjvo-_7UAopYbxRS1qQ?e=LKaLS9
[mosek_lic]:       https://1drv.ms/u/s!AiogHeTeve1hjvpAHK-FCdqT2ikhfQ?e=DM0Uxm
[sim_results]:     https://1drv.ms/u/s!AiogHeTeve1hj4MPKhNDWJn26EDWoQ?e=XdZ8Ev
[vsc_python_int]:  https://code.visualstudio.com/docs/python/environments#_working-with-python-interpreters
[vsc_conda_env]:   https://code.visualstudio.com/docs/python/environments#_create-a-conda-environment-in-the-terminal
[acn_api]:         https://acnportal.readthedocs.io/en/latest/acndata/data_client.html

