# Dean-690-Project | Team Love 911 | Second Provider Calls
<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->








#### [George Mason University](https://www2.gmu.edu)
#### DAEN Department | DAEN 690 | Professor: Bernard Schmidt
#### FALL 2021 



<!-- ABOUT THE PROJECT -->
## About The Project

Fire Departments across the nation are being challenged with rising call volume, personnel, and equipment shortages. Managing these challenges requires a basic understanding of how changes in levels of fire department resources that are deployed affect the outcomes from emergencies that occur regularly. Failure in managing these challenges may leave the individuals and community vulnerable to undesirable events. To avoid such situations, The Fairfax County Fire and Rescue Department(FCFRD) would require implementing strategies to predict the requirements for each causality based on the type of call received. The FCFRD needs to determine which circumstances would require a second additional life support provider to be accompanied by a medic unit. This would provide a detailed classification of the type of calls that would require a second additional life support unit. It would help the FCFRD reduce the arrival time and enhance service to the community.  Since the cost involved in dispatching an ALS unit is observed to be greater than a BLS unit, the FCFRD also considers transitioning some ALS units to BLS whenever it is considered sensible. This would help the FCFRD allocate resources effectively and would provide a safe environment to the community by minimizing the impact of the incidents that have occurred.

<p align="right">(<a href="#top">back to top</a>)</p>




## Problem

1 . Under what circumstances do we need a Second Provider?
2 . Under what circumstances can ALS be reduced to BLS?

<p align="right">(<a href="#top">back to top</a>)</p>


## Team Members

* Shreya Reddy            | Product Owner
* Huichao Zhao            | Developer
* Cheng-Han Chung         | Developer
* Apisit Junkun           | Developer
* Phuriwat Nitikunchainun | Developer
* Venkata Sushanth        | Developer
* Zaid Altukhi            | Developer

<p align="right">(<a href="#top">back to top</a>)</p>



## Tools Used

* [Pandas](https://pandas.pydata.org)
* [NumPy](https://numpy.org)
* [Python](https://www.python.org/)
* [MS Excel](https://www.microsoft.com/en-us/microsoft-365/excel/)
* [Tableau](tableau.com/)
* [matplotlib](https://matplotlib.org/)
* [sklearn](https://scikit-learn.org)
* [scipy](https://www.scipy.org)

<p align="right">(<a href="#top">back to top</a>)</p>



## Analytics

* Decision tree
* Logistic Regression
* Correlation Analysis
* Precision Analysis

<p align="right">(<a href="#top">back to top</a>)</p>



## Detect Second Provider

Three steps to classify Second Provider Calls
Step 1 : TransportLOC column contains categories from level one to level four. "Level one" implies that it was a second provider case.
Step 2 : The number of the different units that have transport status in the unit history dataset is "greater than one".
Step 3 : Match the time that the units were out of service and the time that units back to service to during the incident.
![image](https://user-images.githubusercontent.com/62821251/144661891-7de92131-d9b8-40f2-b292-2bcc72a713db.png)


<p align="right">(<a href="#top">back to top</a>)</p>



## Downgrade to BLS

Ambulances in the U.S. are divided into two types: Advanced Life Support(ALS) and Basic Life Support(BLS). ALS is a high-level ambulance that specializes in transporting severely injured patients, while BLS is a basic ambulance that is responsible for transporting patients who are not in critical condition. According to Fairfax County regulations, ambulances are dispatched with ALS to rescue the injured. However, in most cases, the injured only need BLS and not ALS. Therefore, we use the dataset to find out in which situations only BLS is needed but ALS is sent to rescue. We find these cases through analysis methods and provide them to FCFRD for reference to determine whether it is possible to send only BLS in these situations.



<p align="right">(<a href="#top">back to top</a>)</p>



