# Integrated-energy-grid


## 12.03.25 
We are looking into The Netherlands. 

  Look up the energy mix, to be able to make a good reflection. Find out the prices of the different generation methods.
  We're going to scale it down to some value ( let's say 1MW in total) and just have a representative amount that is the energy mix.

FInd information by friday and we start with the code. 


Source for fuel CO2 production (Coal and Natural Gas): https://ourworldindata.org/grapher/carbon-dioxide-emissions-factor?country=Bitumen~Anthracite~Charcoal~Coke~Natural+Gas~Oil+Shale+%26+Tar+Sands

Source for Power Generation Sense: https://www.irena.org/-/media/Files/IRENA/Agency/Publication/2024/Sep/IRENA_Renewable_power_generation_costs_in_2023.pdf

COSTS: 
solar: 
- capital: 753 USD/kW
- marginal: 18.2 USD/kWh
  
offshore: 
- capital: 2564 USD/kW
- marginal: 80 USD/kWh
  
onshore: 
- capital: 1600 USD/kW
- marginal: 40 USD/kWh
  
gas: euro
- capital: 0.58 Meuro/MW (I had 900 from one file)  
- marginal: 90 euro/MWh
  
coal(sub-critical): euro
- capital:  2.5 MEuro/MW
- marginal: 108 euro/MWh
- emissions: 0.8 
  
nuclear: euro
- capital: 8594 euro/kW
- marginal:16 euro/MWh
  


    GAS: initial investment: 0.57 MEuro/MW
    fixed O&M: 19500 euro/MW/year
    variable: 4.4 euro/MWh ( without fuel and CO2 ~70 to 120 with it ) 

    coal:
    initial investment: 2.5 MEuro/MW
    fixed O&M: 45500 euro/MW/year
    variable: 6.5 euro/MWh ( without fuel and CO2 ~108 euro/MWh)


 fuel costs:
- https://tradingeconomics.com/commodity/eu-natural-gas
- https://tradingeconomics.com/commodity/coal    
 
  CO2 floor thingy: https://www.rijksfinancien.nl/sites/default/files/bestanden/belastingplan-2024/overige-impactanalyses/Frontier-Economics-CPF-for-electricity-generation-and-industry-Supervisory-committee.pdf?utm_source=chatgpt.com

  Battery capital cost:
  https://www.iea.org/reports/batteries-and-secure-energy-transitions/executive-summary?utm_source=chatgpt.com

  Netherlands installed battery capacity:
  https://innovationorigins.com/en/home-batteries-drive-dutch-energy-storage-installations/?utm_source=chatgpt.com

  Hydro Pump Capital Cost: 
  https://iea.blob.core.windows.net/assets/4d2d4365-08c6-4171-9ea2-8549fabd1c8d/HydropowerSpecialMarketReport_corr.pdf?utm_source=chatgpt.com

  Netherlands Underground Pumped Hydro:
  https://deingenieur.nl/artikelen/energy-storage-using-water-is-an-option-in-the-netherlands

  Netherlands Lion Battery Storage System: 
  https://www.energy-storage.news/lion-storage-reaches-fid-on-1-4gwh-bess-in-the-netherlands/
