# Module_5_challenge_Mouse_Study<p>
<p><b>Module_5 assignment for data visualisation in pandas dataframe - method and sources</b></p>
<p>This is a fictional dataset of a clinical drugs study using mice as test subjects. We are asked to produce a clean dataframe and undertake a statistical analysis of the results</p>
<p>There are two source csv files which have been retrieved by the source code and put into dataframes. I have printed off a preview of both dataframes to workout how best to merge them.</p>
<p>Used a left merge with the "test results: data frame being the left table and the metadata for the mice being the right table.
<p>Using the duplicated function to find the doubled g898 records.
<p><b>Sources</b><ul><li>
https://stackoverflow.com/questions/46640945/grouping-by-multiple-columns-to-find-duplicate-rows-pandas</li>
<li>I did reach out to Andrew Fellows, another student on the course, when I was unable to use the drop_duplicates function to clean the data to drop the records got mouse g989. He suggested using .loc function. His solution is different to mine, but he dug me out of the trench.</li>
<li>https://pbpython.com/groupby-agg.html - using groupby and aggregation methods in a variety of scenarios. I used this to ensure syntax correct.</li>
<li>Issue with creating regression analysis - needed lineregress from scipy.stats. to do tis i had to import this from scipy.stats (i.e. scipy.stats import linregress). This was done after reading the following on stackoverflow https://stackoverflow.com/questions/59284296/nameerror-global-name-linregress-is-not-defined.</li>
formatting boxplot<li>https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.boxplot.html</li>
I also used stackoverflow to learn how to format the output for the interquartile range, as the standard python formatting causes an error when using scipy.  
