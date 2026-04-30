# California State University Crime Statistics Analysis
Data and files for CS 133 Spring 2026 Term Project

## Installation
We are using the  local setup using VS Code and a cloud-based approach using Google Colab.

Method 1: Local Setup with VS Code
This method is for running the analysis on your own machine and managing the files locally.
1. Clone the Repository: Open your terminal or command prompt and navigate to the folder where you want to save the project. Run the following command to copy the repository: 
`“https://github.com/CS133-DataVisualization/term-project-crimefighters101.git”`
2. Open in VS Code: Launch VS Code, select File > Open Folder, and choose the newly created project directory.
3. Install Dependencies: Ensure you have Python installed. Open the integrated terminal in VS Code and install the required libraries using the following command: 
`pip install numpy matplotlib seaborn pandas`
4. Run the Program: Open the main Python script or Jupyter Notebook file within VS Code and click the Run icon to begin the sequence analysis.

Method 2: Google Colab
This is the method with no need to install software locally or for cloud computing resources.
1. Upload to Google Drive: Download the repository as a ZIP file from GitHub and extract it. Upload the folder to Google Drive.
2. Open Google Colab: Navigate to colab.research.google.com and sign in with Google account.
3. Load the Notebook: Select File > Upload notebook and choose the .ipynb file from extracted folder, or select the GitHub tab to pull the code directly into Colab.
4. Mount Google Drive: If sequences are stored in a CSV file on the drive, run the following code snippet in a Colab cell to grant access:
`from google.colab import drive`
`drive.mount(‘/content/drive’)`
5. Install Libraries: Google Colab comes with most libraries pre-installed. However, if any are missing, install them by running a cell with: 
`!pip install numpy matplotlib seaborn pandas`
