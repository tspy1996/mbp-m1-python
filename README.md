# mbp-m1-python

#### show local python
ls /usr/local/bin/python*
### remove local python3
?
### Conda (for MAC)

```bash
# create environment 
# Add pip before python!
conda create --name env38 pip python=3.8
```

- Make sure pip path is right(in local path not global ), try

`which pip` → if it points to your conda env, you are good. If not:

`conda deactivate` until you are our of conda envs (**including base**)

`conda activate name_of_your_env`

`which pip` should now point to conda env

`pip list`  should show a fresh, clean list.

```bash
# to remove enviroment
conda env remove -n ENV_NAME
```

### Often use package
```bash
pip install PyMySQL numpy pandas matplotlib tqdm
```
