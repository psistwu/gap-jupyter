# gap-jupyter
This is a Python project based on [pdm](https://github.com/pdm-project/pdm).
It helps user create a JupyterLab environment for [GAP-System](https://www.gap-system.org/)
so that a better user experience is provided.

## Quickstart
### Dependency
1. Please make sure the following items are installed
    * Python
    * pdm
    * GAP-System

2. The Python and pdm can be installed with the following command
   ```console
   $ sudo apt-get install python3 python3-pdm
   ```
3. To install GAP-System, please refer to the official website.

### Initiate JupyterLab
1. After download/unzip or clone the repo, enter the following
   command to initiate JupyterLab service.
   ```console
   $ pdm start
   ```
2. Open a web browser and put `http://localhost:8888/` in the
   address bar and sumbit.
   - One may need to replace `localhost` by other hostname if necessary.
