# EDA-_Project1
Performing a exploratory data analysis on a global terrorism dataset
1. the dataset has alot of empty spaces and irrelevant columns that will not not be needed since our specific focus is on the hot zones during the terrorism attack
2. some valuable insights such as the top 10 countries that got most affected, the citites.
these are the various columns that are in nthe dataset and thier descirption
these are the description of the 135 columns:

1. `eventid`: Unique identifier for each event.
2. `iyear`: Year of the incident.
3. `imonth`: Month of the incident.
4. `iday`: Day of the incident.
5. `approxdate`: Approximate date of the incident.
6. `extended`: Indicates if the incident extended over 24 hours.
7. `resolution`: Resolution of the incident.
8. `country`: Numeric code for the country where the incident occurred.
9. `country_txt`: Name of the country where the incident occurred.
10. `region`: Numeric code for the region where the incident occurred.
11. `region_txt`: Name of the region where the incident occurred.
12. `provstate`: Province or state where the incident occurred.
13. `city`: City or location where the incident occurred.
14. `latitude`: Latitude coordinate of the incident location.
15. `longitude`: Longitude coordinate of the incident location.
16. `specificity`: Level of specificity of the incident location.
17. `vicinity`: Indicates if the incident occurred in the vicinity of the location.
18. `location`: Description of the location where the incident occurred.
19. `summary`: Summary or overview of the incident.
20. `crit1`: Indicator if the incident meets criterion 1 (political, economic, religious, or social goal).
21. `crit2`: Indicator if the incident meets criterion 2 (intentional use of violence).
22. `crit3`: Indicator if the incident meets criterion 3 (substantial human harm).
23. `doubtterr`: Indicates if there is doubt about the terrorist nature of the incident.
24. `alternative`: Alternative code for the type of incident.
25. `alternative_txt`: Alternative description for the type of incident.
26. `multiple`: Indicates if multiple incidents are associated with the event.
27. `success`: Indicates if the terrorist action was successful.
28. `suicide`: Indicates if the incident involved a suicide attack.
29. `attacktype1`: Numeric code for the primary attack type.
30. `attacktype1_txt`: Description of the primary attack type.
31. `attacktype2`: Numeric code for the secondary attack type.
32. `attacktype2_txt`: Description of the secondary attack type.
33. `attacktype3`: Numeric code for the tertiary attack type.
34. `attacktype3_txt`: Description of the tertiary attack type.
35. `targtype1`: Numeric code for the primary target type.
36. `targtype1_txt`: Description of the primary target type.
37. `targsubtype1`: Numeric code for the primary target subtype.
38. `targsubtype1_txt`: Description of the primary target subtype.
39. `corp1`: Name of the corporation or organization targeted.
40. `target1`: Specific target/victim of the attack.
41. `natlty1`: Numeric code for the nationality of the target.
42. `natlty1_txt`: Name of the nationality of the target.
43. `targtype2`: Numeric code for the secondary target type.
44. `targtype2_txt`: Description of the secondary target type.
45. `targsubtype2`: Numeric code for the secondary target subtype.
46. `targsubtype2_txt`: Description of the secondary target subtype.
47. `corp2`: Name of the second corporation or organization targeted.
48. `target2`: Specific second target/victim of the attack.
49. `natlty2`: Numeric code for the nationality of the second target.
50. `natlty2_txt`: Name of the nationality of the second target.
51. `targtype3`: Numeric code for the tertiary target type.
52. `targtype3_txt`: Description of the tertiary target type.
53. `targsubtype3`: Numeric code for the tertiary target subtype.
54. `targsubtype3_txt`: Description of the tertiary target subtype.
55. `corp3`: Name of the third corporation or organization targeted.
56. `target3`: Specific third target/victim of the attack.
57. `natlty3`: Numeric code for the nationality of the third target.
58. `natlty3_txt`: Name of the nationality of the third target.
59. `gname`: Name of the group responsible for the incident.
60. `gsubname`: Subname or faction of the group responsible for the incident.
61. `gname2`: Name of a second group responsible for the incident.
62. `gsubname2`: Subname or faction of the second group responsible for the incident.
63. `gname3`: Name of a third group responsible for the incident.
64. `gsubname3`: Subname or faction of the third group responsible for the incident.
65. `motive`: Possible motive or reason behind the incident.

