# statlearn
This is where i follow my stats/R studies.

Books i use: https://drive.google.com/drive/folders/1Vx2jIljyEZEIPi_ScW4MVcRsb030b9ph


More cool stuff:  
https://probmods.org/  
http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/  



# Setting up the environment

- create virtualenv with anaconda  
`$ conda create -n my-r-env -c r r-essentials`
  
- you will probabli need this for git2r, and devtools  
`$ sudo apt-get update && sudo apt-get install libssl-dev`  

- activate it  
`$ conda activate my-r-env`  
  
- start R  
`$ R`  
  
- install some more stuff  
`> install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))`  
`> devtools::install_github('IRkernel/IRkernel')`  
`> q()`  
  
- now you can open up a jupyter notebook, and start a new notebook with R  
`$ jupyter notebbok`  
