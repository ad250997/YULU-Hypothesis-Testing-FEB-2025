<!DOCTYPE html>
<html>
<body>
    <h1>Yulu Bike Rentals: Statistical Analysis of Demand Drivers</h1>
  
  <h2>Overview</h2>
  <p>This case study analyzes Yulu’s bike-sharing data to identify factors influencing rental demand. Using hypothesis testing and statistical methods, the analysis evaluates the impact of weather, seasons, and weekdays vs. weekends on bike rentals. The dataset includes 10,886 hourly records with features like temperature, humidity, and user type (casual/registered).</p>

  <h2>Key Objectives</h2>
  <ul>
      <li>Assess whether bike rentals differ significantly between weekdays and weekends.</li>
      <li>Determine the impact of weather conditions and seasons on rental demand.</li>
      <li>Provide data-driven recommendations for operational optimization.</li>
  </ul>

  <h2>Methodology</h2>
  <ul>
      <li>Performed outlier handling using the IQR method to clean the dataset.</li>
      <li>Conducted <strong>t-tests</strong> (for weekday vs. weekend demand) and <strong>ANOVA</strong> (for weather/season comparisons).</li>
      <li>Used chi-square tests to analyze relationships between weather conditions and seasons.</li>
      <li>Visualized trends with histograms, boxplots, and correlation heatmaps.</li>
  </ul>

  <h2>Key Insights</h2>
  <ul>
      <li><strong>Weather Impact:</strong> Significant demand drop in poor weather (p-value ≈ 8e-44), with clear conditions driving 68% of rentals.</li>
      <li><strong>Seasonality:</strong> Rentals vary significantly across seasons (p-value ≈ 7.8e-153), with summer and fall seeing peak demand.</li>
      <li><strong>Weekday vs. Weekend:</strong> No significant difference in demand (p-value = 0.837), indicating consistent usage patterns.</li>
  </ul>

  <h2>Recommendations</h2>
  <ul>
      <li>Implement dynamic pricing during adverse weather to maintain demand.</li>
      <li>Optimize bike fleet distribution in peak seasons (summer/fall).</li>
      <li>Focus marketing efforts on casual users during weekends to boost engagement.</li>
  </ul>
</body>
</html>
