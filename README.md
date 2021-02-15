# :flying_saucer:Application-of-Benford-s-Law
:globe_with_meridians:*Course of probabilities and statistics*

Benford's law, also called the Newcomb–Benford law, the law of anomalous numbers, or the first-digit law, is an observation about the frequency distribution of leading digits in many real-life sets of numerical data. The law states that in many naturally occurring collections of numbers, the leading digit is likely to be small. In sets that obey the law, the number 1 appears as the leading significant digit about 30% of the time, while 9 appears as the leading significant digit less than 5% of the time. If the digits were distributed uniformly, they would each occur about 11.1% of the time. Benford's law also makes predictions about the distribution of second digits, third digits, digit combinations, and so on.

## Data samples

<p>To illustrate the applicability of Benford's Law, our application aims to analyze two data sets, one on which the law applies and one on which it does not.
The first set represents the data analysis of the Youtube application for Canada in 2019. We chose this data set, because both the number of views and the number of appreciations or comments respect the conditions of Benford's Law: to be randomly generated numbers, prone to exponential growth, unrestricted by maximum or minimum, and the calculations should take place on large samples of data. Thus, through the interface, the user can choose for which category of data he wants to see the applicability of the law (assessments, views or comments). </p>
<p>The second set of information is the analysis of the sales of a supermarket company in Myanmar that recorded for 3 months, data from each city in the country. Thus, we noticed according to the graphs in the picture below, the fact that Benford's Law is not applicable to numbers that are limited by a range (the rating takes values from 1 to 9, and people tend to give better grades, so the larger numbers will be the predominant ones), the quantity that does not increase exponentially (small reference scale) and the IDs that are unique (automatically the distribution of the first digit tends to be equal).</p>

### :eyeglasses:Download CSV files here: 
<p>https://www.kaggle.com/datasnaek/youtube-new?select=CAvideos.csv </p>
<p>https://www.kaggle.com/aungpyaeap/supermarket-sales </p>
<img src="https://github.com/DimaOanaTeodora/Application-of-Benford-s-Law/blob/main/vizualizari.png" width="600" height="300"/>
<img src="https://github.com/DimaOanaTeodora/Application-of-Benford-s-Law/blob/main/neoficiale.png" width="600" height="300"/>
<img src="https://github.com/DimaOanaTeodora/Application-of-Benford-s-Law/blob/main/tabel.png" width="600" height="300"/>

