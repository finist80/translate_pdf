# Introduction 
TODO: template repo with folder structure set up (inputs, outputs, src code, yml environment setup & jupyter notebook)

# Prerequisites
1.	Ensure you have Miniconda: https://repo.anaconda.com/miniconda/Miniconda3-py39_4.11.0-Windows-x86_64.exe
2.  Ensure you have vscode: https://code.visualstudio.com/download
- you may need to install the Jupiter extension in VS code
- If it says you don’t have it set up – you will need to download git from (https://git-scm.com/) and follow the instructions. I just did all the defaults:Git (git-scm.com)

# Set up repo:
1. Next to the the name of the repo, 'template', click the more options then "fork":
![alt text](delete/clone.png)


2. Enter name & continue
![alt text](delete/clone.png)

3. Next to the the name of the **new** repo, click the more options then "clone":

![alt text](delete/clone.png)


4. Click 'Clone in VS Code' under 'IDE':
![alt text](delete/clone_vs.png)

5. Accept any security questions:

6. Select the right option for you:

7. Set up environment:
- 

	Open Anaconda Prompt from ‘Start’ -> ‘Anaconda3 (64 bit)’ -> ‘Anaconda Prompt’, enter “conda init”.


After Anaconda is installed, the next step is to create the Anaconda environment which will install all the necessary package dependencies. To do this, you will need to open a Command Prompt window. You can search for Command Prompt from the windows start menu to open the Command Prompt.
Here is link for the Anaconda environment file on sharepoint: sfile_wrts.yml. We will use this file later so please copy this file to your local location.
From the Command Prompt you type or paste the command seen below after replacing “C:\path\to\sfile_wrts.yml” with the path to the .yml file on your machine:
•	conda env create -f C:\path\to\sfile_wrts.yml

8. Set up jupyter notebook: kernel & imports

9.  Make changes, stage, commit & sync

# Contribute
TODO: feel free to contribute to make this better, but please don't overwrite the template!
