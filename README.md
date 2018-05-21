# caseweek-socialmedia
This repository contains code for the "AI on Her Network Majesty's Service - How to extract knowledge from the Social Media" CaseWeek workshop organized on 16.04.2018 in Warsaw, Poland by Samsung R&D Institute Poland. Please clone the contents of this repository to your local machine with git.

To run the workshop code, you should have python3 installed (v3.6 recommended), as well as the number of required python packages: `numpy`, `tensorflow`(v1.7 recommended), `jupyter` and `tqdm`. 
Please make sure to set up the environment at home, before the workshop. The **Installation** section should help you with this if needed.

After installation, please make sure to check your setup. The **Environment Test** section contains guidelines how to it.

The setup was tested on workstations with Ubuntu and Windows.

# Installation
**1. Install git and python3 (v1.6 recommended)**
- To install git: follow the intructions at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- To install python3: follow the instructions at https://www.python.org/downloads/. During isntallation, the python package manager, `pip`, should be automatically installed.

**2. Clone the contents of the `caseweek-socialmedia` project to your local machine**
```
git clone https://github.com/mpienkosz/caseweek-socialmedia.git
```

**3. Install required python packages: numpy, jupyter and tqdm**

The easiest way to do it is to use the provided `requirements.txt` and pip. Open the terminal/console window, go to the `caseweek-socialmedia` directory and execute:
```
pip install -r requirements.txt
```

**4. Separatelly, install Tensorflow**

In most cases, you should be able to install Tensorflow with pip:
```
pip install tensorflow==1.7.0
```
However, installing Tensorflow may be tricky sometimes. In case of problems, please follow instructions for your system at https://www.tensorflow.org/install/.
We recomment installing version 1.7.0 through pip.

**5. And that's it :) Please check your installation as described in the next section**

# Environment Test

To test the environment, please open the terminal/console window, go to the `notebooks/` directry and launch the jupyter notebook:
```
jupyter notebook
```
After executing this command, the jupyter app should automatically pop up in your browser. Open the browser, select the `Environment_Test.ipynb` notebook and run it.
With the correctly set up environment, you should see the output similar to the following:

```
Building toy keras model and training...
2/2 [==============================] - 0s 9ms/step

.

Toy model accuracy: 100.0%


----------------------------------------------------------------------
Ran 1 test in 0.777s

OK

<unittest.runner.TextTestResult run=1 errors=0 failures=0>


```

You are ready to go :)

