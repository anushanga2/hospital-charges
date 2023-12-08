# Decoding America's Healthcare Costs: Unveiling Trends, Providers, and Patient Stories in Extensive Data Analysis
This report examines a dataset of hospital charges in the United States, identifying issues within the existing processes and subsequently streamlining them for improved efficiency.  

# Introduction 
The following report analyzes a dataset of hospital charges in the USA, encompassing records of over 150,000 treatments across various providers addressing specific ailments. The dataset features details on 100 ailments, includes a list of 3000+ healthcare providers, and incorporates data from all 50 states and around 2000 cities across the USA. 
In the given dataset DRG definition represents the Diagnosis related group which is a classification system used in healthcare to group patients with respect to diagnoses and treatments for medical billing. Provider ID is a unique identifier for each healthcare facility to distinguish one healthcare entity from another. Provider name represents the name of the healthcare facility. In the given data total discharges represent the number of patients who were discharged within a particular time frame. Average covered charges show the average costs that healthcare providers charge for services related to a particular DRG. Average total payments represent the amount that a healthcare provider received in response to a particular service. The charges attribute includes the cost or charges associated with medical services provided specific to a case. Average medicare payments represent the average payment made by the medicare program for medical services provided under specified DRG.  
# Demographic Analysis 
## Distribution of healthcare provider by state 

![Figure 1: Cost variation for the healthcare provider by state](https://github.com/anushanga2/hospital-charges/blob/main/images/1.PNG)  
Figure 1: Cost variation for the healthcare provider by state

Out of all the states in the USA, California has the highest number of healthcare providers with 12,997 providers. The next state with most healthcare providers is Texas with 11,864 providers. Alaska and Wyoming have the least number of healthcare providers respectively with 230 and 247 respectively. This represents that Alaska, and Wyoming have the potential to have weaker access to healthcare services. California also has the highest average covered charge of $67,567. Maryland represents the least number of average covered charges of $13,377. Alaska shows the highest number of medical payments while Alabama ($14,599) has the least medical payment ($7,444). 
## Distribution of healthcare provider by the city 

![Figure 2: Cost variation for the healthcare provider by City](https://github.com/anushanga2/hospital-charges/blob/main/images/2.PNG)  
Figure 2: Cost variation for the healthcare provider by City

Chicago has contributed to the highest number of discharges(6,516) out of all the cities in the USA. Cherokee, Eldridge, Hamlin, Kinder, Nantucket, Norway, and Oak Forest cities have the least amount of discharges in the USA with just 11 discharges. As far as costs of covered charges are considered, Bayonne has the highest number of charges with $147,441. Stanford has the next most number of charges with $139,376. Dilley has the least amount of covered charges with $2,995. When considering average medicare payments, vail has the highest amount of medicare payments and Dilley has the lowest average medicare payments amounting to $39,943 and $2,872 respectively. 
Distribution of cost with respect to the DRG

![Figure 3: Average covered charges and average total payments](https://github.com/anushanga2/hospital-charges/blob/main/images/3.PNG)  
Figure 3: Average covered charges and average total payments 

![Figure 4: Average total payments and average medicare payments](https://github.com/anushanga2/hospital-charges/blob/main/images/4.PNG)  
Figure 4: Average total payments and average medicare payments


When considering the average total payments, the most expensive DRG is the Septicemia or Severe Sepsis with MV 96+ hours. The second most expensive DRG is the Infectious and Parasitic diseases. There is also a strong correlation between total payments and average medicare payments. 
# Cost Analysis 

![Figure 5: Top 20 most affordable hospitals in USA](https://github.com/anushanga2/hospital-charges/blob/main/images/5.PNG)  
Figure 5: Top 20 most affordable hospitals in USA  

Out of all the medical providers in the USA, Community General Hospital is the most affordable hospital in the USA with an average cost of $2,995. Other affordable hospitals in the USA are Sharkey Issaquena community hospital, Knox county hospital, Turning point hospital, Lake whitney hospital, and W O Moss regional medical center respectively. 


![Figure 6: Top 20 most expensive hospitals in USA](https://github.com/anushanga2/hospital-charges/blob/main/images/6.PNG)  
Figure 6: Top 20 most expensive hospitals in USA   

When considering the most expensive hospitals in the USA, UVA health science center is the most expensive hospital with an average covered charge of $211,922. Other most expensive hospitals in the USA include Bayonne hospital center, Doctors medical center, Stanford hospital, and Northbay medical center.

![Figure 7: Top 20 hospitals with respect to highest average medicare payment](https://github.com/anushanga2/hospital-charges/blob/main/images/7.PNG)  
Figure 7: Top 20 hospitals with respect to highest average medicare payment   

When considering the hospitals with respect to the highest average medicare payment, it can be identified that Uva health science center has the highest average medical payment of $41,836 and Vail valley medical center has second most average medical payment of $39,943. The hospitals with lowest average medicare payments are identified as Brighton hospital, Wilmington treatment center, and Methodist west houston hospital respectively. 
# Conclusion 
In conclusion, the healthcare dataset for the United States serves as a valuable tool for identifying and addressing process inefficiencies, allowing for streamlined operations and more efficient resource allocation. Notably, California stands out with the highest number of healthcare providers and an average covered charge of $67,567, indicative of increased demand driving pricing trends. Examining cities, Chicago leads in discharges (6,516), while Bayonne records the highest healthcare charges at $147,441. 

Delving into specific Diagnosis Related Groups (DRGs), Septicemia or Severe Sepsis with MV 96+ hours emerges as the most expensive. Analyzing Medicare providers, Community General Hospital emerges as the most cost-effective with an average cost of $2,995, while UVA Health Science Center tops the list with an average covered charge of $211,922. Notably, UVA Health Science Center also records the highest average Medicare payment at $41,836, followed closely by Vail Valley Medical Center at $39,943. 

These insights underscore the diverse capacities of hospitals in managing patient discharges, emphasizing the importance of strategic resource allocation, effective planning, and understanding the impacts on institutions handling substantial patient loads. Additionally, the data highlights variations in healthcare facility availability, empowering stakeholders to make informed decisions about accessing new healthcare resources. 
