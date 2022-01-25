# Contributing to PyMC

## PART 1: Pre-reqs to contributing

Contributing Guide:  [PyMC CONTRIBUTING.md](https://github.com/pymc-devs/pymc/blob/main/CONTRIBUTING.md)


### GitHub Account

https://github.com/reshamas

### Git
<kbd>  git --version  </kbd> 

```
▶ git --version
git version 2.19.0
```

### Conda
<kbd> conda --version  </kbd>

```
▶ conda --version
conda 4.10.3
```

### Python
<kbd> which python  </kbd>

```bash
▶ which python
/Users/reshamashaikh/miniforge3/bin/python
```

<kbd>  python --version    </kbd>

```bash
▶ python --version
Python 3.9.7
```

### Text Editor
[Visual Studio Code](https://code.visualstudio.com/download)

---

## PART 2: My working directory

NOTE: I use a directory called `software-build` where I clone my python libraries to which I contribute.  

```bash
▶ pwd
/Users/reshamashaikh
(base) 
~                                                                     
▶ cd software-build 
(base) 
~/software-build                                                      
▶ pwd
/Users/reshamashaikh/software-build
(base) 
~/software-build                                                      
▶ 
```

---

## PART 3: Fork & clone, set remotes

NOTE: this is *my* fork.  You will need to update syntax with your user name.  
Replace "reshamas" with "your_gh_username"

<kbd> git clone git@github.com:reshamas/pymc.git </kbd>

```bash
▶ git clone git@github.com:reshamas/pymc.git
Cloning into 'pymc'...
remote: Enumerating objects: 57337, done.
remote: Counting objects: 100% (630/630), done.
remote: Compressing objects: 100% (292/292), done.
remote: Total 57337 (delta 419), reused 482 (delta 337), pack-reused 56707
Receiving objects: 100% (57337/57337), 735.38 MiB | 24.10 MiB/s, done.
Resolving deltas: 100% (41734/41734), done.
(base) 
~/software-build   
```

<kbd> cd </kbd> into the `pymc` folder:  
```bash            
▶ cd pymc
(base) 
~/software-build/pymc  main ✔                                     2d  
```

Check `remotes`. Note there is one remote:  

<kbd> git remote -v </kbd>

```bash
▶ git remote -v
origin	git@github.com:reshamas/pymc.git (fetch)
origin	git@github.com:reshamas/pymc.git (push)
(base) 
~/software-build/pymc  main ✔                                     2d  
▶ 
```




