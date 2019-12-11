# Install Packages for Python


## PIP

pip is the standard package manager for Python. It allows you to install and manage additional packages that are not part of the Python standard library.

https://realpython.com/what-is-pip/

### Install PIP

```shell
# Pip for Python 2
sudo apt-get install python2-pip
# Pip for Python 3
sudo apt-get install python3-pip 
```

### Update pip

```shell
python -m pip install --upgrade pip
```

Notice that you use python -m to update pip. The -m switch tells Python to run a module as an executable. This is necessary because in order for you to update pip, the old version has to be uninstalled before installing the new version, and removing it while running the tool can cause errors.
https://realpython.com/what-is-pip/

The command also works in python3:
```shell
python3 -m pip install --upgrade pip
```

## Anaconda

Anaconda® is a package manager, an environment manager, a Python/R data science distribution, and a collection of over 1,500+ open source packages.
An easy-to-install collection of high performance Python libraries along with Conda, our tool for managing packages and environments. Beyond the collection of open source packages in the Anaconda installer, you can use Conda to install over 1.5k packages (including the R language) from the Anaconda public repository and more than 20k packages from community channels, such as Conda-forge and bioconda. 

- https://docs.anaconda.com/anaconda/
- https://docs.anaconda.com/anaconda/install/linux/

### Install dependencies
sudo apt-get install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6

### Install Anaconda:
- Download installer from: https://www.anaconda.com/distribution/
- Recomended: verify file integrity with SHA-256: https://docs.anaconda.com/anaconda/install/linux/ 

After installing Anaconda, python3 may become the default python.


## Install usefull packages:

- [numpy](https://numpy.org/)
- [scipy](https://scipy.org/scipylib/)
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)

Anaconda also contains these packages, so if you installed Anaconda, these packages are already installed on your computer.


