Download Link: https://assignmentchef.com/product/solved-hw2-the-distribution-of-movie-ratings-cs249
<br>
Movie ratings are numeric scores summarizing the quality of a movie. In this assignment, we study two sources of ratings:

<ul>

 <li>up-to-date, recently tweeted movie ratings (from MovieTweetings)</li>

 <li>historical movie rating averages (from IMDb).</li>

</ul>

Ratings from both of these sources are numeric values ranging from 0 to 10.

Perhaps remarkably, the distribution for the two kinds of ratings look the same. The goal of this assignment is to characterize the movie ratings distribution.

<em>You are supposed to produce an output file answering four sets of questions (10 questions in all):</em>

<ol>

 <li><em>characterizing the distribution of live MovieTweetings movie ratings</em></li>

 <li><em>studying the differences between average and median MovieTweetings ratings.</em></li>

 <li><em>characterizing the distribution of archival IMDb movie ratings</em></li>

 <li><em>analyzing skewness of the Gamma distribution.</em></li>

</ol>

The details of these questions are laid out in the notebook. And as it explains, your program should produce a CSV file HW2_output.csv answering the questions. A correct output file could look like this:

lognormal,5.55555,1.11111 skewness,2.22222, kurtosis,3.33333,

Batman: The Dark Knight,3.33333,8.88888

Batman v Superman: Dawn of Justice,9.11111,9.55555 lognormal,5.22222,1.44444 skewness,2.55555, kurtosis,3.44444, 1,,

False,,

This is just an example of the format of an output file; your output file will be different.

This file characterizes the distribution of ratings as a <em>lognormal distribution</em>. This is not correct: the ratings distribution clearly cannot be lognormal, since it is <em>negatively skewed </em>(it leans to the right) whereas the lognormal distribution is <em>positively skewed </em>(it leans to the left).

Another distribution is needed. The notebook suggests some candidate distributions as possibilities, but you job is to identify one, and obtain the best fit (i.e., maximal likelihood parameters) for the data.

The notebook does not give as much guidance as the earlier assignment notebooks. However, this is also a short assignment. To complete this assignment, please upload two files to CCLE:

<ol>

 <li>your output CSV file csv</li>

 <li>your notebook file ipynb (to show your work).</li>

</ol>

The notebook should have the commands you used to produce the output file. All assignment grading in this course will be automated, so please assume that when uploading files.

We will use Paul Eggert’s <strong>Late Policy</strong>: The number of days late is <em>N </em>= 0 for the first 24 hrs, <em>N </em>= 1 for the next 24 hrs, etc., and if you submit an assignment <em>H </em>hours late, 2<sup>b<em>H/</em>24c </sup>points are deducted.


