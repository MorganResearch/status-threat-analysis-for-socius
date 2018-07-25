The files distributed are a full set of analysis files, written after Mutz's article was published and completed at the time a preprint was posted to SocArxiv.  

Set the Stata working directory to the folder where this distribution has been unzipped.

For a streamlined version of the analysis, run these two do files in this order:

1.  mk-mutz-panel-merged-releases.do
2.  critic-analysis-essential-subset-of-code.do

These two files will produce the essential results.  The first will recreate a merged data file from the data files released by Mutz, replacing the one distributed already in the data folder.  The second will report results in log files with the same title (in the log folder and replacing those that are already present in the distribution).

For a complete version of all of the analysis conducted, mostly in the order it was conducted, the following do files can be run (after installing the outreg2 command with "ssc install outreg2"). Run in this order:

1.  mk-mutz-panel-merged-releases.do
2.  mutz-code-panel-edited-v1.do
3.  mutz-code-panel-edited-v2.do
4.  mutz-code-cross-edited-v1.do	
5.  mutz-code-cross-edited-v2.do

In comparison to the essential subset of code above, additional results are generated, and in a different order.  Most regression models of the critic are written out to Excel files in the docs folder.
