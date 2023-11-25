# ACN

## Installation overview

### python environment and GitHub repo's

```
git clone https://gist.github.com/e25a92908f1630375fa0163b2f383142.git acn_setup```
sh acn_setup/acn-setup.sh 
rm -rf acn_setup
```

### API-KEY

update the file .env with API_KEY

1. setup secret in ```.env``` file

Documentation on API can be found here: [ACN - Data Client][acn_api]  

The API key for this project is stored [here (authorization required)](https://1drv.ms/t/s!AiogHeTeve1hjvo-_7UAopYbxRS1qQ?e=LKaLS9)

## Run jupyter notebook

1. Open Visual Studio Code
1. File > Open Workspace from File... ```~/acn/acn.code-workspace```
1. Open ACN-sim_L0x.ipynb
    1. Select kernel acn_py39 (Python 3.9.18)
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


## Versioning

Note: this tool seems to use an old panda's version being:

[pandas python version][pandas-1.1.5]

[pandas-1.1.5]: https://pandas.pydata.org/pandas-docs/version/1.1.5/getting_started/install.html

## additional packages locally installed with pip via github


