# NASA Space Apps 2020 by Hacker's Tribe Foundation - Delhi

Steps to ensure while uploading your project:

- Create the main directory with your team name
- Inside this main directory should be 3 things:
    - Source Code and/or Link to hosted implementation
    - README.md file (Format can be copied from README-Team.md file)
    - Presentation (Powerpoint or Google Slides) or Video

[How to create a Pull Request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github)

**NOTE** - Use Github Desktop if using Windows to upload the files

## RESOURCES
### Procedure for installing Jupyter Notebook and Python via Anaconda
- Download Anaconda
    - [Linux](https://www.anaconda.com/download/#linux)
    - [MacOS](https://www.anaconda.com/download/#macos)
    - [Windows](https://www.anaconda.com/download/#windows)
- Install version of Anaconda which you downloaded, following the instructions on the download page
- Congratulations, you have installed Jupyter Notebook!
- You can start the notebook server from the command line (using Terminal on Mac/Linux, Command Prompt on Windows) by running - jupyter notebook

### Import the dataset and Load the dataset

import pandas as pd

read_file = pd.read_csv('filename.csv')