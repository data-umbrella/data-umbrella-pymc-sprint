# data-umbrella-pymc-sprint
Data Umbrella PyMC Sprint


### PyMC Contributing Guide
https://github.com/pymc-devs/pymc/blob/main/CONTRIBUTING.md


### PyMC Code Repo
https://github.com/pymc-devs/pymc

### Docstring Tutorial
https://pymc-data-umbrella--13.org.readthedocs.build/en/13/webinars/contributing_to_documentation/docstring_tutorial.html


### Oriol's PR
https://github.com/pymc-devs/pymc-data-umbrella/pull/13/files


Directory:  
```bash
▶ pwd
/Users/reshamashaikh/ds/my_repos/pymc-projects/pymc-devs-repos/pymc-examples
(base) 
```

Activate virtual environment:  
```bash
pymc-projects/pymc-devs-repos/pymc-examples  nb_bayes_factor ✗                                         6d ⚑  
▶ mamba activate pymc-ex
(pymc-ex) 
pymc-projects/pymc-devs-repos/pymc-examples  nb_bayes_factor ✗                                         6d ⚑  
▶ 
```

Instructions for installing pre-commit:  
https://pre-commit.com/
 
Run `pre-commit`:  
```bash
pymc-projects/pymc-devs-repos/pymc-examples  main ✔                                                     1m  ⍉
▶ pre-commit run --files examples/diagnostics_and_criticism/Bayes_factor.ipynb
```
Or run `pre-commit` on all files:
```bash
pre-commit run --all
```

Steps:  
`git add myst_nbs/diagnostics_and_criticism/Bayes_factor.myst.md`

`git status` should show that the file has been added
check that's the correct path   
also be sure that the notebook itself had been added Bayes_factor.ipynb  
probably something like
`git add examples/diagnostics_and_criticism/Bayes_factor.ipynb`
