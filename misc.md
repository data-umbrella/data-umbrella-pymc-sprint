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

Steps:  
`git add myst_nbs/diagnostics_and_criticism/Bayes_factor.myst.md`

`git status` should show that the file has been added
check that's the correct path   
also be sure that the notebook itself had been added Bayes_factor.ipynb  
probably something like
`git add examples/diagnostics_and_criticism/Bayes_factor.ipynb`
