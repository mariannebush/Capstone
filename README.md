# World Happiness Report

![Happiness](https://github.com/mariannebush/Capstone/assets/142458084/45dca488-568c-4cdf-be32-d1856c0c974e)

# Explanation of Project

The World Happiness Report is a partnership of Gallup, the Oxford Wellbeing Research Centre, the UN Sustainable Development Solutions Network, and the WHR’s Editorial Board. The report is produced under the editorial control of the WHR Editorial Board.

The World Happiness Report reflects a worldwide demand for more attention to happiness and well-being as criteria for government policy. It reviews the state of happiness in the world today and shows how the science of happiness explains personal and national variations in happiness.

I investigated the happiness report data to determine what trends I could discover.

Features

1) Loading Data: Read in two .xls files
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

Open Git and enter the following commands to create a virtual environment:

#### Windows

python -m venv venv

source venv\Scripts\activate

pip install -r requirements.txt

#### Linux/Mac0S

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

After the virtual environment is created, please return to this repository and clone the repository to your computer. You can find instructions on how to clone a repository on Git's website: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

Navigate on your computer to where you cloned the repository. Run the file Happiness.ipynb. In order to exit the virtual environment enter "deactivate".

# Visualizations and Interpretation  

Please visit my Tableau Public page here in order to view the visualizations I created for my World Happiness Report Project: https://public.tableau.com/app/profile/marianne.bush/vizzes

- Click on "World Happiness Report"

### Geographic Representation of Happiness Score
The geographic representation of happiness scores displays life ladder scores throughout the world. Red represents the lowest happiness scores and dark green represents the highest happiness scores. It appears that the lowest happiness scores are found primarily in Africa. Eastern Europe, Asia and the Middle East have lower happiness scores that North America and Western Europe. 

### Happiness Scores over Time for the Top 5 Countries (Ranked in 2024)
The happiness scores over time for the top 5 countries (as ranked in 2024) show that this year's top 5 countries consistently have relatively high happiness scores, although there is some fluctuation in the scores. Particularly in Israel, there are sharp drops and increases in happiness scores over short periods of time.

### Changes in Happiness Scores over the Past 10 Years in North America
The happiness scores in North America show that all three countries consistently have relatively high happiness scores. Mexico bottomed out in 2020/2021, but has rebounded recently back to a higher happiness score. Canada and the United States have had similar drops in their happiness scores. In the United States happiness scores are lower than Canadian happiness scores.


