# FB-Player
**README**

**Data Description:**
The dataset contains information about football players from the English Premier League. The attributes include:
- `name`: Name of the player
- `club`: Club of the player
- `age`: Age of the player
- `position`: Position of the player on the pitch
- `position_cat`: Categorical representation of player positions (1 for attackers, 2 for midfielders, 3 for defenders, 4 for goalkeepers)
- `market_value`: Market value of the player as of July 20th, 2017
- `page_views`: Average daily Wikipedia page views from September 1, 2016, to May 1, 2017
- `fpl_value`: Value of the player in Fantasy Premier League as of July 20th, 2017
- `fpl_sel`: Percentage of Fantasy Premier League players who have selected that player in their team
- `fpl_points`: Fantasy Premier League points accumulated over the previous season
- `region`: Region of the player (1 for England, 2 for Europe, 3 for Americans, 4 for Rest of the world)
- `nationality`: Nationality of the player
- `new_foreign`: Whether the player is a new signing from a different league for the 2017/18 season (as of July 20th)
- `age_cat`: Categorical representation of player age
- `club_id`: ID of the club
- `big_club`: Whether the player belongs to one of the top 6 clubs
- `new_signing`: Whether the player is a new signing for the 2017/18 season (as of July 20th)

**Task:**
The task is to predict the market value of a player using linear regression and to investigate the data using Seaborn for visualization.

**Steps to Perform:**
1. Load the dataset and perform data exploration to understand the characteristics of the data.
2. Use Seaborn for data visualization to identify any patterns or relationships between variables.
3. Preprocess the data by handling missing values, encoding categorical variables, and splitting the dataset into training and testing sets.
4. Build a linear regression model to predict the market value of players based on the available features.
5. Evaluate the performance of the model using appropriate metrics such as mean squared error or R-squared.
6. Fine-tune the model if necessary and reevaluate its performance.
7. Provide insights and conclusions based on the model's predictions and the data visualization findings.

**Files Included:**
1. `EPL_players_dataset.csv`: CSV file containing the dataset.
2. `EPL_players_analysis.ipynb` (or `.py`): Jupyter Notebook (or Python script) containing code for data exploration, visualization using Seaborn, and building the linear regression model.
3. `README.md`: This readme file providing an overview of the task, data, and steps to perform.

**Dependencies:**
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

**Instructions:**
1. Clone the repository to your local machine.
2. Install the required dependencies using pip or conda.
3. Run the Jupyter Notebook or Python script to perform data analysis and build the linear regression model.

**Note:**
Ensure that the dataset file (`EPL_players_dataset.csv`) is placed in the same directory as the Jupyter Notebook or Python script for proper execution.
