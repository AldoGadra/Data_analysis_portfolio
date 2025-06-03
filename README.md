# Aldo Gadra - Data Analysis Portfolio

## About
Hello everyone! My name is Aldo Gadra, and I am an aspiring data analyst focusing on business analytics and econometrics. I have an adequate understanding of statistics, such as data distribution, regressions, and machine learning techniques. This is also supported by my excellent grasp on data analysis tools such as Excel, Python, Tableau, and SQL. The combination of both knowledge and skill set serves as a strong foundation for me to prepare, clean, analyze, and visualize data in order to aid the data-based decision process. 

In my spare time, I enjoy doing data analysis and research on geeky pop culture topics like comics and games. Which you could find more on my Medium page [here](https://medium.com/@aldgadra). I adore investigating niche pop culture topics and gathering insights that geeks enjoy.

In this portfolio, I have included projects showcasing my analytical capability along with corresponding technical skills for business and general data analytics topics.

# Portfolio Project

### Kickstarter Success Rate Analysis

**Code**: [Kickstarter Success Rate Analysis](https://github.com/AldoGadra/Data_analysis_portfolio/blob/main/kickstarter_success_rate/Kickstarter_Success_Rate.ipynb)

**Article**: [What Made Kickstarter’s Success Rate so Low?](https://medium.com/p/f5dc575005f9)

**Description**: Kickstarter is a widely popular crowdfunding platform to help people start their own business or projects. But their success rates tends to fluctuates time to time, and may waste their vast potential. This project aims to explore variables that correlates and may caused the mentioned fluctuation. This projects includes several data analysis and testing methods that includes EDA, Seasonal Trend Decomposition (STL), and changepoint analysis. 

**Original Dataset**: [Kickstarter Projects](https://www.kaggle.com/datasets/ulrikthygepedersen/kickstarter-projects)

**Skills**: Data cleaning, data wrangling, data visualization,  STL, and changepoint analysis. 

**Tools**: 
- Python: Pandas, Numpy, Seaborn, and Ruptures. 

**Findings:**
- There is a identifiable decline period in Kickstarter's success rate fluctuation. The mentioned decline period correlates to the rise of "expensive" campaigns that have excessive goal. The "expensive" campaign rise is link to the rise of technology campaign that is known to have excessive goal to cover its developing cost. 

### Bundling itch.io Popular Products with K-means Clustering

**Code**: [Bundling itch.io Popular Products with K-means Clustering](https://github.com/AldoGadra/Data_analysis_portfolio/blob/main/Itch.io%20Catalog%20Clustering/Kaggle_Itch.io.ipynb)

**Article**: [Bundling itch.io Popular Products with K-means Clustering ](https://medium.com/@aldgadra/bundling-itch-io-popular-products-with-k-means-clustering-2f57264ba907)

**Description**: 
Itch.io is a widely popular online marketplace that specializes in independent video and tabletop games. The indie specialization brings up a unique, diverse catalog for the itch.io marketplace. But due to their uniqueness, itch.io's product catalog can be hard to categorize for further market research needs. This project aims to categorize itch.io listings through clustering in order to gain insights on product categories and their market performance.

**Original Dataset**: [Itch.io Popular Pages](https://www.kaggle.com/datasets/sanjivydorian/itch-io-pages-datset)

**Skills**: Data cleaning, data wrangling, data visualization, PCA (Principle Component Analysis), and Clustering (Kmeans & DBScan). 

**Tools**: 
- Python: Pandas, Numpy, Seaborn, and Sklearn. 

**Findings:**
- There are 4 types of products on itch io: Top market performance group (Mostly visual novel games), average market performing products, alternative genre (strategy and action games), and expensive products.

### Perth GWR House price and School Proximity
Article: [https://medium.com/p/f5dc575005f9](https://medium.com/@aldgadra/does-school-distance-influence-house-price-b9c0c0cb06e4)

**Description**: Homeowners often bought houses as a means to invest more on their future life, including on their children education. But how much are homeowners are willing to pay to live near a good school? This projects aims to test wether if high quality schools correlate with increased house price. I tested this OLS and GWR to capture the relationship spatial non-stationary effect. 

**Original Dataset**: [https://www.kaggle.com/datasets/ulrikthygepedersen/kickstarter-projects](https://www.kaggle.com/datasets/syuzai/perth-house-prices/data)

**Skills**: Data cleaning, data wrangling, data visualization, regression subset method,  OLS, and GWR.

**Tools**: 
- R: GWModel, GGplot, dplyr, tidyr, lmtest, olsrr, leaps.  

**Findings**:
- High quality schools have a significant positive relationship with nearby house price. This relationship have spatial non-stationary. But the aforementioned effect can still be explained under global assumption using OLS. 

### Kickstarter Success Rate Analysis

**Code**: [Data_analysis_portfolio/bali_sport_seasonal_trend](https://github.com/AldoGadra/Data_analysis_portfolio/tree/main/bali_sport_seasonal_trend)

**Description**: 
Bali is the top tourism destination in Indonesia. Bali's Ngurah Rai International Airports accommodate 38.7% of Indonesia's international visitor arrivals in 2019 and has risen to 45.4% in 2024. The foreign visitors, combined with continuing tourism development, have introduce new lifestyle changes in Bali regarding diets, wellness, culture, and fitness. 

If we use the Google Trends' data on the "gym" search term as a proxy for fitness, we can see that there is an increasing trend of fitness popularity from 2010 to 2024.  

This brings up an interesting question: "How is the development of fitness activities' popularity in Bali?"

**Data Source**: Google Trends

**Skills**: Data cleaning, data wrangling, data visualization, and STL.

**Tools**: 

R: dplyr, tidyr, reader, Kendall, and forecast. 

**Findings**:

Most of the wellness activities follow the tourism seasonal pattern, which may be caused by most of the activities being popular tourism activities. But interestingly, only gym and yoga that are found to keep rising in popularity while others are either declining or moving stagnantly. 
