# Artificial Neural Network CHATBOT (ANN)

**Instructions on common runtime errors** :page_with_curl:

Running the bot can be hindered by microsoft licensing whereby you will have to change the execution policy to AllSigned and later revert to RemoteSigned or according to your license reference.

NB: Updates of optimizers and libraries should be conducted after every release to avoid deprecations or malfunctioning.


#FILE DESCRIPTION 📁


* * **1. User Intentions**
* * [intents.json](./intents.json): This file contains the user intents which will be useed by the ANN to give out the respective response.

* * **2. Training the ChatBot**
* * [training.py](./training.py): this file contains the script that trains the ANN with the data from the intents.json file.

* * **3. ChatBot Modelling**
* * [chatbot.py](./chatbot.py): This file contains the final stages and scripts that model the bot from the generated pickle files and documents from the training stage.


**INSTALLATION **

**To install the requirements**

pip install -r requirements.txt

If errors come up,you can try mitigating them using these installation options

**For Tensorflow:**

# Requires the latest pip

pip install --upgrade pip

# Current stable release for CPU and GPU

pip install tensorflow

# Or try the preview build (unstable)

pip install tf-nightly

**For Numpy: **
Use pip to install it if it's missing in your workspace though it comes pre-installed during Python installation.

# Best practice, use an environment rather than install in the base env

conda create -n my-env

conda activate my-env

# If you want to install from conda-forge

conda config --env --add channels conda-forge

# The actual install command

conda install numpy

If more issues arise,confirmation and mitigation can be carried via the guide from official numpy website: https://numpy.org/install/

**For NLTK**

NLTK requires Python versions 3.7, 3.8, 3.9, 3.10 or 3.11.

For Windows users, it is strongly recommended that you go through this guide to install Python 3 successfully https://docs.python-guide.org/starting/install3/win/#install3-windows

Setting up a Python Environment (Mac/Unix/Windows)
Please go through this guide to learn how to manage your virtual environment managers before you install NLTK, https://docs.python-guide.org/dev/virtualenvs/

Alternatively, you can use the Anaconda distribution installer that comes “batteries included” https://www.anaconda.com/distribution/

Mac/Unix
Install NLTK: run pip install --user -U nltk

Install Numpy (optional): run pip install --user -U numpy

Test installation: run python then type import nltk

For older versions of Python it might be necessary to install setuptools (see https://pypi.python.org/pypi/setuptools) and to install pip (sudo easy_install pip).

Windows->
These instructions assume that you do not already have Python installed on your machine.

32-bit binary installation->
Install Python 3.8: https://www.python.org/downloads/ (avoid the 64-bit versions)

Install Numpy (optional): https://numpy.org/install/

Install NLTK: https://pypi.python.org/pypi/nltk

Test installation: Start>Python38, then type import nltk

Installing Third-Party Software
Please see: https://github.com/nltk/nltk/wiki/Installing-Third-Party-Software

Installing NLTK Data
After installing the NLTK package, please do install the necessary datasets/models for specific functions to work.

If you’re unsure of which datasets/models you’ll need, you can install the “popular” subset of NLTK data, on the command line type python -m nltk.downloader popular, or in the Python interpreter import nltk; nltk.download('popular')

For details, see https://www.nltk.org/data.html


## Author :black_nib:

* __Festus Maithya__ [festusmaithyakcau](https://github.com/festusmaithyakcau)
