# Global sea surface temperature fluctuations

## Background on this CLIP

This infographic shows 35 years (1981-2016) of fluctuations in annual sea surface temperature across the globe.  The temperature range modelled, covers 0.5 degree centigrade, with blue tones at the lower end and yellow at the upper. A sharp increase in global sea surface temperature is noticeable towards the end of the data set.


## Data Sources

The CLIP uses the following datasets:
- [Level 4 Analysis Climate Data Record, version 2.1](https://catalogue.ceda.ac.uk/uuid/62c0f97b1eac4e0197a674870afe1ee6)
- yearly_global_sst_mean

## Data Preparation

The data for this infographic came from the yearly_global_mean measurements, which provide 35 years of observations.

To prepare the data, follow these steps:
- Open .csv file in an appropriate application (e.g. MS Excel) 
- Set number format of value cells to 2 decimal places, for simplicity.

## Creating Visualizations 

To recreate this visualization:
- Using appropriate software, create a 51 step colour ramp (e.g. #00adff to #fafa6e), to correspond with the 0.01 degree increments over the 0.51C temperature increase range observed in the dataset
- Programatically or manually create 35 vector shapes, representing each year of the dataset, with progressively increased height and width (e.g 10px), to form a mosaic
- Programatically or manually assign to the appropriate colour from your ramp to each progressive shape, according to the temperature value measured for that year
- In the example provided, the middle shape represents the year 1981 and the outer 2016, but feel free to experiment with placement, order and sizing as required.

## CREDITS & LICENSE
- Idea by: [INSTITUTION](https://climate.esa.int/)
- Processing Scripts by: [INSTITUTION](https://climate.esa.int/)
- Visualization by: [INSTITUTION](https://climate.esa.int/)

The code in this repository is published under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)
