# ACN

## Installation overview

### Python environment and GitHub repo's

```
git clone https://gist.github.com/e25a92908f1630375fa0163b2f383142.git acn_setup &&
source acn_setup/acn-setup.sh &&
rm -rf acn_setup
```

### API-KEY

update the files with API Key 
- ```~/acn/acn_jads/.env```
- ```~/acn/exp_jads/.env``` 

The API key for this project is stored [here (authorization required)](https://1drv.ms/t/s!AiogHeTeve1hjvo-_7UAopYbxRS1qQ?e=LKaLS9), additional info can be found here: [ACN - Data Client][acn_api]  

## Run jupyter notebook

1. Open Visual Studio Code
1. File > Open Workspace from File... ```~/acn/acn_jads/acn.code-workspace```
1. Open ACN-sim_L0x.ipynb
    1. Select kernel env_acn (python 3.8.18)
    1. Clear All Outputs 
    1. Restart
    1. Run All

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
[vsc_python_int]:  https://code.visualstudio.com/docs/python/environments#_working-with-python-interpreters
[vsc_conda_env]:   https://code.visualstudio.com/docs/python/environments#_create-a-conda-environment-in-the-terminal
[acn_api]:         https://acnportal.readthedocs.io/en/latest/acndata/data_client.html

