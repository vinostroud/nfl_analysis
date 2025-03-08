# nfl_analysis

This repository is a series of files working with data from nflfast R (https://www.nflfastr.com/). All code is in python, using the nfl_data_py https://github.com/nflverse/nfl_data_py.

Some notes on individual files.

```
nfl_py_datacleaning
```
This is a standalone block of code that helps clean data so that it's easier and more accurate to work with. For example, it removes null values and equates the play with intended play (ie, a scramble is treated as a pass play). The files are all heavily commented so it's easy to see what's happening and make your own choices if you haven't used the dataset before.

```
qb_passer_rtg_halves
```
Shows change in QB EPA and Passer rating between ranges of weeks within the 2024 season. It can be easily modified from a time series perspective.

```
2024_nfl_data_sandbox
```
Plots Offensive EPA vs Pts Scored in the 2024 season. It shows you how to use team logos.

```
Pitt_Russ_threedown.ipynb
```
Shows Pittsburgh Steelers 1st and 2nd down EPA vs 3rd Down

Also shows Russel Wilson CPOE and QB EPA for 1st and 2nd down vs 3rd Down


```
Jared_Goff.ipynb
```
Looks at Jared Goff's career. Plots CPOE and QB_EPA in three ways-- line plot, 3D scatter plot, and surface plot. 

This would have benefitted from a Dual Axis Time Series Chart.

```
points v. defstats.ipynb
```
Builds a model using XGBOOST to see if defensive stats are a predictor of score (not great!)

```
off_stats_v_points
```
Compares points scored to offensive stats. Also use XGBOOST. As of 8 March 2025, this needs a lot of work. The _rush_epa is not set up correctly and the model metrics are abomidable. 
