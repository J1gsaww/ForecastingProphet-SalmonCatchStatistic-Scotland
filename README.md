<h1>Salmon Catching Data Analysis</h1>
<p>This project analyzes salmon catching data to gain insights and make predictions.</p>

<h2 id="introduction">Introduction</h2>
<p>This section provides an overview of the project and its objectives.</p>

<h2 id="data-exploration">Data Exploration</h2>
<p>Exploratory data analysis was conducted to understand the structure and characteristics of the data.</p>

<h2 id="data-cleaning">Data Cleaning</h2>
<p>The data was cleaned and prepared for analysis, including handling missing values and outliers.</p>

<h3>Amount of Each Type of Fish Caught in Each Year</h3>
<img src="images/fish_by_year.jpg" alt="Amount of Each Type of Fish Caught in Each Year">
<h4>Trend Analysis</h4>
<p> - There is a noticeable decline in the amount of fish caught across all types from the peak in the mid-1990s to 2020. </p>
<p> - Wild_1SW and Wild_MSW have the most significant declines, while Finnock and Sea_trout also show a reduction. </p>
<h4>Key Observations</h4>
<p> - The decline in all types of fish suggests a broader ecological issue affecting all fish populations. </p>
<p> - Potential reasons could include overfishing, climate change, pollution, and changes in water quality or habitat.</p>

<h3>Proportion by Fishing Method</h3>
<img src="images/method_proportion.jpg" alt="Proportion by Fishing Method">
<h4>Trend Analysis</h4>
<p> - Net and Coble: Retained method is the most predominant, accounting for 53.7% of the catches. </p>
<p> - Fixed Engine: Retained method follows, making up 46.3% of the catches. </p>
<p> - Released methods (Net and Coble, Fixed Engine) are negligible, indicating low release rates.</p>
<h4>Key Observations</h4>
<p> - The dominance of retained methods suggests that catch-and-release practices are not widely adopted or enforced. </p>
<p> - This could contribute to the declining fish populations observed in other graphs.</p>

<h3>Sum of All Fish Caught by District and Year</h3>
<img src="images/sum_fish_district.jpg" alt="Sum of All Fish Caught by District and Year">
<h4>Trend Analysis</h4>
<p> - A lot of fluctuations can be observed, especially in the early 2000s, with some districts showing peaks and troughs in fish catches. </p>
<p> - The districts with the highest catches (e.g., Tweed, Conon) have seen substantial declines since their peaks in the mid-2000s.</p>
<h4>Key Observations</h4>
<p> - The variability in fish catches over the years suggests environmental factors, policy changes, or variations in fishing practices. </p>
<p> - The overall trend for many districts is a decline, which could indicate overfishing, habitat loss, or other ecological issues.</p>

<h3>Sum of All Fish Caught by District between 2020 - 2022</h3>
<img src="images/sum_fish_district_2020-2022.jpg" alt="Sum of All Fish Caught by District and Year">
<h4>Trend Analysis</h4>
<p> - The Tweed district consistently shows the highest number of fish caught, peaking around 1200 in 2022 despite a slight decline in 2021. </p>
<p> - The North Esk district also shows a notable increase over the years, starting below 200 in 2020 and reaching close to 800 in 2022. </p>
<p> - Most other districts show relatively stable or slight increases in fish catches over the three years.</p>
<h4>Key Observations</h4>
<p> - Tweed and North Esk are the standout districts with significant increases. </p>
<p> - Districts like Annan and Nith show minor changes, indicating stable fish populations or consistent fishing practices.</p>

<h3>Example of Forecasting using Prophet (Wild MSW Catch)</h3>
<img src="images/Wild MSW Forecast.png" alt="Wild MSW Forecast">
<h4>Trend Analysis</h4>
<p> - The forecast shows a continuous decline in the Wild MSW fish population from the 1950s to 2025. </p>
<p> - The forecasted numbers drop below zero, indicating a severe decline if current trends continue.</p>
<h4>Key Observations</h4>
<p> - The declining trend is alarming and suggests that without intervention, Wild MSW populations could become critically low or extinct. </p>
<p> - This highlights the need for sustainable fishing practices, conservation efforts, and policies to protect fish populations.</p>



<h2 id="model-building">Model Building</h2>
<p>Various predictive models were built and evaluated to forecast future trends in salmon catching.</p>

<h2 id="conclusion">Conclusion</h2>
<p>This project provides a comprehensive analysis of salmon catching data and demonstrates various data science techniques, from data cleaning to model building.</p>
<h2>Data</h2>
<p>The dataset used for this analysis contains information about salmon catching incidents, including various features that can be used for predictive modeling.</p>
<h2>Usage</h2>
<p>To run the notebook and replicate the analysis, you need to have Jupyter Notebook installed. Load the notebook and run each cell sequentially.</p>
<h2>Requirements</h2>
<p>The following Python libraries are required:</p>
<ul>
<li>pandas</li>
<li>numpy</li>
<li>matplotlib</li>
<li>seaborn</li>
<li>scikit-learn</li>
</ul>
<h2>Conclusion</h2>
<p>This project provides a comprehensive analysis of salmon catching data and demonstrates various data science techniques, from data cleaning to model building.</p>
