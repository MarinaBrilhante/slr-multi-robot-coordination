# slr-multi-robot-coordination

Systematic Literature Review on Robot Fleet Management Systems and Multi-robot Coordination for wheeled mobile robots in industrial context.

## Identification

### Base Search String

```
(("robot" OR "agv" OR "amr") AND "fleet" AND "manag*" AND "system")
```

#### Total number of articles retrieved: 776

* [IEEE Xplore](http://ieeexplore.ieee.org)
  - 204 results
  - All metadata
  - Last inquiry: May 9, 2025 
  - ``` 1- (mobile robot* OR agv OR amr) AND fleet AND manag*``` &rarr; 177 results
  - ``` 2- ("robot" OR "agv" OR "amr" ) AND fleet AND "manag*" AND system``` &rarr; 191 results
  - We analysed all 177 results from query #1 and added the accepted ones (12) to the results of query #2. Resulting in 203 articles. Additionally, one article was added manually, a continuation of an already added article.

* [Scopus](http://www.scopus.com)
  - 301 results
  - Title + abstract + keywords
  - Last inquiry: April 23, 2025 
  - ``` 1- {Fleet Management System}``` - filtered by keyword: ```Fleet Operations```, ```Fleet Management System```, ```Fleet Management``` &rarr; 308 results 
  - ``` 2- ( "robot" OR "agv" OR "amr" ) AND fleet AND "manag*" AND system``` &rarr; 299 results
  - We added two articles from query #1 to the results of query #2.

* [Web of Science](http://www.isiknowledge.com)
  - 271 results
  - Web of Science Core Collection, All fields
  - Using the Base Search String
  - Last inquiry: May 9, 2025 


### Selection Criteria
#### Exclusion Criteria
* Availability: Papers not available in full
* Gray, Secondary, and Tertiary Literature: Books, reviews, thesis, ...
* Language: Papers not published in English
* Scope: Paper outside of the scope of "multi mobile robot in industrial setting"

#### Records removed before screening:
* Duplicated: 241
* Exclusion criteria: 18

## Screening
#### Records screened: 517
#### Records removed during screening: 
* Exclusion criteria (scope): 424

## Quality Assessment
#### Records assessed for quality: 93
#### Quality Assessment Checklist:
* 1 - Is the fleet management problem clearly defined and contextualized for mobile robots in industrial or warehouse settings? 
* 2 - Does the article provide a clear overview of the software/system architecture for multi-robot or fleet coordination?
* 3 - Are the path planning or motion planning algorithms described in sufficient detail?
* 4 - Does the article explain how tasks are assigned to robots, including any scheduling or coordination method? 
* 5 - Does it present a strategy for priority management, intersection handling, or traffic rules in multi-robot scenarios?
* 6 - Are there mechanisms discussed to detect or avoid deadlocks and livelocks? 
* 7 - Does the study implement or evaluate strategies for detecting and avoiding static/dynamic obstacles? 
* 8 - Is the system validated via simulation, testbed, or deployment in an industrial or realistic scenario?
* 9 - Are the results clearly presented and relevant to fleet management performance or coordination?
* 10 - Does the conclusion reflect on fleet management or coordination and align with the article’s objectives? 

#### Scoring:
* Yes: 2.0, Partially: 1.0, No: 0.0. 
* As not all questions were applicable to every article, a normalization process was applied to ensure fair
scoring. The **raw score** was calculated as the ```sum of points received```, and the **maximum possible score** for each article was computed as: ```number of answered questions × 2```. The **normalized score** was then derived by ```dividing the raw score by the maximum score```.

#### Records excluded:
* Q1, Q2, Q9 or Q10 = 0 &rarr; 14 records excluded
* Single Component Only &rarr; 8 records excluded
* Cut-off score (<75.0) &rarr; 31  records excluded

## Data Extraction
#### Records accepted for data extraction: 40

#### Data extraction items: 
* Methodology: methods/strategies/algorithms for Path Planning, Task Scheduling/Allocation, Obstacle Avoidance, Deadlock Avoidance, Priority Management, ...
* Architecture Type: centralized, decentralized, hybrid, ...
* Fleet Type: homogeneous, heterogeneous

## Results Overview

Analysis of the bibliographic data retrieved from the 40 included articles, using the [VOSviewer](https://www.vosviewer.com/) tool. 

#### Keywords co-occurence
<img width="3004" height="1826" alt="co_occurance_14_overlay_visu" src="https://github.com/user-attachments/assets/09bba26a-0aaa-4f0f-b085-234aa541ec79" />
<img width="3004" height="1826" alt="co_occurance_14_network_visu" src="https://github.com/user-attachments/assets/35309979-f926-4208-82a4-8655deb7543b" />

#### Co-authorship analysis
<img width="3004" height="1826" alt="co_authorship_13authors" src="https://github.com/user-attachments/assets/9b60fc2f-3350-4bbf-8a45-aec3eb3d4ea3" />

#### Evolution of number of published articles by year
<img width="1015" height="768" alt="chart_year" src="https://github.com/user-attachments/assets/7d45c617-9afb-4b0c-b152-f852429b946b" />

## License

[MIT](https://choosealicense.com/licenses/mit/)
