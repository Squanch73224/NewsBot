# NewsBot: Getting Started Guide
NewsBot.JupyterNotebook

# Hi, welcome to the Git! To create this simple news bot, you will need:
1. A computer with a terminal, PowerShell, or command prompt.
2. The `requests` library for making HTTP requests.
3. Python installed on your system.
4. Jupyter Notebook for interactive coding.
5. An API key from News API.
6. A text editor like Notepad or TextEdit to save your API key.

# Step 1: Obtain API Key
- Visit [News API](https://newsapi.org/) and click "Get API Key".
- Follow the instructions to register for an API key.
- Copy your API key.
- Open text edit or notebook to past your API key and save it in a txt file in a secure location.

# Step 2: Install Libraries
- Open up your terminal and make sure you have the latest python version installed.
To check your python version in the terminal type: 
1. python --version
2. python -V
3. python
- Update Python to the latest version using appropriate commands for your operating system.
To update to the latest python version type in the terminal for...
1. Lunix Operating System:
   sudo apt update
   sudo apt upgrade python3
2. MacOS:
   brew update
   brew upgrade python
3. Windows:
   download from python website: [python](https://www.python.org/downloads/)
   
NOTE: Linux Debian is easier to use!!! USB needed for installation: [youtube](https://youtu.be/Owr-PGxFBQE?feature=shared)

- Create a virtual environment using `python3 -m venv myenv` or 'python -m venv myenv'
- Activate the virtual environment with `source myenv/bin/activate` for Linux/MacOS or `myenv\Scripts\activate` for Windows.
- Install the `requests` library with `pip install requests`.
- Install Jupyter Notebook with `pip install jupyter notebook`.
- Launch Jupyter Notebook using `jupyter notebook` command in the terminal.

# Step 3: Code
- Copy the template code from the "Create NewsBot" file in this Git repository.
- Paste the code into a cell in Jupyter Notebook.
- Replace `API_KEY = "ENTER_YOUR_API"` with your News API key.
- Modify the `query` variable to specify the topics you want to search for using [space]/AND/OR in between words as needed.
- Customize the code further in the parameters section according to your preferences, Goodluck!

# Code Rundown:
- **Imports**: Import the `requests` library for making HTTP requests.
- **Define URL**: Define the URL of the server's API endpoint.
- **Define Parameters and Headers**: Specify parameters and headers for the HTTP request.
- **Make HTTP GET Request**: Send an HTTP GET request to the server's API endpoint.
- **Handle Success or Failure**: Check the status code of the response to determine if the request was successful. Print response content if successful; otherwise, print an error message.
