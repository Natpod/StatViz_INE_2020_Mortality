# StatViz_INE_2020_Mortality
Code and Description for Visualizations for the Master in Computational Biology Statistic Data Analysis and Visualization course in 2020 Mortality INE dataset(2022)
Authors : Lucía Martín Fernandez, Ana Solbas Casajús, Ángela Gómez Sacristán and Natalia García Sánchez

Data comes from the following sources: 

- **Mortality rate in Spanish provinces (2020)**: https://datos.gob.es/en/catalogo/ea0010587-defunciones-por-lugar-de-residencia-capitales-mes-de-la-defuncion-y-sexo-mnpd-identificador-api-t20-e301-defun-a2020-l0-20009-px  
- **Crude mortality rate (per year)**: https://www.ine.es/jaxiT3/Tabla.htm?t=1411&L=0 
- **Mortality rate per year, age and sex**: https://www.ine.es/jaxiT3/Tabla.htm?t=27150
- **Death causes**: https://datos.gob.es/en/catalogo/ea0010587-defunciones-por-causas-capitulos-sexo-y-provincia-ecm-identificador-api-49044
- **Average age in population per Autonomous Community** : https://www.ine.es/jaxiT3/Datos.htm?t=3198#!tabs-tabla

In addition, there are three R markdown files that have been used to generate the visualizations for the assignment. 

- `BarplotsINEDeaths.Rmd`: script used to generate the barplot and boxplots charts. 
- `Spain_maps.Rmd`: script used to generate the Spain map plots containing information about the 2020 death rates by province and Autonomous Community. 
- `mortalityRatePerYear.Rmd`: script used to generate the time series plots for death rate and life expectancy in Spain as well as the death rate per age and sex in 2020 barplot. 

Dependencies : *mapSpain, reshape2, ggplot2, sf, dplyr, tidyr* should be preinstalled in an R environment
