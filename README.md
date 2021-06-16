# A Written Report for the Surfs Up Analysis

## Overview of Surfs Up Analysis
 W. Avy is a potential business partner who would like coherent information of Hawaii weather before opening up a surf and ice cream shop on the island of Oahu. W. Avy wants temperature data for the months of June and December to see if the business is able to be open year round, so through the information obtained through hawaii.sqlite we will retrieve that information then condense it into two databases. 

### Resources
**Source of Data** : hawaii.sqlite

**Software** : Python 3.7.6 , Jupyter Notebook, Visual Studio Code.

## Results
### June 
The important information to ascertain from the June chart is that the average temperature would be close to 75°F, with the max temperature at 85°F and most of the time it would be closer to 77°F.

![junetemp](https://user-images.githubusercontent.com/82983000/122286472-e3262200-cebd-11eb-9ca2-050b618a7312.png)

### December
For December the average temperature would of course be lower, however, not so much that would deter tourists or locals from visiting the shop.The average temperature is around 71°F, with the max temperature at 83°F and 74°F most of the time. 

![dectemp](https://user-images.githubusercontent.com/82983000/122286763-34ceac80-cebe-11eb-9148-3f6c45f3b5c2.png)

### Differences

- June average temperature is 74.94°F to December's average temperature at 71.04°F
- June max temperature is 85°F whereas December max temperature is 83°F
- June min temperature is 64°F with December min temperature at 56°F

## Summary
The difference between June and December are negligible when it comes to weather. December is colder across all counts with the minimum temperature being far colder than June’s coldest temperature, however, on average both months remain in the lower 70’s with both maxing out at the higher 80’s.  

### Additionals

As this is a surf and ice cream shop the other determining factor when it comes to success besides the temperature is precipitation. By utilizing the same engine in sqlite and a refactored code we can find the average rainfall across the two months. 


![junerains](https://user-images.githubusercontent.com/82983000/122288795-fa660f00-cebf-11eb-9dad-8a86d6fc6c3f.png)



![decrains](https://user-images.githubusercontent.com/82983000/122288811-ffc35980-cebf-11eb-9a22-448fdb70edf9.png)


From the additional charts we can see that rain is not prominent on the island of Oahu and therefore should not cause too much of a problem for the ice cream surf shop. 






