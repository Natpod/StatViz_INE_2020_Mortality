# StatViz_INE_2020_Mortality
Code and Description for Visualizations for the Master in Computational Biology Statistic Data Analysis and Visualization course in 2020 Mortality INE dataset(2022)
Authors : Lucía Martín Fernandez, Ana Solbas Casajús, Ángela Gómez Sacristán and Natalia García Sánchez

Data comes from the following sources: 

Data corresponds to the following datasets (sources commented on https://github.com/Natpod/StatViz_INE_2020_Mortality):

| Filename   |      Description      |  Used in code | Source |
|----------|:-------------:|:-------------:|:-------------:|
| `Provincias_datos.csv` |  Mortality rate in Spanish provinces (2020) - manually preprocessed | `BarplotsINEDeaths.Rmd`, `mortalityRatePerYear.Rmd`, `Spain_maps.Rmd`[links](https://github.com/Natpod/StatViz_INE_2020_Mortality) | [datos.gob.es](https://datos.gob.es/en/catalogo/ea0010587-defunciones-por-lugar-de-residencia-capitales-mes-de-la-defuncion-y-sexo-mnpd-identificador-api-t20-e301-defun-a2020-l0-20009-px)  | 
| `crudeMortality.csv` |   Crude mortality rate (per year)  |  `BarplotsINEDeaths.Rmd`, `mortalityRatePerYear.Rmd`, `Spain_maps.Rmd` [links](https://github.com/Natpod/StatViz_INE_2020_Mortality) | [INE](https://www.ine.es/jaxiT3/Tabla.htm?t=1411&L=0) |
| `mortalityRate.csv` | Mortality rate per year, age and sex |  `mortalityRatePerYear.Rmd` [links](https://github.com/Natpod/StatViz_INE_2020_Mortality) |
| `causas_muerte.csv` | Death causes from 2010 to 2020|  `mortalityRatePerYear.Rmd` [links](https://github.com/Natpod/StatViz_INE_2020_Mortality) | [INE](https://www.ine.es/jaxiT3/Tabla.htm?t=27150) | [datos.gob.es](https://datos.gob.es/en/catalogo/ea0010587-defunciones-por-causas-capitulos-sexo-y-provincia-ecm-identificador-api-49044) |
| `ccaa_provincia.csv` | File mapping Autonomous Community to Province - manually preprocessed |  `BarplotsINEDeaths.Rmd` [links](https://github.com/Natpod/StatViz_INE_2020_Mortality)| [INE](https://www.ine.es/daco/daco42/codmun/cod_ccaa_provincia.htm) |
| `CCAA_DR_Mortality_Population.csv` | Crude and per 100,000 Mortality rates per Autonomous Community in 2020 | `Spain_maps.Rmd`[link](https://github.com/Natpod/StatViz_INE_2020_Mortality/blob/main/Spain_maps.Rmd) | crafted in `BarplotsINEDeaths.Rmd` |

- **Mortality rate in Spanish provinces (2020)**: 
- **Crude mortality rate (per year)**: https://www.ine.es/jaxiT3/Tabla.htm?t=1411&L=0 
- **Mortality rate per year, age and sex**: https://www.ine.es/jaxiT3/Tabla.htm?t=27150
- **Death causes**: https://datos.gob.es/en/catalogo/ea0010587-defunciones-por-causas-capitulos-sexo-y-provincia-ecm-identificador-api-49044

- **File mapping Autonomous Community to Province**: https://www.ine.es/daco/daco42/codmun/cod_ccaa_provincia.htm
- **Crude and per 100,000 Mortality rates per Autonomous Community in 2020** : crafted in `BarplotsINEDeaths.Rmd`

In addition, there are three R markdown files that have been used to generate the visualizations for the assignment. 

- `BarplotsINEDeaths.Rmd`: script used to generate the barplot and boxplots charts. 
- `Spain_maps.Rmd`: script used to generate the Spain map plots containing information about the 2020 death rates by province and Autonomous Community. 
- `mortalityRatePerYear.Rmd`: script used to generate the time series plots for death rate and life expectancy in Spain as well as the death rate per age and sex in 2020 barplot. 

Dependencies : *mapSpain, reshape2, ggplot2, sf, dplyr, tidyr* should be preinstalled in an R environment
