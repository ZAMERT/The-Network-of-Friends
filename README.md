# The Network of Friends: Mapping Character Interactions and Popularity

This project analyzes **character relationships** and **popularity patterns** in the TV show **Friends** using a custom built graph system. 
Each character is represented as a node, and edges reflect the frequency of co-occurance of characters. 
Using this network, the project explores relationship structures, centrality rankings, shortest paths, and how interaction patterns relate to episode scores and viewership. 
This project is developed as the final project for SI507 at the University of Michigan.

## Project Goals

- Build a graph that captures **who appears with whom** across the entire series. 
- Analyze **relationship patterns**, **centrality**, and **network connectivity**. 
- Link graph structure to **episode popularity**. 
- Provide an interactive and analytical toolkit for exploring characters. 

--------------------

## Data Sources

This project uses several publicly available datasets from Kaggle. 

### 1. **FRIENDS TV Series -Screenplay Script(Text)**
- Source: Kaggle. 
- Contains full dialogue text with episode metadata.   
- Used to determine co-occurrence of characters. 
- URLs: https://www.kaggle.com/datasets/blessondensil294/friends-tv-series-screenplay-script

### 2. **Friends Series Dataset (Ratings)**
- Source: Kaggle.
- Contains titles, summaries, and **episode ratings**. 
- Used to compute per-character popularity scores. 
- URLs: https://www.kaggle.com/datasets/rezaghari/friends-series-dataset?select=friends_episodes_v3.csv

### 3. **Friends Episode Data (viewers)**
- Source: Kaggle.
- Contains **US viewers number** for each episode. 
- Used to enhance popularity and interaction analysis. 
- URLs: https://www.kaggle.com/datasets/bcruise/friends-episode-data/data

**Note:**
Only some small sample scripts are included in this repository. 

--------------------