1. `guncertain1`: Indicates uncertainty about the presence of guns in the incident for the group responsible.
2. `guncertain2`: Indicates uncertainty about the presence of guns in the incident for a second group responsible.
3. `guncertain3`: Indicates uncertainty about the presence of guns in the incident for a third group responsible.
4. `individual`: Indicates if the incident was carried out by an individual rather than a group.
5. `nperps`: Number of perpetrators involved in the incident.
6. `nperpcap`: Number of perpetrators captured during the incident.
7. `claimed`: Indicates if a group or individual claimed responsibility for the incident.
8. `claimmode`: Numeric code for the method of claim.
9. `claimmode_txt`: Description of the method of claim.
10. `claim2`: Additional claim of responsibility by a second group or individual.
11. `claimmode2`: Numeric code for the method of the second claim.
12. `claimmode2_txt`: Description of the method of the second claim.
13. `claim3`: Additional claim of responsibility by a third group or individual.
14. `claimmode3`: Numeric code for the method of the third claim.
15. `claimmode3_txt`: Description of the method of the third claim.
16. `compclaim`: Indicates if there is a competing claim of responsibility for the incident.
17. `weaptype1`: Numeric code for the primary weapon type used in the incident.
18. `weaptype1_txt`: Description of the primary weapon type.
19. `weapsubtype1`: Numeric code for the subcategory of the primary weapon type.
20. `weapsubtype1_txt`: Description of the subcategory of the primary weapon type.
21. `weaptype2`: Numeric code for the secondary weapon type used in the incident.
22. `weaptype2_txt`: Description of the secondary weapon type.
23. `weapsubtype2`: Numeric code for the subcategory of the secondary weapon type.
24. `weapsubtype2_txt`: Description of the subcategory of the secondary weapon type.
25. `weaptype3`: Numeric code for the tertiary weapon type used in the incident.
26. `weaptype3_txt`: Description of the tertiary weapon type.
27. `weapsubtype3`: Numeric code for the subcategory of the tertiary weapon type.
28. `weapsubtype3_txt`: Description of the subcategory of the tertiary weapon type.
29. `weaptype4`: Numeric code for the fourth weapon type used in the incident.
30. `weaptype4_txt`: Description of the fourth weapon type.
31. `weapsubtype4`: Numeric code for the subcategory of the fourth weapon type.
32. `weapsubtype4_txt`: Description of the subcategory of the fourth weapon type.
33. `weapdetail`: Additional details about the weapons used in the incident.
34. `nkill`: Number of total confirmed kills in the incident.
35. `nkillus`: Number of confirmed kills of U.S. citizens in the incident.
36. `nkillter`: Number of confirmed kills of terrorists in the incident.
37. `nwound`: Number of total confirmed wounded in the incident.
38. `nwoundus`: Number of confirmed wounded U.S. citizens in the incident.
39. `nwoundte`: Number of confirmed wounded terrorists in the incident.
40. `property`: Indicates if property was damaged or destroyed in the incident.
41. `propextent`: Numeric code for the extent of property damage.
42. `propextent_txt`: Description of the extent of property damage.
43. `propvalue`: Value of the damaged or destroyed property.
44. `propcomment`: Additional comments or details about the property damage.
45. `ishostkid`: Indicates if hostages were taken during the incident.
46. `nhostkid`: Number of hostages taken during the incident.
47. `nhostkidus`: Number of U.S. citizen hostages taken during the incident.
48. `nhours`: Duration of the incident in hours.
49. `ndays`: Duration of the incident in days.
50. `divert`: Indicates if a hijacking or diversion of transportation occurred during the incident.
51. `kidhijcountry`: Country where a hijacking or kidnapping took place during the incident.
52. `ransom`: Indicates if a ransom was demanded during the incident.
53. `ransomamt`: Amount of ransom demanded.
54. `ransomamtus`: Amount of ransom demanded in U.S. dollars.
55. `ransompaid`: Amount of ransom paid.
56. `ransompaidus`: Amount of ransom paid in U.S. dollars.
57. `ransomnote`: Details or content of the ransom note.
58. `hostkidoutcome`: Outcome of the hostage situation.
58. `hostkidoutcome_txt`: Description of the outcome of the hostage situation.
59. `nreleased`: Number of hostages released during the incident.
60. `addnotes`: Additional notes or comments about the incident.
61. `scite1`: Citation or source of information for the incident.
62. `scite2`: Additional citation or source of information for the incident.
63. `scite3`: Additional citation or source of information for the incident.
64. `dbsource`: The database source from which the information is derived.
65. `INT_LOG`: Logistical international involvement in the incident (0 = No, 1 = Yes).
66. `INT_IDEO`: Ideological international involvement in the incident (0 = No, 1 = Yes).
67. `INT_MISC`: Miscellaneous international involvement in the incident (0 = No, 1 = Yes).
68. `INT_ANY`: Any form of international involvement in the incident (0 = No, 1 = Yes).
69. `related`: Related incidents or events that are linked to the current incident.
