## set password
    
    jupyter notebook password
    
## start server

    jupyter notebook --port=8000 --ip=xx.xx.xx.xx --no-browser --notebook-dir="~"
    
## use both python2 and python3 in jupyter

    pip2 install jupyter
    pip3 install jupyter
    
    python2 -m ipykernel install --user
    python3 -m ipykernel install --user

## use virtualenv in jupyter

### Install the ipython kernel module into your virtualenv

    pip install ipykernel
### Run the kernel "self-install" script:

    python -m ipykernel install --user --name=my-virtualenv-name
Replacing the --name parameter as appropriate.

### You should now be able to see your kernel in the IPython notebook menu: Kernel -> Change kernel
