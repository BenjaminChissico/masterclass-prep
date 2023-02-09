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
- Put the requirements_udpated.txt file in the "masterclass" folder 
- run the following command `pip install -r requirements_updated.txt`

Let the installation finish, this can take a few minutes(15-30 minutes).
Congratulations, you successfully installed python, created your first virtual environment, and installed all necessary libraries for the masterclass course!


If you restart your pc & you want to re-activate your virtual-environment just do the following steps:
- navigate to your "masterlcass" folder with the anaconda prompt 
- when there, type `.venv\Scripts\activate` and press enter 

<h2 align=middle>Happy Hacking </h2>














