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

### 3.1: Fork the repo

### 3.2: Clone the repo

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

### 3.3: `cd` into cloned repo

<kbd> cd </kbd> into the `pymc` folder:  
```bash            
▶ cd pymc
(base) 
~/software-build/pymc  main ✔                                     2d  
```

### 3.4: Check remotes

Check `remotes`. Note there is one remote, the `origin`:  

<kbd> git remote -v </kbd>

```bash
▶ git remote -v
origin	git@github.com:reshamas/pymc.git (fetch)
origin	git@github.com:reshamas/pymc.git (push)
(base) 
~/software-build/pymc  main ✔                                     2d  
▶ 
```

### 3.5: Add another remote, called `upstream`

<kbd> git remote add upstream git@github.com:pymc-devs/pymc.git </kbd>

```bash
▶ git remote add upstream git@github.com:pymc-devs/pymc.git
(base) 
~/software-build/pymc  main ✔                                     2d  
▶ 
```

### 3.6: Check remote(s)

<kbd> git remote -v </kbd>

```bash
▶ git remote -v
origin	git@github.com:reshamas/pymc.git (fetch)
origin	git@github.com:reshamas/pymc.git (push)
upstream	git@github.com:pymc-devs/pymc.git (fetch)
upstream	git@github.com:pymc-devs/pymc.git (push)
(base) 
~/software-build/pymc  main ✔                                     2d  
▶ 
```

---

## PART 4: Find an issue

I will work on this issue:  xxx


## PART 5: Create a feature branch

<kbd> git checkout -b docstring_update </kbd>

```bash
▶ git checkout -b docstring_update
Switched to a new branch 'docstring_update'
(base) 
~/software-build/pymc  docstring_update ✔                         2d  
▶ 
```

<kbd> git branch </kbd>

```bash
* docstring_update
  main
(END)
```

For me, I hit <kbd> q <kbd> to exit.
  
---
  
## PART 6: Set up working environment
  
  <kbd> conda env create -f conda-envs/environment-dev-py38.yml </kbd>
  
  







