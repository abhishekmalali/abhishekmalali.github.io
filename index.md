---
layout: default
---

## Abhishek Malali

<img class="profile-picture" src="sherlock.jpg">

I am currently a Data Scientist at Tribe Dynamics. My role focuses on finding data driven stories in the realm of Social media marketing. I also lead efforts at the Tribe to integrate NLP and Image processing for classification tasks which bring more value to our customers.

Prior to my current stint at Tribe, I was a Masters student in Computational Science and Engineering at Harvard University. My master’s thesis applies LSTM backed models to learn and predict on irregular time series in Astronomy and reduces autocorrelation within residuals generated from predictions. I graduated with a Bachelors in Electrical and Electronics Engineering from NITK Surathkal, India and submitted a thesis for epilepsy prediction with Intra-Ictal EEG time series data.

## Research Interest

I am primarily interested in applying Machine learning techniques in a robust and scalable manner to a variety of problems. My previous research experiences have spanned from applying classical time series methods to deep learning to problems in vastly different domains. I am particularly interested in image and time series problems which are applied to noisy real world data. I am interested in understanding the effect of noise and the complications brought forward by such datasets. Previously I have handled noisy datasets in astronomy and medical research.

## Publications

1. Abhishek Malali, Ganne Chaitanya, Shashi Gowda and Kaushik Majumdar , 2016, Analysis of cortical rhythms in intracranial EEG by temporal difference operators during epileptic seizures, Biomedical Signal Processing and Control [[Paper]](https://www.sciencedirect.com/science/article/pii/S1746809416000033)

## Research and Academic awards
1. IACS Harvard Scholarship for $25000 (2017)
2. Sponsored by H2O.ai for 2nd year of M.E.(CSE) (2017)
3. Institute Gold Medal at NITK (2014)
4. OP Jindal Engineering and Management Scholarship (Awarded to top 80 students in the country every year) (2010, 2012, 2013)

## Projects
* **Deep Learning for Irregular Time Series Prediction** - The motivation behind the research lies in the lack of research for predicting irregular time series. Irregular time series are common in Astronomy, Banking, IOT etc. This work modifies the LSTM module accept irregularly sampled data and learn from it. The work also involves reducing the autocorrelation within the residuals which is a common problem for time series prediction methods. This is accomplished by deriving the autocorrelation for irregular series though a Continuous time AutoRegressive approximation which is theoretically valid. The autocorrelation term is used as regularization term while training the model to modify the network weights such that the correlation effect within the residuals is minimized while improving the training accuracy. We demonstrate the efficacy of the method on synthetically generated data as well as real world astronomy datasets. Advised by Professor Pavlos Protopapas.[[Code]](https://github.com/abhishekmalali/TimeFlow)

* **What's the best way to ask a question?** - In this project, we contrast two different questioning schemes to assess efficacy in recovering true class labels from noisy labels provided by crowdsourced non-experts, when there are more than two classes to choose from.  The questioning schemes were 1. Display all the classes at the same time instant and ask the user to select one 2. Display each class sequentially and ask the user to answer with a Yes/No. We generate data with a confusion matrix for each expert, and an underlying class distribution, and attempt to recover both parameters and the true labels. We use Expectation Maximization (EM), Simulated Annealing, and PyMC to compare efficiency and verify results. Our results suggest that for cases where we have more than 2 classes, its more efficient to ask the user to classify by displaying each class sequentially. Collaborated with Neil Chainani and Christian Junge.[[Website]](http://abhishekmalali.github.io/questioning-strategy-classification/) [[Code]](https://github.com/abhishekmalali/questioning-strategy-classification)

* **Implementing Machine Learning Models in Spark** - Spark is a burgeoning big data processing framework that is known to offer fast performance and intuitiveness, through its innovative use of distributed dats structures known as RDDs. On top of Spark sits a library called MLib hosts a wide variety of machine learning algorithms that can be run parallelly on the RDDs. In this project, we chose to tackle two machine learning methods to write: random forests, and ordinal regression. Random forests currently exists within Spark's MLib, but we wanted to see if we could write an implementation that would surpass the performance of MLib's version. Ordinal regression, however, does not exist in MLib. We took it upon ourselves to write both of these algorithms in Spark by leveraging its parallel functionality. Collaborated with Neil Chainini and Leonhard Spiegelberg. [[Website]](http://abhishekmalali.github.io/spark-ml/) [[Code]](https://github.com/abhishekmalali/spark-ml)

* **NBA Player friendly scheduler** - We attempt our take at solving the NBA schedule problem such that a team does not have to play 4 games in 5 days in the league and other scheduling constraints. The problem is solved as a constraint satisfaction problem where constraints are the league game requirements. Another take at solution involves solving the schedule as a Integer linear programming problem. We generated a player friendly schedule which ensures their are no back to back away games and keeps player workload to a minimum within a week. Collaborated with Charles Liu and Sam Daulton.[[Code]](https://github.com/therealchuckliu/NBA_Scheduler)

* **Quantitative Evaluation of Player Performance** - We analyze and study transfer market in international football and perceive the valuation of players to be driven by subjective measures of what team the play for, what nationality they are and the league their club belongs to. In this project we attempt to define a quantitative metric, based on the impact a player has on each match they appear in, by which we evaluate a player's value using open data from www.worldfootball.net. In addition to this, we use the transfer data available on wikipedia to better understand pricing. Collaborated with Taylor Killian and Virgil Audi.[[Website]](http://cs109-fifa.github.io) [[Code]](https://github.com/cs109-FIFA/cs109-FIFA)

* **Seizure detection using differential operators and time frequency analysis** - The research was done as a part of my Undergraduate thesis requirement. We created a robust algorithm based on temporal features generated by differential operators to predict seizures within seconds of the onset. The algorithm was tested on the Freiburg EEG epilepsy dataset. Collaborated with Ganne Chaitanya and Shashi Gowda. Advised by Kaushik Majumdar.

## References

* Pavlos Protopapas, Scientific Director, Institute of Advanced Computational Sciences, Harvard University
* Kaushik Majumdar, Associate professor, Indian Statistical Institute, Bangalore
* Jora Gonda, Associate Professor, National Institute of Technology - Karnataka, Surathkal

This is a jekyll based resume template. You can find the full source code on [GitHub](https://github.com/bk2dcradle/researcher)
