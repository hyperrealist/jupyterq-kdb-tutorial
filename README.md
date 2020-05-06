# Introduction
The purpose of this repository is to collect learning materials as I learn the basics of functional programming language Q and its associated database kdb+. I will try to present them as a tutorial for my own future reference, and also for anyone coming from a Python data science background who is trying to learn Q.

## Motivation
Kdb+ is a high-performance database technology developed by [Kx systems](kx.com). Built on top of kdb+, Q provides high-performance analytics for real-time data streams. Among its common uses are various applications in finance domain such as real-time time series analysis and high-frequency trading (HFT). When looking for sources to learn kdb+ and Q, I found that one has to mostly read through pages and pages of static (= boring) books. Coming from a world of Jupyter/Python-based machine learning, I was thrilled to learn that there are [official Q bindings for Jupyter (JupyterQ)](https://code.kx.com/q/ml/). Now I am taking it upon myself to exploit the official Jupyter bindings to create an interactive Q and kdb+ tutorial for beginners (like myself). Don't worry, I will do the reading of static and boring books for you. Wish me luck!

# Getting Started
Use conda to install the relevant packages using the following commands:
```sh
conda install -c kx kdb
conda install -c kx embedpy
conda install -c kx jupyterq
```
Alternatively, you can get things set up using docker or by installing individual components yourself by following [these instructions](https://code.kx.com/q/ml/setup/).<br>

****NOTE**: Official website mentions that jupyterq will only work on the base conda environment. However, I was able to get it running on a different environment without doing anything special. I will be using jupyter lab to create the notebooks.*
