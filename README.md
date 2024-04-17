Project Background:
* This project involves in analyzing the characteristics of different automobiles vehicles with a focus on factors like engine power, top speed, fuel efficiency and weight.​
* To Investigate the relationship between engine horsepower, vehicle weight, and top speed to understand how these factors affect the performance of vehicles.​

Goal:
* Industry Innovation and Competition: The automotive industry is highly competitive, with manufacturers constantly striving to innovate and differentiate their products. Understanding the relationships between vehicle characteristics such as weight, power, and efficiency can provide valuable insights for manufacturers seeking to design and market competitive vehicles.​
* Rising Environmental Concerns: With increasing awareness about environmental issues such as climate change and air pollution, there is a growing emphasis on developing vehicles that are more fuel-efficient and emit fewer greenhouse gases.  This project aims to analyze key attributes of vehicles to understand their environmental impact and identify opportunities for improvement.​

Benefits:
* Empower consumers to make informed purchasing decisions based on vehicle performance and efficiency.​
* Position manufacturers strategically in the automotive market by meeting consumer demands and staying ahead of industry trends.​
* Optimize vehicle design and engineering for better performance and customer satisfaction.​

EDA:
* Our exploratory data analysis (EDA) revealed a clear linear relationship between miles per gallon (MPG) and both horsepower (HP) and speed[SP], indicating that higher horsepower and speed correspond to improved fuel efficiency.​
* Surprisingly, our analysis indicates that vehicle weight and volume exert a modest influence on MPG, suggesting that there may be other dominant factors driving fuel efficiency. This suggests that while weight and volume do impact MPG to some extent, their effects are overshadowed by other variables.​
* These insights underscore the importance of focusing on engine power and speed optimization to enhance fuel efficiency in vehicles, while also highlighting the potential for further investigation into the nuanced factors influencing MPG.​

Diagnosis analysis:
The boxplot reveals potential outliers in HP, VOL, SP, and WT data groups.​
* HP Group: This group appears to have the most outliers, suggesting data points that fall significantly outside the typical range for this group.​
* VOL, SP, and WT Groups: While these groups also have outliers, they seem to be present to a lesser extent compared to HP.​

Model Comparision:
* KNN Regressor: Based on the R-squared score, the KNN Regressor appears to be the best performing algorithm in this case. It has an R-squared score of 0.7539, which indicates that it explains 75.39% of the variance in the target variable. It also has the lowest RMSE (0.4799), which signifies a good fit to the data.​

* Gradient Boosting, Random Forest, and XGBoost: These three algorithms also delivered good performance with R-squared scores above 0.73 and RMSE values below 0.5. They are all ensemble methods that combine the predictions of multiple decision trees, which can lead to robust and accurate models.​

Conclusion:
* Our analysis, along with the performance of the KNN model Regression, provides valuable insights into car fuel efficiency.​

* Engine Power and Speed: The analysis revealed a surprisingly strong positive correlation between MPG and both horsepower (HP) and speed (SP). This suggests that advancements in engine technology and aerodynamic design may be leading to improved fuel efficiency despite higher power output.​

* Weight and Volume: While weight (WT) and volume (VOL) do have some influence on MPG, their impact appears less significant compared to HP and SP. This highlights the potential for car manufacturers to focus on optimizing engine performance and aerodynamics for better fuel economy without necessarily compromising vehicle size.​

​
