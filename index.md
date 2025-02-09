---
layout: default
title: Abhishek Malali
---

## About Me

<img class="profile-picture" src="Abhishek.jpg">

I am a Senior Applied Scientist at Amazon AGI and Alexa. 

My research focuses on the application of Large Language Models (LLMs) in conversational AI, API action generation and understanding, parameter-efficient fine-tuning, synthetic data generation, and prompt optimization through self-reflection. As a technical lead, I tackle complex business challenges by employing machine learning-driven approaches and oversee their deployment in production, either through direct involvement or by collaborating with cross-functional engineering teams. During my tenure at Amazon, I have contributed to enhancing speech model personalization, developing context-driven query correction models, and creating cross-functional products aimed at elevating the overall customer experience. Additionally, I have led a small team, providing mentorship and support to optimize team performance and foster professional growth.

Before joining Amazon, I worked as a Data Scientist at Tribe Dynamics (acquired by CreatorIQ), focusing on refining models for classifying social media data for marketing purposes. I hold a Master’s degree in Computational Science and Engineering from Harvard University, where I published a thesis on predicting irregular time series in Astronomy and addressing autocorrelation in residuals through modifications to LSTM architectures. I also earned a Bachelor's degree in Electrical and Electronics Engineering from NITK Surathkal, India, with a research project on epilepsy prediction using Intra-Ictal EEG time series data during my undergraduate studies.

## Publications

1. Abhishek Malali, Ganne Chaitanya, Shashi Gowda and Kaushik Majumdar , 2016, Analysis of cortical rhythms in intracranial EEG by temporal difference operators during epileptic seizures, Biomedical Signal Processing and Control [[Paper]](https://www.sciencedirect.com/science/article/pii/S1746809416000033)


## Open Source Packages
1. TimeFlow, TensorFlow Wrapper for Time Series Modelling [[Github]](https://github.com/abhishekmalali/TimeFlow)
2. TimeSynth, Multipurpose Library for Synthetic Time Series [[Github]](https://github.com/TimeSynth/TimeSynth)

## Research and Academic awards
1. IACS Harvard Scholarship for $25000 (2017)
2. Sponsored by H2O.ai for 2nd year of M.E.(CSE) (2017)
3. Institute Gold Medal at NITK (2014)
4. OP Jindal Engineering and Management Scholarship (Awarded to top 80 students in the country every year) (2010, 2012, 2013)

## Projects
* **Deep Learning for Irregular Time Series Prediction** - The motivation behind the research lies in the lack of research for predicting irregular time series. Irregular time series are common in Astronomy, Banking, IOT etc. This work modifies the LSTM module accept irregularly sampled data and learn from it. The work also involves reducing the autocorrelation within the residuals which is a common problem for time series prediction methods. This is accomplished by deriving the autocorrelation for irregular series though a Continuous time AutoRegressive approximation which is theoretically valid. The autocorrelation term is used as regularization term while training the model to modify the network weights such that the correlation effect within the residuals is minimized while improving the training accuracy. We demonstrate the efficacy of the method on synthetically generated data as well as real world astronomy datasets. Advised by Professor Pavlos Protopapas.[[Code]](https://github.com/abhishekmalali/TimeFlow)

* **What's the best way to ask a question?** - In this project, we contrast two different questioning schemes to assess efficacy in recovering true class labels from noisy labels provided by crowdsourced non-experts, when there are more than two classes to choose from.  The questioning schemes were 1. Display all the classes at the same time instant and ask the user to select one 2. Display each class sequentially and ask the user to answer with a Yes/No. We generate data with a confusion matrix for each expert, and an underlying class distribution, and attempt to recover both parameters and the true labels. We use Expectation Maximization (EM), Simulated Annealing, and PyMC to compare efficiency and verify results. Our results suggest that for cases where we have more than 2 classes, its more efficient to ask the user to classify by displaying each class sequentially. Collaborated with Neil Chainani and Christian Junge.[[Website]](http://abhishekmalali.github.io/questioning-strategy-classification/) [[Code]](https://github.com/abhishekmalali/questioning-strategy-classification)

* **Implementing Machine Learning Models in Spark** - Spark is a burgeoning big data processing framework that is known to offer fast performance and intuitiveness, through its innovative use of distributed data structures known as RDDs. On top of Spark sits a library called MLLib hosts a wide variety of machine learning algorithms that can be run parallely on the RDDs. In this project, we chose to tackle two machine learning methods to write: random forests, and ordinal regression. Random forests currently exists within Spark's MLLib, but we wanted to see if we could write an implementation that would surpass the performance of MLLib's version. Ordinal regression, however, does not exist in MLLib. We took it upon ourselves to write both of these algorithms in Spark by leveraging its parallel functionality. Collaborated with Neil Chainani and Leonhard Spiegelberg. [[Website]](http://abhishekmalali.github.io/spark-ml/) [[Code]](https://github.com/abhishekmalali/spark-ml)

* **NBA Player friendly scheduler** - We attempt our take at solving the NBA schedule problem such that a team does not have to play 4 games in 5 days in the league and other scheduling constraints. The problem is solved as a constraint satisfaction problem where constraints are the league game requirements. Another take at solution involves solving the schedule as a Integer linear programming problem. We generated a player friendly schedule which ensures their are no back to back away games and keeps player workload to a minimum within a week. Collaborated with Charles Liu and Sam Daulton.[[Code]](https://github.com/therealchuckliu/NBA_Scheduler)

* **Quantitative Evaluation of Player Performance** - We analyze and study transfer market in international football and perceive the valuation of players to be driven by subjective measures of what team the play for, what nationality they are and the league their club belongs to. In this project we attempt to define a quantitative metric, based on the impact a player has on each match they appear in, by which we evaluate a player's value using open data from www.worldfootball.net. In addition to this, we use the transfer data available on wikipedia to better understand pricing. Collaborated with Taylor Killian and Virgil Audi.[[Website]](http://cs109-fifa.github.io) [[Code]](https://github.com/cs109-FIFA/cs109-FIFA)

* **Seizure detection using differential operators and time frequency analysis** - The research was done as a part of my Undergraduate thesis requirement. We created a robust algorithm based on temporal features generated by differential operators to predict seizures within seconds of the onset. The algorithm was tested on the Freiburg EEG epilepsy dataset. Collaborated with Ganne Chaitanya and Shashi Gowda. Advised by Kaushik Majumdar.

## References

* Pavlos Protopapas, Scientific Director, Institute of Advanced Computational Sciences, Harvard University
* Kaushik Majumdar, Associate professor, Indian Statistical Institute, Bangalore
* Jora Gonda, Associate Professor, National Institute of Technology - Karnataka, Surathkal

This is a jekyll based resume template. You can find the full source code on [GitHub](https://github.com/bk2dcradle/researcher)
