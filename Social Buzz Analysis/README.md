# Social Buzz Data Analysis Project

Social Buzz, a social media platform emphasizing content over users, has experienced unprecedented growth. The platform focuses on trending content, measured by over 100 user reactions, while maintaining user anonymity. With over 100,000 pieces of unstructured content generated daily, the company faces challenges related to scaling operations, preparing for an IPO, and adopting best practices for managing big data.

---

## 🔍 Analysis Overview  

1. **Data Overview**:
![Data Overview](https://github.com/Yungssu/ExcelAnalysis/blob/main/Social%20Buzz%20Analysis/SocialBuzzERD%20(1).png)
   - This Entity-Relationship Diagram (ERD) represents the data structure for analyzing user reactions on Social Buzz.
      - Content: Stores details about the posts, including the content type, category, and URL.
      - Reactions: Tracks user interactions with content, recording the type of reaction and timestamp.
      - ReactionTypes: Defines reaction types, their sentiment, and associated scores.
   - This design links user reactions to specific content, enabling insights into user preferences and engagement patterns. 

- **Content**: Stores details about the posts, including the content type, category, and URL.  
- **Reactions**: Tracks user interactions with content, recording the type of reaction and timestamp.  
- **ReactionTypes**: Defines reaction types, their sentiment, and associated scores.  

This design links user reactions to specific content, enabling insights into user preferences and engagement patterns.

3. **Key Insights**:
   - Determined the most popular content category by analyzing aggregate user reaction scores.  
   - Ranked the Top 5 content categories based on user engagement metrics.  
   - Identified the month with the highest number of posts, highlighting seasonal posting trends.  

## 📊 Results  

### Total Scores per Category
![Results](https://github.com/Yungssu/ExcelAnalysis/blob/main/Social%20Buzz%20Analysis/SocialBuzzTotalScore.png)
   - The "Animals" category won overall, and gained the most points. The remaining top-performing categories, in order, were "Science," "Healthy Eating," "Technology," and "Food." These are some of the top categories in terms of user engagement and interest, and they present categories of focus for Social Buzz in terms of activity on the platform and growth.

### Top 5 "popular" Category  
![Results](https://github.com/Yungssu/ExcelAnalysis/blob/main/Social%20Buzz%20Analysis/SocialBuzzTop5.png)
   - Among the five leading performance categories, two related directly to food were “Healthy Eating” and “Food.” This also shows a significant user interest in food and nutrition content.
### Total Posts per Month  
![Results](https://github.com/Yungssu/ExcelAnalysis/blob/main/Social%20Buzz%20Analysis/SocialBuzzPostsPerMonth.png)
   - This graph illustrates the monthly posting trends on Social Buzz, showing fluctuations in the number of posts throughout the year. The data reveals peak activity in January, May, and July, with dips in February and October. These trends highlight opportunities for aligning content campaigns with months of increased posting activity.

## 💡 Recommendations

Based on the insights gathered from analyzing Social Buzz's data:

1. **Focus on Top-Performing Categories**  
   - Makes the site categories as listed, the Animals, Science, Healthy Eating, Technology and Food areas, have the highest total popularity for the topics within them.
   - Tailor campaigns and partnerships that align with these niches to maintain and increase user engagement, allowing Social Buzz to hone its advantage in these high-performance areas.

2. **Leverage Food-Related Content**  
   - Social Buzz can partner with food influencers to take engagement to the next level as "Healthy Eating" and "Food" joined the top five categories.
   - Adding subcategories to these niches is creating more potentially desirable content that would appeal to a wide format while retaining its core market, and driving more engagement across food content on the platform.

4. **Seasonal Posting Strategies**  
   - Analyze monthly posting trends to identify peak periods and synchronize major content campaigns with these high-traffic months, maximizing visibility.  
   - Focus on promoting specific categories, such as "Animals" and "Science," during their peak engagement months to optimize user interaction and capitalize on content popularity.

5. **Enhance Data-Driven Decision Making**  
   - Leverage data insights to enhance content recommendation algorithms, ensuring users are served content that aligns with their interests and engagement patterns.  
   - Invest in advanced content curation tools that utilize these insights to prioritize and highlight trending topics, improving user experience and driving sustained engagement on the platform.


## 🛠️ Tools Used  

- **Excel**: Data Cleaning and Pivot Tables  
- **Markdown**: For project documentation  

---

## 🔗 Portfolio Link  
- [Back to My Portfolio](https://github.com/Yungssu/kennethHuyong.github.io)
