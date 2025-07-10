# finance-python-projects
A collection of my data analysis and machine learning projects focused on financial data.

### Project 1: Exploratory Data Analysis and Storytelling of S&P 500 Sector Data
Objective: To conduct an in-depth exploratory data analysis of S&P 500 sector information to uncover trends, correlations, and predictive insights into the U.S. economy.

#### Key Responsibilities & Achievements:
* Sourced and downloaded S&P 500 sector data from iShares using web scraping techniques.
* Performed comprehensive data cleaning and preprocessing to ensure data quality and prepare it for analysis.
* Conducted descriptive statistical analysis to understand the distribution of sector weights, identifying key metrics such as mean, standard deviation, and percentiles.
* Developed and interpreted a correlation matrix and heatmap to visualize relationships between different sectors over a 20-year period.
* Created various data visualizations, including pie charts and histograms, to present findings in a clear and compelling manner.
* Analyzed the historical weights of the Consumer Discretionary sector and estimated the probability density function (PDF) using Kernel Density Estimation (KDE).
* Investigated the impact of the Energy sector's performance on the Consumer Discretionary sector by analyzing conditional distributions.
* Developed predictive insights into future sector performance by analyzing historical data around major economic events like the Global Financial Crisis and the Dot-com bubble.

Technologies Used: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

### Project 2: ETF Recommender System
Objective: To develop an ETF recommender system for Charles Schwab by analyzing ETF holdings and identifying similar investment vehicles.

#### Key Responsibilities & Achievements:
* Extracted and transformed ETF holdings data from a MongoDB collection.
* Created a comprehensive universe of stock tickers by combining holdings from multiple ETFs, including SPY, IVV, QQQ, and ARKK.
* Calculated Cosine and Jaccard similarities between ETFs based on their underlying holdings to measure their resemblance.
* Built a recommender system that suggests similar ETFs to a given input ETF, providing investors with alternative investment options.
* Utilized the Finviz API to enrich the dataset with additional financial metrics and perform further analysis.

Technologies Used: Python, Pandas, PyMongo, Scikit-learn, Finviz, MongoDB, Jupyter Notebook

### Project 3: Analysis of Earnings Call Transcripts for Stock Categorization and Insights
Objective: To analyze earnings call transcripts to categorize stocks and extract meaningful insights using natural language processing (NLP) and machine learning techniques.

#### Key Responsibilities & Achievements:
* Automated the collection of earnings call transcript URLs from Seeking Alpha using Selenium.
* Utilized BeautifulSoup to scrape and extract the full text of the earnings call transcripts.
* Applied a suite of NLP techniques for text preprocessing, including tokenization, stop-word removal, lemmatization, and part-of-speech filtering.
* Implemented a supervised machine learning model (Logistic Regression) to classify stocks as either belonging to the ARKK ETF or not, based on the language used in their earnings calls.
* Employed an unsupervised machine learning technique (Latent Dirichlet Allocation - LDA) to identify and visualize 15 key topics discussed in earnings calls across different companies.
* Compared the prevalent topics in ARKK ETF companies with those in other ETFs to identify distinctive investment themes and strategies.

Technologies Used: Python, Pandas, Scikit-learn, NLTK, BeautifulSoup, Selenium, Jupyter Notebook
