# Fitness-Market-Analysis

![1](https://github.com/hhuseyincosgun/Fitness-Market-Analysis/assets/21257660/69becc72-73da-4384-b8b2-c31918bf8e21)

In this project, we will query the local and global fitness landscape to identify the international niche for our fitness products. We will use **[Pandas](https://pandas.pydata.org/docs/)** to analyze data related to online interest in _home gyms, gym workouts, home workouts_, and fitness products.

# Project Overview

In this project, we aim to identify the international market for fitness products by querying local and global fitness landscapes. The project involves various analyses and visualizations using the following key libraries:

## Used Libraries

- **pandas (pd):** Used for data manipulation and analysis. [Official Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- **seaborn (sns):** Employed for data visualization; the style and color palette were set to 'white' and 'Pastel2', respectively. [Official Documentation](https://seaborn.pydata.org/)
- **matplotlib.pyplot (plt):** Utilized for creating graphs. [Official Documentation](https://matplotlib.org/stable/contents.html)
- **os:** Used for operating system operations. [os Module Documentation](https://docs.python.org/3/library/os.html)



## Functions and Descriptions

1. **read_file(filepath, plot=True):**
   - Reads a CSV file and converts it into a pandas DataFrame.
   - Returns a processed DataFrame with three columns: ***'week', 'region', and 'interest'***.
   - Creates a line plot using Seaborn to visualize the data.

2. **read_geo(filepath, multi=False):**
   - Reads a CSV file and converts it into a pandas DataFrame.
   - Returns a processed DataFrame with two columns: ***'country'*** and ***'interest'***.
   - Creates a bar plot using Seaborn to visualize the data.
   - Uses multi=True if analyzing more than one keyword, otherwise multi=False.

## Project Steps and Usage

1. **Global Fitness Interest Analysis:**
   - Evaluates international fitness interest using data from the ***'workout.csv'*** file.

2. **Fitness Interest Trends:**
   - Compares trends in interest for home workouts, gym workouts, and home gyms using data from the ***'three_keywords.csv'*** file.

3. **Fitness Interest by Regions:**
   - Segments regional fitness interest using data from the ***'workout_global.csv'*** file.

4. **Home Workouts and Regions:**
   - Evaluates the demand for home workouts, gym workouts, and home gyms regionally using data from the ***'geo_three_keywords.csv'*** file.

5. **Interest Analysis by Country and Category:**
   - Conducts an in-depth analysis by examining yoga and zumba interest in specific countries.
