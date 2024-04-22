# Actionable Knowledge Representation

course material for tutorial

Tutorial 2: Find a Product Tutorial as an introduction to Protègè

## Start-Up for Tutorials 4 and up with juypter notebooks

Please install docker and docker-compose to your system. Here is the link for windows: https://hub.docker.com/editions/community/docker-ce-desktop-windows/ <br>
Optional: Also install git (for windows: install git on windows: https://gitforwindows.org/)

set your environment variables (e.g. to `C:\Users\user\.local\lib\python3.8\site-packages` for pip and `C:\Users\user\.local\lib\python3.10\site-packages` for additional packages

### Check if docker is installed correctly

To check if docker is installed correctly, in your shell run `docker run hello-world`
You will get a hello message if everything was installed correctly

## Start up jupyter

To start up jupyter, we will use docker to start a standard jupyter notebok
1. In your shell, run `docker run -p 8888:8888 jupyter/scipy-notebook`
2. This might take a while. Wait till the container is ready
3. Open the Jupyter-Lab using the link shown in your terminal (something like http://127.0.0.1:8888/lab?token=...), it should open a tab in your browser
4. if you get a "token required" website -> disable cookies in your browser

Now you should have a blank jupyter notebook.

## Install SPARQL kernel - only needed for <b>querying</b> in later Tutorials

We are going to use a SPARQL kernel in our lectures (<i>the first Tutorials can be used without it</i>). To install this, please follow these steps:

1. In your jupyter notebook, open the terminal
2. in the terminal, run `pip install sparqlkernel`
3. Then run `jupyter sparqlkernel install --user`

If you now switch to the launcher start page, in addition to the python kernel you should now see a SPARQL kernel installed.

## Start Tutorials

Now let's start with the Tutorials!

You can either
- clone this repository using git (e.g. git bash): `git clone https://github.com/michaelakuempelActionableKnowledgeRepresentation.git`
or
- download the tutorial jupyter notebook files directly

In your jupyter notebook, please upload the tutorial files

To open the notebooks you can choose them from the left sidebar. 

