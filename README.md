# Project Overview
In this project, you will investigate a classic phenomenon from experimental psychology called the Stroop Effect. You will learn a little bit about the experiment, create a hypothesis regarding the outcome of the task, then go through the task yourself. You will then look at some data collected from others who have performed the same task and will compute some statistics describing the results. Finally, you will interpret your results in terms of your hypotheses.

# Project Details
Statistics: The Science of Decisions Project Instructions
In a Stroop task, participants are presented with a list of words, with each word displayed in a color of ink. The participant’s task is to say out loud the color of the ink in which the word is printed. The task has two conditions: a congruent words condition, and an incongruent words condition. In the congruent words condition, the words being displayed are color words whose names match the colors in which they are printed: for example RED, BLUE. In the incongruent words condition, the words displayed are color words whose names do not match the colors in which they are printed: for example PURPLE, ORANGE. In each case, we measure the time it takes to name the ink colors in equally-sized lists. Each participant will go through and record a time from each condition.
Questions For Investigation
As a general note, be sure to keep a record of any resources that you use or refer to in the creation of your project. You will need to report your sources as part of the project submission.
1. What is our independent variable? What is our dependent variable?
2. What is an appropriate set of hypotheses for this task? What kind of statistical test do you expect to perform? Justify your choices.
Now it’s your chance to try out the Stroop task for yourself. Go to this link, which has a Java-based applet for performing the Stroop task. Record the times that you received on the task (you do not need to submit your times to the site.) Now, download this dataset which contains results from a number of participants in the task. Each row of the dataset contains the performance for one participant, with the first number their results on the congruent task and the second number their performance on the incongruent task.
3. Report some descriptive statistics regarding this dataset. Include at least one measure of central tendency and at least one measure of variability.
4. Provide one or two visualizations that show the distribution of the sample data. Write one or two sentences noting what you observe about the plot or plots.
5. Now, perform the statistical test and report your results. What is your confidence level and your critical statistic value? Do you reject the null hypothesis or fail to reject it? Come to a conclusion in terms of the experiment task. Did the results match up with your expectations?
6. Optional: What do you think is responsible for the effects observed? Can you think of an alternative or similar task that would result in a similar effect? Some research about the problem will be helpful for thinking about these two questions!

# Corrections
####Q2a: Null and alternative hypotheses are clearly stated in words and mathematically. Symbols in the mathematical statement are defined.
As mentioned in the previous reviews, please consider to refer to the population means explicitly in your report:

The idea of hypothesis testing and statistical inference is that we have limited data, samples(generally denoted by X), and from that limited data, we are trying to infer something about the population (generally denoted by U) we don't know about.
With our test we are trying to assess whether the sample means are different because the two populations and population means are different or just by chance.
Therefore our hypothesis should be concerned with μC and μI, respectively the congruent and incongruent population response time means.

####Q2b: A statistical test is proposed which will distinguish the proposed hypotheses. Any assumptions made by the statistical test are addressed.
Please look at here for a more detailed assumptions for conducting t-test.
The t-test for dependent means is considered typically "robust" for violations of normal distribution.This means that the assumption can be violated without serious error being introduced into the test in most circumstance.
However, if we are conducting a one-tailed test and the data are highly skewed, this will cause a lot of error to be introduced into our calculation of difference scores which will bias the results of the test. In this circumstance, a nonparametric test should be used.

####Q5: A statistical test has been correctly performed and reported, including test statistic, p-value, and test result. The test results are interpreted in terms of the experimental task performed.
You may aware that in SciPy package, we have been provided with the method to conduct the dependent t-test directly, please refer to here for more information.
