**Project Status**: Done  
**Code & Visualisations**: [Here](https://github.com/IchfanKurniawan/quantium-intern-project/blob/master/code/quantium-intern-project-01.ipynb)    
 
## Project Context
As part of Quantium’s retail analytics tem and approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region,  let's explore the dataset & find insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.  


## FINDINGS  
**General Distribution?**
- lifestage: RETIREES, OLDER SINGLES/COUPLES, and YOUNG SINGLE/COUPLES are on top 3 in the number of record
- the exact distribution of lifestage in the record
- YOUNG FAMILIES, OLDER FAMILIES, YOUNG SINGLES/COUPLES, OLDER SINGLES/COUPLES, and RETIREES are almost 90%  
- premium_customer: the order is mainstream > budget > premium
- Top 3 product in term of the number of records are Smiths, Doritos, Thins
- Smiths, Doritos, Thins, Cobs are almost 80% of the records
- 175g is the most dominant(~40% of record)
- 175, 170, 110 are more than 70% of record



**What it is like the distrbution of lifestage in the premium customer category?**  
from the heatmap, we know:   
- the most dominant is the young singles/couples-mainstream  
- the most dominant lifestage in premium category coming from older singles/couples & retirees  

**How many product each lifestage category buy?**	
- in term of number product bought, the most dominant are retirees, older single/couples, & then young singles/couples  
- almost no difference in term of mean product bought  

**How much sales each lifestage category contribute?**
- in term of total product bought, the most dominant are retirees, older single/couples, & then young singles/couples  
- almost no difference in term of mean sales  
- retirees, older single/couples, & then young singles/couples are account for 60++% of sales based on pareto  
	
**What are the most popular brand for each lifestage category?**
- from the brand name distribution before, we know that Smiths, Doritos, & Thins are the most dominant brand  
- from the lifestage distribution before, we know that retirees, older singles/couples, young singles/couples are the most dominant  
- from the heatmap, we know:  
    - the most dominant brands are also mostly bought by the most dominant lifestages   
    - almost 15% product bought is the Smiths products bought & they were bought by the most dominant lifestages  
    - more than 10% product bought is the Doritos products bought & they were bought by the most dominant lifestages  
    - almost 10% product bought is the Thins products bought & they were bought by the most dominant lifestages  
		
**what are the most popular pack size for each lifestage category?**
- from the pack size distribution before, we know that 170, 175, 110 are the most dominant brand  
- from the lifestage distribution before, we know that retirees, older singles/couples, young singles/couples are the most dominant  
- from the heatmap, it is clear that:  
    - 175 gram is the most dominant almost across all lifestages (~40%)  
    - which distributed almost evenly equal to 8% across the most dominant lifestage cetegories  
		
**how many product for each premium_customer category buy?**
- in term of number of bought products, the order is mainstream > budget > premium (still same)  
- and this result is still make sense, because the mainstream is ~40% of the customer  
	
**how much sales for each premium_customer category contribute?**
- no difference than the number of product bought for each premium_customer categories  
- and this result is still make sense, because the mainstream is ~40% of the customer  
- however, what if we normalized the total sales with the number of bought product, so that we could get the normalized sales given by each customer category  

- we know that the mainstream customer category is the most dominant (~40%) and the premium  is the least one (~27%), in term of number customer  

- from here, we know that in term of obtained value/sales (dollar for each bought product) is still proportional with the result before, the mainstream category is the most dominant.  
- However the difference are marginal (less than 2 cent)  

Then:  
- focus on mainstream -> it means, high volumne low margin  
- focus on premium -> it means, low volumne high margin  
	
**what are the most popular brand for each premium_customer category?**  
- from the heatmap, we know that all customer category are all agree that Smiths brand is the most preferred brand  
	
**what are the most popular pack size for each premium_customer category?**  
- from the heatmap, we know that all customer categories are all agree that 175g is the most preferred pack size  
	
**how many product for each brand_name category sold?**  
- in term of number product sold, Smiths, Doritos, Thins, & Cobs are account for more than ~85%  
	
**how much sales for each brand_name category contribute?**
- in term of total sales, Smiths, Doritos, Thins, & Cobs are account for more than ~82%  
- even though the total sales is quite low, however in term of mean of sales, Tostitos brand is the highest brand (Tostitos brand is expensive?)  
	
**how many product for each pack_size category sold?**  
	- in term of number product sold, 175 & 170 only are account for almost ~60%  
	
**how much sales for each pack_size category contribute?**  
- in term of total sales, 175 & 170 only are account for almost ~57%  
- if plus 110g then more than ~70% of total sales  

Then:  
- 175g, 170g, 110g are in the middle -> it means that medium volume & medium margin  
- 380g -> low volume & high margin  
- 200g -> high volume & low margin  
	
**is there any trend over time in term of buying product in the lifestage category?**  
- in weekly frame, there are 3 huge spikes  
- the first spike happened in the second week of July  
- the second spike happened in the forth week of December  
- the third spike happened in the first week of June  
	
**is there any trend over time in term of buying product in the premium_customer category?**  
- in weekly frame, there are 3 huge spikes >>> same with the lifestage before  
- the first spike happened in the second week of July  
- the second spike happened in the forth week of December  
- the third spike happened in the first week of June   
	
**is there any trend over time in term of buying product in the brand name category?**  
- near weekend, there are spikes in sales for every product  
	
**is there any trend over time in term of buying product in the pack_size category?**  
- in weekly frame,there are two huge spikes happened  
- first week of the month, there are little spike  
- huge spikes in the second week of July 2018 and in the third week of December 2019  
