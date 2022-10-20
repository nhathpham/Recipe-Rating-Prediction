# Predicting Data Breaches Using Human Factors
Authors: Nhat Pham, Lakshyana KC
Data source: Linkedin Profiles, People Data Lab, Veris Data Breach (http://veriscommunity.net/vcdb.html)

<h2>I/ Abstract: </h2>
As members of Northeastern's DATA Initiative Research Lab, we partnered with InnSure, a nonprofit startup accelerator with a mission to influence a better future for the insurance industry. We would like to understand how various aspects of employee human behavior may impact the risk of cyber-breaches within firms. There are over 1000 annual publicized data breaches (Statista, 2020), resulting in $4.24 million average cost per data breach (IBM, 2021).
<br />
Objectives of the project include:<br />
• Develop a web-scraping tool that can be leveraged to gather Linked-In data <br />
• Formally propose, structure, and test hypotheses regarding human behavior and cyber 
breaches. <br />
• Propose a prototype for a “Cyber-Risk Index” using the behavioral attributes <br />
<br />

![innsure](https://user-images.githubusercontent.com/87089936/196846695-f05afbed-f330-4b84-82d5-b85d2c399752.PNG)<br />

<h2>II/ Results</h2>
★ Web Scraping and Property Identification <br />
- We performed a review of research on similar topic, and of Linkedin profile structures, to identify human factors to consider in the analysis<br />
- We focused solely on executive profiles, since research showed executives are significantly more vulnerable to cyber breaches than other employees<br />
- Results:<br />
+ A scraper tool using Selenium in Python that is able to capture various information facets of a Linked-In Profile<br />
+ ~1000 executive profile data, with a healthy sample size, in healthcare AND non-healthcare industries. <br />
<br />
Example of scraped profiles:<br />

![scraped_profile](https://user-images.githubusercontent.com/87089936/196847029-8bf9742f-960f-4516-a06f-4f4c7eaa80ac.PNG)<br />
<br />

+ Due to Linkedin's restriction on scraping, we also used Phantombuster, and People Data Labs, to scrape more executive profiles.

★	Classification Model <br />
- Random Forest<br />
- LinearSVC<br />
- Logistic Regression<br />
- AdaBoost <br />
- KNeighbors<br />
- GaussianNB<br />

Please see our Final Presentation for details.<br />

![image](https://user-images.githubusercontent.com/87089936/196848172-0faaf7b5-27ed-4226-b97d-0e8bec0f9165.png)

 
