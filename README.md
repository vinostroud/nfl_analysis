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

