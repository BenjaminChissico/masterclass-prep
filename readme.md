# Installation & Preparation Master class 


## Installation Python 

Follow these steps to install Python on your Notebook.

1. Close your VPN Connection 
2. Visit the following Page: https://docs.conda.io/en/latest/miniconda.html and download the MiniConda3 Windows 64-bit installation.
3. After downloading the installation exe, head to the downloads folder and install the software.
4. Make sure that you install it "for you", so you **do not need** admin-rights. 
5. Reboot your Notebook if necessary 




## Preparing the Python-Environment

After you've successfully installed Miniconda, you should have a new cli (command line interface). 
This new command prompt is called "Anaconda Prompt".  

Follow the next steps to create the environment in which the master class will be hold in 

- Create a new Folder, e.g., "masterclass".
- Navigate your anaconda prompt to that folder 
- run the following command in the anaconda prompts in this order:
    - `pip install virtualenv`
    - `python -m virtualenv .venv`
    - `.venv\Scripts\activate`
- Congratulations, you successfully downloaded virtualenv and created your first empty virtual environment called ".venv". In the very left corner of your Anaconda Prompt you should see now (.venv) in front of the cursor.
- run the following command to install the starting package for the course "jupyter lab" `pip install jupyterlab`

After the installation went through you should be able to open a "jupyter lab" by simply typing "jupyter lab" in the command line (you need to activate your environment first!).

If you restart your pc & you want to re-activate your virtual-environment just do the following steps:
- navigate to your "masterlcass" folder with the anaconda prompt 
- when there, type `.venv\Scripts\activate` and press enter 
- type `jupyter lab` and the jupyterlab should open in the browser.

<h2 align=middle>Happy Hacking </h2>













