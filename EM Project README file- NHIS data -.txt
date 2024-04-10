EM Project README file- NHIS data - DATA-FINAL
------------------------------------------------------------------------------------------------
LAYOUT:

varname
condition

description:
------------------------------------------------------------------------------------------------
0
id
6-digit code

description: THIS 6 DIGIT CODE DENOTES A UNIQUE IDENITIFIER FOR SURVEY PARTICIPANT. USED TO MATCH SAMPLE ADULT AND PERSONAL FILES.

1
SRVY-YR
4-digit code

description: THIS IS THE YEAR WHEN THE SURVEY WAS TAKEN.

2
ALC1YR
condition
Freq drank alcohol pst yr: Time unit
0 Never/None
1 Week
2 Month
3 Year
7 Refused
8 Not ascertained
9 Don't know

description:In ANY ONE YEAR, have you had at least 12 drinks of any type of alcoholic beverage?

3
ALCLIFE
condition
Had 12+ drinks in ENTIRE LIFE
1 Yes
2 No
7 Refused
8 Not ascertained
9 Don't know

description:In your ENTIRE LIFE, have you had at least 12 drinks of any type of alcoholic beverage?

4
ALC12MNO
condition
Freq drank alcohol pst yr: # of units
000 Never
001-365 1-365 day(s)
997 Refused
998 Not ascertained
999 Don't know

description:In the PAST YEAR, how often did you drink any type of alcoholic beverage?

5
ALC12MTP
condition
Freq drank alcohol pst yr: Time unit
0 Never/None
1 Week
2 Month
3 Year
7 Refused
8 Not ascertained
9 Don't know

description:In the PAST YEAR, how often did you drink any type of alcoholic beverage?

6
ALC12MYR
condition
Freq drank alcohol: Days in past year
000 Never/none
001-365 1-365 days
997 Refused
998 Not ascertained
999 Don't know

description:In the PAST YEAR, how often did you drink any type of alcoholic beverage?

7
ALCAMT
condition
Average # drinks on days drank
01-94 1-94 drinks
95 95+ drinks
97 Refused
98 Not ascertained
99 Don't know

description:In the PAST YEAR, on those days that you drank alcoholic beverages, on the average, how many drinks did you have?

8
ALC5UPNO
condition
Days 5+ drinks, past yr: # days
000 Never/None
001-365 1-365 day(s)
997 Refused
998 Not ascertained
999 Don't know

description:In the PAST YEAR, on how many DAYS did you have 5 or more drinks of any alcoholic beverage?

9
ALC5UPTP
condition
Days 5+ drinks, past yr: Time unit
0 Never/None
1 Per week
2 Per month
3 Per year
7 Refused
8 Not ascertained
9 Don't know

description:In the PAST YEAR, on how many DAYS did you have 5 or more drinks of any alcoholic beverage?

10
ALC5UPYR
condition
Number of days had 5+ drinks past year
000 Never/None
001-365 1-365 days
997 Refused
998 Not ascertained
999 Don't know

description: In the PAST YEAR, on how many DAYS did you have 5 or more drinks of any alcoholic beverage?

11
ALCSTAT1
condition
Alcohol drinking status: Recode
01 Lifetime abstainer
02 Former infrequent
03 Former regular
04 Former, unknown frequency
05 Current infrequent
06 Current light
07 Current moderate
08 Current heavier
09 Current drinker, frequency/level unknown
10 Drinking status unknown

description: description code for type of drinker the person is (left in as it is an interesting metric to have on hand just in case)

12
white
=1, if white
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS WHITE.

13
black
=1, if black
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS BLACK.

14
hisp
=1, if hispanic
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS HISPANIC.

15
employed
=1, if had a job in the last week
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS EMPLOYED AT A JOB FOR PAY.

16
nw
=1, if looking for work
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS LOOKING FOR WORK.

17
diploma
=1, if obtained at highest a highschool diploma
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY HAD ACHIEVED AT LEAST A HIGHSCHOOL DIPLOMA AS THEIR HIGHEST EDUCATION LEVEL.

18
nodiploma
=1, if obtained at highest below a highschool diploma
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY HAD ACHIEVED BELOW A HIGHSCHOOL DIPLOMA AS THEIR HIGHEST EDUCATION LEVEL.

19
uninsured
=1, if no insurance
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS WITHOUT HEALTH INSURANCE.

20
age
int

description: THIS IS A VARIABLE FOR AGE CENTERED AROUND 21 (ie. age= NOMINAL AGE- 21).

21
age2
int

description: THIS IS A VARIABLE FOR AGE CENTERED AROUND 21 (ie. age= NOMINAL AGE- 21) SQUARED.

22
age
=1, if male
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS MALE.

23
over21
=1, if age>-1
=0, otherwise

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY WAS OVER 21 AT TIME OF SURVEY.

24
northw
=1, if in northwest
=0, otherwise
=-1, from 2004 which did not include this data when including region as control drop 2004

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY LIVED IN THE NORTHWEST AT TIME OF SURVEY.

25
midw
=1, if in midwest
=0, otherwise
=-1, from 2004 which did not include this data when including region as control drop 2004

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY LIVED IN THE MIDWEST AT TIME OF SURVEY. THERE IS NO REGION DATA IN 2004.

26
south
=1, if in south
=0, otherwise
=-1, from 2004 which did not include this data when including region as control drop 2004

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY LIVED IN THE SOUTH AT TIME OF SURVEY. THERE IS NO REGION DATA IN 2004.

27
west
=1, if in west
=0, otherwise
=-1, from 2004 which did not include this data when including region as control drop 2004

description: THIS IS A BINARY VARIABLE THAT EQUALS 1 WHEN THE RESPONDANT TO THE SURVEY LIVED IN THE WEST AT TIME OF SURVEY. THERE IS NO REGION DATA IN 2004.

28
hos
double (float)

description: ASSIGNED TO EACH PERSON THE AVERAGE HOSPITAL COVERAGE IN THEIR REGION, CALCULATED BY TAKING THE PER CAPITA HOSPITALS IN THEIR SURVEY REGION