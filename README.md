# Python Big Data Demo

In this demo, we will use something called **Jupyter Notebook** and a few other **Python** libraries. And we gonna use **Anaconda** to install them. For more information about this tools just search for them on google.

### Install Anaconda
To install **Anaconda** just search for **Anaconda Python** or acces directly this [link to Anaconda](https://anaconda.org/) and install it on your machine. It's recommended to install the Python 3.6 version. Follow the instruction and install it on your machine.

### Lunch Jutyper
1. After installation of Anaconda, we have to lunch Jutyper. We will do this throw **Anaconda Navigator**. Just search for **Anaconda Navigator** on your machine and lunch it.

2. Click `Lunch` button under Jupyter module. This will create a local server.***Don't close the terminal window that appears, because the server will shout down***

3. Create a directory folder on your machine and put there the **data file** that you have recived and navigate to it in the **navigation window** that appears after lunching **Jupyter**.

4. Alaso in that directory create a new **Python File** by pressing the `New` button on the right and select **Python 3**

### Vizualization of data
Here should appear a kinda ***command line*** window, this is were you will writte our commands for visualization data.

1. Now we have to import some libraries to work with. First we will import **Panda Library**. Write this command:
```
import pandas as pd
```
and click `Run` button

2. Import another ***module*** called **pyplot** from the **matplotlib** library, this will help as to plot some cool graphs. Writte this command:
```
from matplotlib import pyplot as plt
```
and click `Run` button

3. To work with the data, firstly we have to import it and stock it into a variable. Writte this command:
```
sample_data = pd.read_csv('winequality-white.csv')
```
Inside the parantases write your file name and click `Run` button

4. To see the whole table just writte the variable name and hit `Run` button. In this case
```
sample_data
```
If the file is valid you should see the table in a very friendly way.
