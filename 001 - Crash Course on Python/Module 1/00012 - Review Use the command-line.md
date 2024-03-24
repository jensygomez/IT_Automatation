# Review: Use the command-line

The command-line is used to tell your computer what to do. You can use it to access servers, move files, change directories, and write scripts. In this reading, you will learn how to write Python scripts at the command-line along with the Python GUI IDLE. We will also cover the different ways you can access the command-line based on your operating system. 

## **Using the command line on MacOS**

Using the spotlight search, type in “terminal.” Select the terminal application. You should see your username followed by the $ sign. MacOS comes with Python 2.7 pre-installed. You can install Python 3 from [python.org](http://python.org/). Just remember, this means that you will have 2 versions of Python installed on your Mac, and you will need to pay special attention to your paths.

To check which version of Python you have installed on your Mac, use the following command.

python --version

To check for Python3, use the following command. 

python3 --version

## **Using the command line on Windows OS**

In Windows, open the start menu. In the search box type cmd. Right-click on cmd and select Run as administrator. This will open up the command-line. Windows OS does not come with Python installed. Visit the official Python [download page](https://www.python.org/downloads/windows/) for Windows. Select the Windows installer (64-bit) or (32-bit). After the installer is downloaded, double–click the file. Select **Install launcher for all users**. Follow the prompts during installation. Make sure to select the **Add python.exe PATH** checkbox. This will allow you to launch Python from the command line. Once installation is complete, you can check for Python from the command line.

To check for Python, use the following command. The version of Python you installed will appear. 

python --version

## **Using the command line on Linux OS**

Access the Linux terminal using Ctrl + Alt + T. This will allow you to check for Python. Type python. Python comes preinstalled on most Linux systems. If the command is not found, you can install Python by writing sudo apt install python3. 

You can begin writing Python code from the terminal. Simply type python to use the interactive mode. You can also write Python scripts using Linux with IDLE which we will cover next. 

## **Using IDLE**

Python IDLE is included with Python installations on Windows and MacOS. You can download IDLE using your package manager on Linux. Python IDLE is an interactive interpreter or file editor that allows you to easily write Python scripts and programs. IDLE provides syntax highlighting, code completion, and automatic indentation. 

Double click on the IDLE icon to open it on your computer. This will open a blank Python interpreter window. You can begin writing code right away. 

![Image of the IDLE Shell with print("Hello, world!") and Hello, world! as the output](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/vxqTrO1gTkGVEzsKgBvsSw_d8df1191c611474c82b90221a30c4df1_F_1GIi2ugZ_nX3gBi9ZmgJTcXfF1Q_IfRjJ1s7Mxr-60kW6DaAfNIZZY6s82hvWe9HOPOISg6SrD64kc8pCsz34MfyMqF_PhKiNUC6LZoyStvnbxsgfX_LPhh9nRRl-6mkZQ69kzIWXydBFOtGw2fr6r-kOqtkC1_L82hsFVlZ-TZSDe9f6-DOB9Z40W2ne7YZDFh5zkcnahpr2N18ra4y1Yn3K4gkOHC0wb8w?expiry=1705536000000&hmac=unS7BQWmeFCmbaufo6PfHHBNzO_5tEGDCi1A1HeNNR4)

You can also open a new file. Go to File → Open → New File from the menu bar. Here you can write a Python file. Once you have completed writing your Python code in the file, go to File → Save As. Give your Python file a name. Hit Save. To run the Python code in the file you saved click Run → Run Module from the menu.

## [Sum.py](http://sum.py/) File

![Image of a code file titled sum.py that takes 2 variables and assigns a numerical value to them, adds them, and prints them](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/rE8T_JS1T9i-YDoko9T-Ig_2593c9b819974f478d692e40bd80d4f1_hvnI0TTdXoTa3DB1w75F3B4UmEuXQqX3bTETBM3IE1FBeN2L6tZR_YeUl25buJuvenAoKRrcV2b6qB6XgNOdzz5V5Y8qHnkLG6FOdxtOvIGCBx8HbH3A0OT-5fxvApN-D8qyvtZz_0ZDfytzkqGbmOcscxkJJ3PqQs-Lu4hkhK4H5xN4AJYTSmS3C50mqOYSXalsZg8KyLHOa8nuuiQNY8GRSVCbGTPU9crIYQ?expiry=1705536000000&hmac=J6KJ1Bsv8z5-d_ezUPLxrfT3u-CvufLTKgahosgnCZc)

## [Sum.py](http://sum.py/) Output

![Image shows the output of sum.py which is The sum of the numbers is: 3](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/XTAMT8dSTlS5YIRynTK00A_bbf2df9cda564a0ab2317df67207d5f1_dmNKlTyBm52jiUjHo9wR8majcE3eSUoVLSv3HNZwNIOqif86bxoFqTv6pcttqGBQK-xOoHzVMmTM2Nv2tWS5vfzoipCsb-lP5pCxEp44SI7GENvntNoQCsVrTSjljcqITAl8-cVG0BG-jT0etPGJ6hVLm593-B0zuIENmRC3sPXVw8ctVq_ddmvzz3n6UccpaBTBWbCIFkM-W8YYkjMtozVbNJQaFGIQH4bH5Q?expiry=1705536000000&hmac=uTFQ-cdZd0bgkvyDPqFAToQzKmU0V3ZFaBhGHDQ7Xx0)

## **Key takeaways**

Whichever operating system you are using, you will be able to run Python from the command-line.  Using a text editor like IDLE and running python from the command-line  is best for executing and debugging individual scripts or .py files. 

## **Resources for more information**

Here is a list of additional resources for writing and running Python on your local machine. 

- A [guide](https://towardsdatascience.com/a-quick-guide-to-using-command-line-terminal-96815b97b955) to using terminal (command-line) on Mac, Windows, and Linux operating systems. 

- [IDLE documentation and instructions](https://docs.python.org/3/library/idle.html)

- [Python Scripts vs. Jupyter Notebooks](https://learnpython.com/blog/python-scripts-vs-jupyter-notebooks/)
