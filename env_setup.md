# Environment

### Create conda env
```shell
conda create --name=ptltflow python=3.6.9 -y 
```

### Remove conda env
```shell
conda env remove --name ptltflow -y
```

### add jupyter kernel
```shell
python -m ipykernel install --user --name ptltflow --display-name "Pytorch Lite Flow"
```

### remove jupyter kernel
```shell
jupyter kernelspec uninstall ptltflow -y
```

### Fix CV2 import problem
```shell
rm /home/puff/anaconda3/envs/bds/lib/libstdc++.so.6
ln -s /usr/lib/x86_64-linux-gnu/libstdc++.so.6 /home/puff/anaconda3/envs/ptltflow/lib/libstdc++.so.6
```



    ~/My/S/ENV_MD  python env_md.py -n ptltflow -dn "Pytorch Lite Flow" -pv 3.6.9
# Environment

### Create conda env
```shell
conda create --name=ptltflow python=3.6.9 -y 
```

### Remove conda env
```shell
conda env remove --name ptltflow -y
```

### add jupyter kernel
```shell
pip install ipykernel
python -m ipykernel install --user --name ptltflow --display-name "Pytorch Lite Flow"
```

### remove jupyter kernel
```shell
jupyter kernelspec uninstall ptltflow -y
```

### Fix CV2 import problem
```shell
rm /home/puff/anaconda3/envs/bds/lib/libstdc++.so.6
ln -s /usr/lib/x86_64-linux-gnu/libstdc++.so.6 /home/puff/anaconda3/envs/ptltflow/lib/libstdc++.so.6
```



    ~/My/S/ENV_MD  python env_md.py -n ptltflow -dn "Pytorch Lite Flow" -pv 3.6.9
# Environment

### Create conda env
```shell
conda create --name=ptltflow python=3.6.9 -y 
```

### Remove conda env
```shell
conda env remove --name ptltflow -y
```

### add jupyter kernel
```shell
conda activate ptltflow
pip install ipykernel
python -m ipykernel install --user --name ptltflow --display-name "Pytorch Lite Flow"
```

### remove jupyter kernel
```shell
jupyter kernelspec uninstall ptltflow -y
```

### Fix CV2 import problem
```shell
rm /home/puff/anaconda3/envs/bds/lib/libstdc++.so.6
ln -s /usr/lib/x86_64-linux-gnu/libstdc++.so.6 /home/puff/anaconda3/envs/ptltflow/lib/libstdc++.so.6
```



    ~/My/S/ENV_MD  python env_md.py -n ptltflow -dn "Pytorch Lite Flow" -pv 3.6.9
# Environment

### Create conda env
```shell
conda create --name=ptltflow python=3.6.9 -y 
```

### Remove conda env
```shell
conda env remove --name ptltflow -y
```

### add jupyter kernel
```shell
conda activate ptltflow
pip install ipykernel
python -m ipykernel install --user --name ptltflow --display-name "Pytorch Lite Flow"
```

### remove jupyter kernel
```shell
jupyter kernelspec uninstall ptltflow -y
```

### Fix CV2 import problem
```shell
rm /home/puff/anaconda3/envs/ptltflow/lib/libstdc++.so.6
ln -s /usr/lib/x86_64-linux-gnu/libstdc++.so.6 /home/puff/anaconda3/envs/ptltflow/lib/libstdc++.so.6
```


### install main package
```shell
pip install ptlflow
```
