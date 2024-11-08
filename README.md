java c
ECO375 Fall 2024, Empirical Project 
Research question: What was the agglomeration elasticity in the US in 2000? The agglomeration elasticity is a concept from urban economics: the elasticity of productivity with respect to population density. In this case, we will represent productivity with the average hourly wage (in 2022 USD).
Therefore, you will estimate the relationship between the log average hourly wage (lw) and the log population density (lpd).
Dataset: You are given data on 381 US cities from the 2000 Census. In addition to the two variables of interest (lw and lpd), it contains information on the demographics, education, labour market, and housing market of these cities. In designing a regression model to estimate the causal relationship of density on wages, you must carefully consider the nature of endogeneityin this context in order to motivate your choice of control variables. You can’t just include all possible controls. You can succeed  in this assignment by using OLS only, but well-argued uses of IV will be rewarded. All data is from the 2000 Census, except for 1900 population.
Requirements (also see rubric at end of document):
1) Due by DEADLINE, 11:59pm. You must use Stata for your analysis. Upload to Quercus your report, the reproducible code (in a .do file) and a log file containing the output from running your program.
Your report has to be in pdf format (save as pdf in word).
2) Your paper should contain all sections listed in the rubric.
3) Be sure not to directly includ代 写ECO375 Fall 2024, Empirical Project
代做程序编程语言e Stata output in your report. Use figures, equations, and tables to summarize your results.
4) Submit the Stata code (with comments) and a log file containing your estimation results, together with the report to Quercus. Make sure that your results can be replicated by running your code on a  different computer.
NOTE: this data is shared with permission from IPUMS. Please do not distribute it to others, and see the further note at the end of this document.
To get started, run the following commands to load the data, and confirm that your output matches the output attached.
* assuming you have navigated to the correct directory in the Stata console
use eco375asgt, clear
desc, f
summarize
reg lw lpd

Note on data:
Citation for 2000 census data:
Steven Ruggles, Sarah Flood, Matthew Sobek, Daniel Backman, Annie Chen, Grace Cooper, Stephanie Richards, Renae Rodgers, and Megan Schouweiler. IPUMS USA: Version 15.0 [dataset]. Minneapolis,
MN: IPUMS, 2024. https://doi.org/10.18128/D010.V15.0 
Citation for 1900 census data:
Steven Manson, Jonathan Schroeder, David Van Riper, Katherine Knowles, Tracy Kugler, Finn
Roberts, and Steven Ruggles. IPUMS National Historical Geographic Information System: Version 18.0 [dataset]. Minneapolis, MN: IPUMS. 2023. http://doi.org/10.18128/D050.V18.0 
If you are interested in using US Census data outside of this course, you can download it from usa.ipums.org and nhgis.ipums.org.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
