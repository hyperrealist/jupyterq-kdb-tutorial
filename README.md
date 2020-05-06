# Introduction
Kdb+ is a high-performance database technology developed by [Kx systems](kx.com). Built on top of kdb+, the functional programming language 'Q' provides high-performance analytics for real-time data streams. Among its common uses are various applications in finance domain such as real-time time series analysis and high-frequency trading (HFT). The purpose of this repository is to collect learning materials as I learn the basics of functional programming language Q and its associated database kdb+. I will try to present them as a tutorial for both my own future reference, and for anyone who is comfortable with the user-friendly and narrative notebook style of Jupyter but is still trying to tame the beast Q.

## Motivation
When looking for sources to learn kdb+ and Q, I found that one has to mostly read through pages and pages of static (= boring) books. Coming from the world of Jupyter/Python-based machine learning, I was thrilled to learn that there are [official Q bindings for Jupyter (JupyterQ)](https://code.kx.com/q/ml/). Now I am taking it upon myself to exploit the official Jupyter bindings to create an interactive Q and kdb+ tutorial for beginners (like myself). Don't worry, I will do the reading of static and boring books for you. Wish me luck!

# Getting Started
Use conda to install the relevant packages using the following commands:
```sh
conda install -c kx kdb
conda install -c kx embedpy
conda install -c kx jupyterq
```
Alternatively, you can get things set up using docker or by installing individual components yourself. Follow the instructions listed [here](https://code.kx.com/q/ml/setup/).<br>

****NOTE**: Official website mentions that jupyterq will only work in the base conda environment. However, I was able to get it running on a different environment without doing anything special. I will be using jupyter lab to create the notebooks.*
