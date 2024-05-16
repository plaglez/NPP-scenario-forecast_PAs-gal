# NPP-scenario-forecast_PAs-gal
Lago-González, Pedro; Acuña Alonso, Carolina; Álvarez, Xana

## **Description**
The ecosystem Net Primary Productivity (NPP) can be used as quantification of its carbon absorption. This dataset is is the result of applying Gradient Boosting Regression Trees to forecast this variable under a bunch of different set up scenarios. The model was applied in four differentiated Protected Areas of Galicia (NW Spain), namely, the Central Massif, the Sil Canyons, the Fragas do EUME SCI and the Tambre River corridor. The model was trained with historical data from 2003 to 2021 (scenario 1). Then it was applied to data from climatic projections based on the SSP2-4.5 and SSP5-8.5 (scenario 2 and 3, respectively) between the years 2026 to 2049. For each, the NPP were forecasted for different proposed land uses, which consisted in keeping it constant from the last historical sample (labelled as "NPP"), increasing forestall areas in a 70% (labelled as "NPP_scx_forest"* ) and increasing agricultural in a 70% (labelled as "NPP_scx_agri"*). *x here represent the scenario label (i.e. 1, 2, 3).

### **Variables**

|Variable|Description|Units          |
|--------|-----------|---------------|
|x       |Longitude  |Decimal degrees|
|y       |Latitude   |Decimal degrees|
|year    |Time       |Years          |
|t2m     |Annual Mean superficial air temperature|ºC|
|t_amplitude|Thermal diurnal range|ºC|
|isothermality|Percentage of the temperature diurnal range explaining the temperature annual range|%|
|t_season|Temperature seasonality (sd*100)|ºC|
|max warm|Maximal temperature of the warmest month|ºC|
|min_cold|Minimal temperature of the coldest month|ºC|
|Q3_temperature|Mean temperature of the warmest quarter|ºC|
|Q1_temperature|Mean temperature of the coldest quarter|ºC|
|tp|Total annual precipitation|mm|
|prec_wet|Precipitation of the wettest month|mm|
|prec_dri|precipitation of the driest month|mm|
|prec_CV|Precipitation seasonality (coefficient of variation)|%|
|Q1_prec|Precipitation of the wettest quarter|mm|
|Q3_prec|Precipitation of the driest quarter|mm|
|d2m.Q1|Mean dewpoint temperature of the 1st quarter|ºC|
|pev.Q1|Mean potential evaporation of the 1st quarter|mm|
|slhf.Q1|Mean surface latent heat flux of the 1st quarter|J m<sup>-2|
|sshf.Q1|Mean surface sensible heat flux of the 1st quarter|J m<sup>-2|
|SW.Q1|Mean shortwave radiation of the 1st quarter|J m<sup>-2|
|RH.Q1|Mean relative humidity of the 1st quarter|%|
|d2m.Q2|Mean dewpoint temperature of the 2nd quarter|ºC|
|pev.Q2|Mean potential evaporation of the 2nd quarter|mm|
|slhf.Q2|Mean surface latent heat flux of the 2nd quarter|J m<sup>-2|
|sshf.Q2|Mean surface sensible heat flux of the 2nd quarter|J m<sup>-2|
|SW.Q2|Mean shortwave radiation of the 2nd quarter|J m<sup>-2|
|RH.Q2|Mean relative humidity of the 2nd quarter|%|
|d2m.Q3|Mean dewpoint temperature of the 3rd quarter|ºC|
|pev.Q3|Mean potential evaporation of the 3rd quarter|mm|
|slhf.Q3|Mean surface latent heat flux of the 3rd quarter|J m<sup>-2|
|sshf.Q3|Mean surface sensible heat flux of the 3rd quarter|J m<sup>-2|
|SW.Q3|Mean shortwave radiation of the 3rd quarter|J m<sup>-2|
|RH.Q3|Mean relative humidity of the 3rd quarter|%|
|d2m.Q4|Mean dewpoint temperature of the 4th quarter|ºC|
|pev.Q4|Mean potential evaporation of the 4th quarter|mm|
|slhf.Q4|Mean surface latent heat flux of the 4th quarter|J m<sup>-2|
|sshf.Q4|Mean surface sensible heat flux of the 4th quarter|J m<sup>-2|
|SW.Q4|Mean shortwave radiation of the 4th quarter|J m<sup>-2|
|RH.Q4|Mean relative humidity of the 4th quarter|%|
|LULC|Land Use|Classification**|
|DEM|Digital Elevation Model|m.a.s.l.|
|NPP|(Forecasted) net primary productivity of the unmodified land use|kgC m<sup>-2|
|NPP_scx_forest***|Forecasted/Hindcasted net primary productivity of the predominantly forestall land use|kgC m<sup>-2|
|NPP_scx_agri***|Forecasted/Hindcasted net primary productivity of the predominantly agricultural land use|kgC m<sup>-2|

```
**Land uses codification
  110: Agricultural
  120: Forestall
  130: Mining and quarrying
  200: Secondary production
  410: Transport networks
  500: Residential use
  620: Abandoned areas
  631: Land areas not in other ecomnomic use
  632: Water areas not in other economic use
```
***For the variables *NPP_scx_forest* and *NPP_scx_agri*, change x for the climatic scenario label (i.e. 1 for historical, 2 for SSP2-4.5 and 3 for SSP5-8.5).

## Download
The dataset can be downloaded at OneDrive


## Acknowledgements
This research was funded by Grant TED2021-130241A-I00 funded by MCIN/AEI/ 10.13039/501100011033 and by the European Union NextGenerationEU/PRTR (X. Álvarez). This research was partially funded by the Conselleira de Educación, Universidade e Formación Profesional, Xunta de Galicia, Spain, under project GPC-ED431B 2022/12 (P. Lago-González) and C. Acuña-Alonso thanks the Postdoctoral Program of Xunta de Galicia (ED481B-2023-042).
