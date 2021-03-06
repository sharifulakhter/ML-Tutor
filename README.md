# Machine Learning with jupyterlab-slim
![FED UP!!!](fedup.png)

## Introduction
It's always fun to learn `Machine Learning (ML)`. But setting up the environment is a tedious task and eats up a lot of time as well as energy. You need to install python, then libraries, dependencies, Jupyter etc. By the time you finish configuration you're exhausted. Isn't it true? But what if you don't need to do any of those? What if someone else takes care of those on behalf of you and you can enjoy Machine Learning? Sounds so Great. Right? Well, 'Docker' to the rescue! You just need to install `Docker` on your machine and need not to worry about anything else. You can set up the environment and demolish any time you want. All of these is just a command away from you. The idea is to provide a configured environment so that teachers can focus on teaching and students can focus on learning.

## What you’ll get here?
- `Python` version 3.7.9
- Configured `Jupyter Lab` (Image size 1.83 GB)
- Installed Libraries (Most of the ML libraries including `tensorflow 2.3.0` for DL)
- No need to worry about dependencies
- Root privileges which means you can also install libraries if you want or required.
- Some public datasets
- `Demo codes` from almost all crucial ML concepts

## Prerequisite
- Only `Docker  >= 19.03.12`

## How to install Docker?
It’s pretty easy and straight forward process. Please visit the [link](https://docs.docker.com/docker-for-windows/install/)

## Steps to follow after docker installation

1) First lets check docker is properly installed or not. Open your terminal and fire the below command.

```docker version```
  
You should get the following output.

![](docker-version.PNG)

2) Since docker is running perfectly now we can move to the second step. Fire the below command.

```docker run -itd --rm -p 8080:8080 aman10/jupyterlab-slim```

![](docker-run.PNG)

3) Now open your browser and copy paste the below URL and give password `aman` when prompted.

```http://host.docker.internal:8080```

![](j-lab1.PNG)

Viola !!! Your Jupyter Notebook with all crucial ML codes organized to learn and practice.

**SUGGESTION:** Go through the codes chronologically.

![](j-lab2.PNG)

Enjoy Machine Learning

![](j-lab3.PNG)

**NOTE:** You can close the browser and revisit the URL again. Your notebook will be there until or unless you shut down it manually.

## What to do when you're done ?

It's very simple. Just shutdown the Jupyter Lab.

![](j-lab4.PNG)

## Additional Links

Learn more about Docker [here](https://docs.docker.com/)
Learn more about Jupyter Lab [here](https://jupyterlab.readthedocs.io/en/latest/)

To go to my Docker Hub repository [Click here](https://hub.docker.com/repository/docker/aman10/ml-tutor)

## License
This is a completely free software to download, use and modify. Feel free to share with others.
