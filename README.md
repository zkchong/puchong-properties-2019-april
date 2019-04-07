# Puchong properties on 2019 April

Real estate is one of the favorite investments for working folks in Malaysia. As part of the data savvy company, the data engineering team harvested the prices of Puchong properties from one of the famous properties website. 

Like you guys, we have a lot of questions in our mind:

1. Do all the properties share about the same price per square foot (psf)  if they are located at about the same area with about same number of rooms?
2. Will the psf be slightly higher if they are located near to the main road?
3. Which properties should I invest ? 

We can't answer of all them.

Hence, we decided to share the extracted data (Puchong area only) at github. May all the mighty data scientists to plot their best insight. 


# File
- puchong-data.csv : Puchong properties raw data.
- puchong-groupby-addr-name.csv : Puchong properties group by project name. 

# Column Names of puchong-data.csv
Most of the column names are self-explanatory.

- id : ID of the unit in one of the favourite properties website.
- lat : Lattitude of the unit.
- lng : Longitude of the unit. 
- bathroom : Total of bathroom of the unit.
- bedroom : Total of bedroom of the unit.
- builtUp : The built up area in m2.
- carPark : Number of car park.
- maintenanceFee :  Most of them didn't specify.
- maximumPricePerSizeUnit: Maximum price per size.
- minimumPricePerSizeUnit: Minimum price per size.
- pricePSF : Price per square foot.
- addr_l1 : Address in term of state.
- addr_l2 : Address in term of area (city).
- addr_l3 : Building name.
- currency : Currency. In Ringgit.
- price_min : Minimum selling price.
- price_max : Maximum selling price.
- title : The title of unit in the properties website. We notice some of them didnt specify the addr_l3 and there is a need to ETL this field to get the right addr_l3. 
