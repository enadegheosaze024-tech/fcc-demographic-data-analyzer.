This is my second project in the freeCodeCamp Data Analysis with Python certification. I used the Pandas library to analyze a dataset of demographic data extracted from the 1994 Census database

**Project Purpose:**
The goal of this program is to perform a descriptive statistical analysis on a population dataset to identify relationships between education, work habits, and income levels.By running this code, we can answer specific demographic questions such as:
1. How many people of each race are represented in the data?
2. What is the average age of men?
3. What is the percentage of people who have a Bachelor's degree?
4. Does a higher education (Bachelors, Masters, or Doctorate) actually lead to a higher salary ($>50K$)?What are the minimum hours a person works per week, and what percentage of those "minimum workers" are high earners?Which country has the highest percentage of people that earn $>50K$?

**The Learning Journey and Challenges:**
As a learner, this project was a significant step up from basic NumPy calculations. I encountered several "real-world" coding hurdles that taught me more than the documentation ever could:

1.The "Hidden Symbol" Trap: Initially, my calculations for high-income earners returned 0.0%. I discovered that searching for "50K" wasn't enough because the dataset used ">50K". I learned to always inspect the unique values in a column before filtering.

2.Variable Scope Errors: I ran into an UnboundLocalError when trying to define num_min_workers. This taught me the importance of separating my filtered DataFrames from my scalar counts.

3.Chained Indexing vs. Coordinates: I learned why we use df[filter]['column'] to "drill down" into data and the difference between row filtering and column selection.

4.The Git "Permission Denied" 403: My biggest non-coding challenge was realizing that local boilerplates are often pre-linked to the source. I had to learn how to remove remote origin to successfully push my work to my own GitHub profile.

**Technologies Used:**
1. Python 3

2. Pandas: For data manipulation and "drilling down" into census categories.

3. Visual Studio Code: My local development environment.

4. Git/GitHub: For version control and portfolio hosting.

   **How to Use This Program:**
To run this project locally, follow these steps:
1. Clone the Repository:
git clone https://github.com/enadegheosaze024-tech/fcc-demographic-data-analyzer.git
2. Navigate to the folder: cd fcc-demographic-data-analyzer
3. Ensure you have Pandas installed:
type 'pip install pandas' in your terminal
4. Run the analysis:
type 'python main.py' in your terminal

**Key Insights Found:**
1. Education Impact: Approximately 46.5% of people with advanced degrees (Bachelors, Masters, or Doctorate) earn more than 50K, compared to only 17.4% of those without.

2. Global Trends: In this dataset, Iran had the highest percentage of high-income earners at 41.9%.

3. Top Career in India: The most common high-income occupation for individuals in India is Prof-specialty.

   
