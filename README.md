This program utilizes a machine learning clusters algorithm called K-Means to
reprsent data in a graph of clusters. The data is cleaned up and organized into
a pandas dataframe. The dataframe then goes through the K-Means algorithm then
finally inputted into a scatterplot graph to represent the data.

To execute the program, from the command line convert the code from notebook to
python by using this command:
jupyter nbconvert --to python nb.ipynb

After the command has been ran, execute the program like a python program by doing:
python nb.py

You may need to install the python mistune package for this to work and here is the
command for that:
sudo pip install -U mistune
