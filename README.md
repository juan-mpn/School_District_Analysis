# School_District_Analysis Challenge
UCB Data Analytics - Anaconda - Pandas and Python
# Questions and Data Analysis
# After removing the reading and math scores, answer the following questions:
# How is the district summary affected?
## R: Very minimal impact to the school district one point reduction overall
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	        15	  39,170	      $24,649,428.00	  79.0	            81.9	                  75	            86	              80

Prior to removing Thomas HS
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	        15	  39,170	      $24,649,428.00	  78.9	            81.9	                  74            	85	              79

# How is the school summary affected?
## R: Summary records are impacted very little


# Sort and show top five schools.
Thomas HS is no longer in top, now shows in bottom:
##Top 5:
School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Cabrera High School	Charter	1858	$1,081,356.00	$582.00	83.061895	83.975780	94.133477	97.039828	95.586652
Pena High School	Charter	962	$585,858.00	$609.00	83.839917	84.044699	94.594595	95.945946	95.270270
Griffin High School	Charter	1468	$917,500.00	$625.00	83.351499	83.816757	93.392371	97.138965	95.265668
Wilson High School	Charter	2283	$1,319,574.00	$578.00	83.274201	83.989488	93.867718	96.539641	95.203679
Wright High School	Charter	1800	$1,049,400.00	$583.00	83.682222	83.955000	93.333333	96.611111	94.972222

## Bottom 5
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
**Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	66.911315	69.663609	68.287462**
Rodriguez High School	District	3999	$2,547,363.00	$637.00	76.842711	80.744686	66.366592	80.220055	73.293323
Figueroa High School	District	2949	$1,884,411.00	$639.00	76.711767	81.158020	65.988471	80.739234	73.363852
Huang High School	District	2917	$1,910,635.00	$655.00	76.629414	81.182722	65.683922	81.316421	73.500171
Johnson High School	District	4761	$3,094,650.00	$650.00	77.072464	80.966394	66.057551	81.222432	73.639992

# How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
## R: It is impacting severely Thomas High School as this is dropping to 5 bottom, allowing another school to come ton top with similar grades 


# How does removing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type?  
## R: Again the impact is only to Thomas HS other schools and summary reports are showing minimal impact by one point. This can tell us that due to the data being so similar to others taking Thomas HS it is not making a big impact on the overall information.

	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Size					
Small (<1000)	83.8	83.9	94	96	95
Medium (1000-2000)	83.4	83.9	88	91	90
Large (2000-5000)	77.7	81.3	70	83	76

	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
School Size					
Small (<1000)	83.8	83.9	94	96	95
Medium (1000-2000)	83.4	83.9	94	97	95
Large (2000-5000)	77.7	81.3	70	83	76

To answer the questions above, you will need to repeat some of the steps you did during the module:

Recreate the district and school summary DataFrames.


Recalculate the top 5 and bottom 5 performing schools.

Recalculate the average math score received by students in each grade level at each school.

Recalculate the average reading score received by students in each grade level at each school.

Recalculate the school performance based on the spending per student.

Recalculate the school performance based on the size of the school.

Recalculate the school performance based on the type of school.
