# Assignment 3 - Replicating a Classic Experiment

by: Andrew Kerekon, Aviv Nur, Bijesh Shrestha, Yihan Wang

## Description

This research conducts a scientific investigation to discover the best successful data visualization strategies using a controlled experiment. As a scientist performing this study, our objective is to compare four visualization formats utilizing a custom-designed experimental setup. The experiment, which is based on the methodology of Cleveland and McGill (1984) and Heer and Bostock (2010), entails developing support code for experiment management, data/stimuli production, error computation, and results documentation, all of which are carried out using simple JavaScript interfaces. The project's goal, with at least ten participants, is to undertake a complete study of the acquired data to determine which visualization method best helps data comprehension. Furthermore, the study is open to going beyond typical visualization methods, such as investigating alternative approaches to data presentation. This endeavor aims to give empirical evidence to the field of data visualization while also encouraging innovation in visual data representation strategies.

## Hypothesis
1. Participants will make more accurate measurements with the vertical bar chart than the stacked bar chart.
2. Participants will make more accurate measurements with the vertical bar chart than the bubble chart.
3. Participants will make the least accurate measurements with the bubble chart.
4. Participants will make similarly accurate measurements with the bubble chart and the pack circle chart.

## Results



## Technical Achievements
We use D3 objects for the creation of four different graphs, bar chart, stacked chart, bubble and packed circle, where the first two are similar and the last two are similar, making it easier to compare and analyze the data at a later stage.

After that we connect the four tables to Revisit, which contains two parts:

"Cleveand Replication" - It includes authors' names and is described as an "Assignment 3: Replication of Cleaveland - McGill Experiment." There's also a link to view the source, suggesting it might be an open-source project or that the experiment details are accessible for review.

"HTML as a Stimulus" - Authored by the reVISIT Team, this seems to be a simple demonstration of using HTML as a stimulus in an experiment, potentially involving D3 visualizations. D3 is a JavaScript library for producing dynamic, interactive data visualizations in web browsers. There's also a "View source" link for this experiment.

After conducting the survey, the collected data was organized and analyzed, and the data results were visualized in Jupyter.

## Design Achievements



## References

Original study:

Development of support code: development of necessary support code for experimental sequences, results file output, and other experimental components such as JavaScript buttons and forms.

Data/stimulus generation and error calculation: Implemented data generation and error calculation functions based on Cleveland and McGill's 1984 paper and Heer and Bostock's 2010 replication study.

Randomized trial order and data point generation: Ensure that the trial order is randomized and that a random set of data points is generated for each trial, where two data points are flagged for comparison.

Participants: The project requires a minimum of 20 participants or an equivalent number of trials to conduct the experiment.

Testing of multiple visualizations: at least three different visualizations or experimental conditions were tested, and test hypotheses for each visualization were considered.

Analysis and reporting: Perform basic analysis and report results, including calculating the average Log2Error for each visualization type and determining the upper and lower bounds of error using Bootstrapped 95% confidence intervals.

Error Calculation Methodology: Calculate the error using the log-base-2 error equation proposed by Cleveland and McGill, which involves calculating the difference between the true percentage and the reported percentage and scaling that error.
