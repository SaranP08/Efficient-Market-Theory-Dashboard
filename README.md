# Efficient-Market-Theory-Dashboard
A dashboard in python to perform Efficient Market Theory analysis

**SYNOPSIS**:
The Efficient Market Theory Analysis project aims to assess the efficiency of financial markets through statistical analysis of historical stock price data. The project employs the Runs Test, a non-parametric statistical test, to determine whether stock price movements exhibit randomness or if they are influenced by their past prices. This dashboard takes tickers of shares as input and performs EMT and gives a result of whether the firm is having a weak “Relation” or “Strong relation”.
INTRODUCTION TO TOPIC:
The Efficient Market Hypothesis (EMH) theorizes that financial markets are informationally efficient, meaning all available information is reflected in asset prices. This implies investors cannot consistently beat the market through fundamental or technical analysis. EMH comes in weak, semi-strong, and strong forms, with varying degrees of informational efficiency. While it promotes passive investing due to the difficulty of outperforming the market, critics argue for market inefficiencies and the potential for some investors to exploit them.
PROBLEM STATEMENT:
	Despite the popularity of Efficient Market Theory, there is a need for a strong analytical framework to empirically examine the efficiency of financial markets. Creating a tool that uses statistical analytic techniques, such as the Runs Test, to assess the randomness of stock price fluctuations can reveal useful information about market efficiency. By addressing this requirement, the initiative hopes to contribute to a better understanding of market dynamics and help investors, researchers, and policymakers make sound decisions.
**SCOPE**:
This study focuses on,
•	Extracting data and processing historical stock price data.
•	Calculating Mean, Standard Deviation, Z value, and Bounds.
•	Visualising the calculated metrics to get a better understanding.
OBJECTIVES:
1.	Develop a software tool capable of fetching historical stock price data from online sources.
2.	Implement statistical analysis techniques, particularly the Runs Test, to assess the randomness of stock price movements.
3.	Design an intuitive user interface that allows users to input stock symbols and select date ranges for analysis.
4.	Provide clear and interpretable results of the analysis, indicating the presence or absence of market inefficiencies.
5.	Explore the implications of the analysis results for investment decision-making, academic research, and regulatory considerations.
LIMITATIONS:
  While the Efficient Market Theory Analysis project holds promise for assessing market efficiency, it also faces several limitations:
    1.	Data Quality and Availability: 
       The accuracy and completeness of historical stock price data received from online sources can vary. The limited availability of high-quality data for specific stocks or time periods may have an impact on the credibility of the analysis results.
    2.	Assumption of Stationarity: 
        The Runs Test and other statistical approaches used in the analysis presuppose stationarity, which means that the data's statistical features remain constant throughout time. However, financial markets are dynamic and vulnerable to structural changes, making stationarity assumptions difficult to meet.
    3.	Sensitivity to Parameter Selection: 
        The effectiveness of the Runs Test and other statistical tests can be influenced by parameter selection, such as the significance level or analytic window size. Improper parameter selection can produce biassed or misleading findings.
    4.	Market microstructure effects: 
        Factors such as trade volume, bid-ask spreads, and market liquidity can influence stock price fluctuations and inject noise into analysis. Ignoring these aspects may result in an oversimplified analysis of market efficiency. 
    5.	Subjectivity in Analysis: 
        Despite the use of statistical methodologies, the interpretation of analysis results may still be subjective. Different analysts may interpret the same data differently, resulting in conflicting findings about market efficiency.

METHODOLOGY:
1.	Data Collection: 
The project utilizes the “yfinance” library to fetch historical stock price data. The “yfinance” goes to the Yahoo Finance website and fetches the Stock prices data. Specifically, it focuses on the Adjusted Close prices of selected stocks over a specified time period.
2.	Data Processing:
Adjusted close prices are used for calculations. NaN values are removed to ensure accuracy in the analysis.
3.	Tools Used:
  1.	Python: Programming language used for the application.
  2.	Tkinter: For the creation of GUI.
  3.	yfinance: A package in python which downloads stock prices data from Yahoo finance using the ticker names.
  4.	Pandas: Library for data manipulation and analysis.
  5.	NumPy: Library for numerical computations.
  6.	SciPy: Library for optimization.
  7.	Matplotlib: Library for plotting charts.
4.	Analysis: The analysis part is done by implementing the Efficient Market Theory. This uses several formulas to calculate Mean, Standard deviation, Bounds and Z-Score.

FINDINGS SUMMARY:
    The Efficient Market Theory Analysis project offers a robust framework for evaluating market efficiency through statistical analysis of historical stock price data. By employing the Runs Test and providing a user-friendly interface, the project facilitates informed decision-making, advances academic research, and promotes financial literacy in understanding market dynamics and investment principles.
FUTURE ENHANCEMENTS:
1.	Advanced Statistical Techniques: 
    Integration with additional statistical tests such as autocorrelation analysis or variance ratio tests for a more comprehensive assessment of market efficiency.
2.	Enhanced Visualization: 
    Improving visualization techniques to present analysis results through graphs, charts, or interactive dashboards for better interpretation and insights.
3.	Real-Time Analysis:
    Incorporation of real-time data streaming capabilities to enable dynamic monitoring and analysis of market conditions.
