# Mac installation Guide for Introduction to Data Science in R

  * Download and install brew `http://brew.sh/`
  * Install r `brew install r`
  * Install zeromq `brew install zeromq`
  * Download and install miniconda2  `http://conda.pydata.org/miniconda.html`
  * Install jupyter `conda install jupyter`
  * From command prompt run `R`
  * In the R shell that has opened run the command `install.packages(c('rzmq','repr','IRkernel','IRdisplay'),repos = c('http://irkernel.github.io/', getOption('repos')))`
  * On successfully running that command make irkernel available to jupyter by running the follow command `IRkernel::installspec(user = FALSE)`
  * Navigate to the repository for Introduction to Data Science in R and run `jupyter notebook`


** You should be able to create R notebooks from Jupyter now. ** 
