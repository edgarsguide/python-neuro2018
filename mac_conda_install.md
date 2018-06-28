# Installing Python on macOS with Anaconda

It turns out that there is more than one way to install Python. While there are pros and cons for each method, if you are just starting out with Python for scientific computation, I highly recommend that you start out with [Anaconda](https://www.anaconda.com). Anaconda distribution bundles together the Python interpreter (the piece of software you will use to run Python code) with many essential scientific computation Python packages. Here, I provide a step-by-step instructions for installing Python along with essential scientific computing packages and a text editor all through the installation of Anaconda. Let's get started!

### Python on macOS

You may happen to know that every macOS actually comes with Python already installed. While this is absolutely true, the version of Python that comes bundled with your machine is usually quite old (macOS typically comes with Python 2, and not Python3). Furthremore, the Python that comes with the OS is considered a *system Python* and usually requires a lot of care to make sure that you don't accidentally affect other softwares on your machine that might depend on that version of Python. Long story short, it is highly recommended that you install a separte (and a newer) copy of Python for your own use so that you don't have to worry about messing with the system!

### Need help?

I highly recommend that you try to follow this instruction closely and see if you can figure out any issue that arise. Due to the large variation in computer system configurations, no instruction is perfect, and being able to figure out quirks in the instructions and finding your own solution would become vital skill in computer programming in general! However, knowing when to turn for help is just as essential of a skill, so if you get really stuck, then you can always contact me for help!

## 1. Downloading Anaconda

Visit https://www.anaconda.com/download/. Click on the macOS logo by `Download For`:

![visit anaconda](images/mac_conda_install/visit_anaconda.png)

At the bottom of the page, hit "Download" for **Python 3.6** (not Python 2.7!). Wait for the download to complete.

![download anaconda](images/mac_conda_install/select_python3.png)



## 2. Installing Anaconda Distribution

Once the installer completes downloading, launch the installer.

![installer](images/mac_conda_install/starting_anaconda_installation.png)

Go ahead and follow the installation procedure - you don't have to change anything.

![installer](images/mac_conda_install/installing_anaconda.png)

After a couple screens, Anaconda starts installing. Go ahead and grab a cup (or two) coffee - the installation can take some time to complete.

### Installing Visual Studio Code (VSCode)

Once the installation completes, Anaconda will offer to install [Visual Studio Code](https://code.visualstudio.com/) - a coding text editor filled with a lot of features useful for programming. Unless you already have a text editor of your choice (e.g. vim, emacs, Atom, Brackets, etc.), **I strongly recommend that you install Visual Studio Code** at this step. 

If you decide to install it,  hit "Install Microsoft VSCode" button and follow the instructions on the installation screen to complete the installation. If you don't want to install VSCode now, you can always visit VSCode website https://code.visualstudio.com to download and install it at a later time.

![install VS Code](images/mac_conda_install/install_vscode.png)



If everything goes well, the Anaconda distribution installation should complete without an issue! Hit "Finish" to exit out of the installation.

![complete Anaconda install](images/mac_conda_install/anaconda_installation_complete.png)



## 3. Checking Anaconda Installation

To verify the Anaconda installation, let's go ahead and learn to launch Jupyter Lab environment. To do so, we are going to use a **terminal**. From Finder, navigate through `Applications > Utilities > Terminal` and launch the terminal program. 

![anaconda prompt](images/mac_conda_install/launching_terminal.png)

![anaconda prompt](images/mac_conda_install/running_terminal.png)

Once you would be greeted with a simple window with a few words and a blinking cursor. Using such **terminal program**, you can execute Python scripts, install Python packages, and launch tools like Jupyter Lab. It may not be the most visually appealing piece of software, but you will gain a lot by learning to be a bit familiar with it. To launch Jupyter Lab, simply type in `jupyter lab` in the terminal window, and hit `Enter`.

![start Jupyter Lab](images/mac_conda_install/launch_jupyterlab.png)

This should launch a web browser, and take you the Jupyter Lab top page.

![jupyter lab](images/mac_conda_install/launched_jupyterlab.png)

If you got this far, then congratulations! You have successfully installed and verified your Anaconda distribution, and you are now ready for Python workshop week 2 and beyond. 