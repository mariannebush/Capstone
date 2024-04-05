# World Happiness Report

![Happiness](https://github.com/mariannebush/Capstone/assets/142458084/45dca488-568c-4cdf-be32-d1856c0c974e)

# Explanation of Project

The World Happiness Report is a partnership of Gallup, the Oxford Wellbeing Research Centre, the UN Sustainable Development Solutions Network, and the WHR’s Editorial Board. The report is produced under the editorial control of the WHR Editorial Board.

The World Happiness Report reflects a worldwide demand for more attention to happiness and well-being as criteria for government policy. It reviews the state of happiness in the world today and shows how the science of happiness explains personal and national variations in happiness.

I decided to investigate the happiness report data to determine what trends I could discover.

Features

1) Loading Data: Reading in two .xls files
2) Clean and operate on the data: Merged .xls files and eliminated missing data
3) Visualize and present the data: Tableau Dashboard
4) Best Practices: Virtual environment and a data dictionary
5) Interpretation of the data: Summarized at the end of this Readme


# Data Dictionary

![image](https://github.com/mariannebush/Capstone/assets/142458084/98d06a22-d5af-42ac-a250-9718bbc9e7bb)


# How to Run My Project and Best Practices

In order to run my project, you will need Git and Jupyter Notebook. 
* To install Git, please follow the instructions on Git's website: https://github.com/git-guides/install-git
* To install Jupyter Notebook, please follow the instructions on Jupyter's website: https://docs.jupyter.org/en/latest/install/notebook-classic.html

Once you have installed the software, please navigate to my repository and clone it. You can find instructions on how to clone a repository on Git's website: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

Open Git and enter the following commands to create a virtual environment:

#### Windows

python -m venv venv

source venv\Scripts\activate

pip install -r requirements.txt

#### Linux/Mac0S

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt


After the virtual environment is created, enter “git clone” followed by the URL you copied when cloning the repository. Navigate to where you cloned the repository. Run the file Happiness.ipynb. In order to exit the virtual environment enter "deactivate".

# Visualizations and Interpretation  

Please visit my Tableau Public page here in order to view the visualizations I created for my World Happiness Report Project: https://public.tableau.com/app/profile/marianne.bush/vizzes

- Click on "World Happiness Report"

### Geographic Representation of Happiness Score
The geographic representation of happiness scores displays ladder life scores throughout the world. Red represents the lowest happiness scores and dark green represents the highest happiness scores. It appears that the lowest happiness scores are found primarily in Africa.

### Happiness Scores over Time for the Top 5 Countries (Ranked in 2024)
The happiness scores over time for the top 5 countries (as ranked in 2024) shows that this year's top 5 countries consistently have relatively good happiness scores, although there is some fluctuation in scores. Particularly in Israel, there seem to be sharp drops and increases in happiness scores over short periods of time.

### Changes in Happiness Scores over the Past 10 Years in North America
The happiness scores in North America show that all three countries consistently have relatively good happiness scores. Mexico bottomed out in 2020/2021, but seems to have rebounded recently to higher scores. Canada and the United States have had similar drops in their happiness scores, with the United States happiness scores lower than Canadian happiness scores.


