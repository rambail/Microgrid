## Install Python in Virtual environment

###### Navigate to base folder
PS C:\Users\name> cd e:mmr\jyplite

###### Install Virtual Environment
PS E:\mmr\jyplite> python3 -m venv .venv

###### Relax policy (Do be done everytime)
PS E:\mmr\jyplite> Set-ExecutionPolicy Unrestricted -Scope Process

###### Activate the Virtual Environment
PS E:\mmr\jyplite> .venv\Scripts\activate

###### Install Jupyter
(.venv) PS E:\mmr\jyplite> pip3 install -U jupyter

###### Install Packages
(.venv) PS E:\mmr\jyplite> pip3 install -U matplotlib, numpy, scipy, ipywidgets

###### Run Notebook
(.venv) PS E:\mmr\jyplite> jupyter notebook
