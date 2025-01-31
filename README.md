IMDB Movie Dataset Data Analysis

In this Python data analysis project, the IMDB Movie Dataset is explored to derive insights into various movie aspects. Essential Python libraries such as Pandas, Seaborn, and Matplotlib are employed for efficient data manipulation and visualization.

Dataset Overview The dataset consists of 1000 entries, each representing a movie, featuring 12 columns providing information such as title, genre, director, year, runtime, rating, votes, revenue, and metascore.

Data Cleaning The initial step involves checking the dataset's shape, revealing 1000 rows and 12 columns. The identification of missing values, visualized through a heatmap, prompts their removal to ensure data integrity.

Handling Duplicates Duplicate entries are examined and removed to enhance the dataset's clarity and avoid redundancy. 

![IMBD Result1](https://github.com/user-attachments/assets/e4a990a1-ec3e-49b6-b254-9fe0a72b976f)

Exploratory Data Analysis (EDA) EDA is conducted to unveil patterns and trends. It includes displaying overall statistics, identifying lengthy movies, determining the highest average voting and revenue per year, and assessing the rating's impact on revenue.

Top Movies Analysis The identification of the most popular movies based on revenue and highest ratings is performed. Additionally, movies are classified into categories like "Excellent," "Good," or "Average" based on their ratings.

Genre Analysis An exploration of genre information involves counting the number of action movies and finding unique genre values.

List of functions used in the "IMDB Movie Dataset Data Analysis" project:

Pandas Functions:

pd.read_csv(): Reads the dataset from a CSV file. isnull().sum(): Counts the missing values in the dataset. dropna(): Drops rows with missing values. duplicated().any(): Checks for duplicate rows. describe(include='all'): Provides overall statistics about the dataframe. Seaborn Functions:

heatmap(): Visualizes missing values using a heatmap. barplot(x, y, data, hue, dodge): Plots bar graphs for various analyses. scatterplot(x, y, data): Creates a scatter plot for analyzing the relationship between two variables. Matplotlib Functions:

plt.figure(figsize=(width, height)): Sets the figure size for plots. plt.title(): Adds a title to the plot. plt.show(): Displays the plot.

![IMBD Result2](https://github.com/user-attachments/assets/8dfac3c0-633b-45fd-aedb-42344ce7b652)

