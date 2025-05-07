Documentation to set up environment
# Unfinished, will need to format via Markdown and provide specific links and make it look pretty
Welcome! ReVISit Python Bindings is an internal tool used by operators of ReVISit to take adavantage of 
Jupyter's analytical qualities to provide better insights on the results of studies. Perfect for
AI/ML and data science applications.

Setup steps
1. Make sure that VSCode is installed on your environment, and within VSCode, Jupyter Notebook 
and Python. You can install VSCode to your device here: https://code.visualstudio.com/download .
You can navigate to the VSCode store to install Jupyter Notebook for free, and install Python.
2. Branch and then clone the repository to VSCode. You can do this by navigating to the repository,
creating a branch, and then clicking the 'clone' button 
3. Within the terminal, you will need to install a couple of commands:
    pip install revisitpy
    pip install revisit
    pip install revisit_server
4. Finally, run this command:
    uv sync
5. If everything is installed correctly, you should be able to run studies directly within the IDE.
If you are unable to run it, try manually installing required dependencies according to the error
messages by using the IDE terminal.