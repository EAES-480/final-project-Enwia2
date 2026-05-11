Project title
================
by Dylan Enwia

## Executive Summary

In this project titanite petrochronology and geochemistry from was examined from porphyry copper deposits (PCDS) in Sonora, Mexico. The main research question was: How does titanite age relate to temperature and rare earth element (REE) anomalies? Titanite is a useful mineral for this type of study because it can preserve both age information and geochemical information. U-Pb dating provides titanite crystallization ages, while Zr in titanite thermometry provides temperature estimates. In addition, europium (Eu) and crsium (Ce) anomalies can provide insight into magma evolution, redox conditions, and possible hydrothermal alteration. 

The dataset included 279 titanite analyses from five Sonora samples: Cuitaca, Cerro Verde, Cerro Saupchi, Puerto La Valdeza, and Suaqui Verde. The predictor variable used in the statistical models was Age_Ma, or titanite age in millions of years. The response variables were Temperature_C, Eu_Anomaly, Ce_Anomaly. The goal was to test whether titanite age could explain variation in these geochemical variables.

The exploratory plots showed that the samples tend to cluster by sample group. In the age versus temperature plot, some samples showed a slight increase in temperature with age, while others were flatter or slightly negative. This suggested that temperature may be partly related to age, but also strongly influenced by sample identity. The age versus Eu anomaly plot showed more scatter, with some samples having low Eu/Eu* values and others showing a wider range, including higher Eu anomaly values. This suggests that Eu anomaly may reflect different magma evolution histories or possible alteration effects. The age versus Ce anomaly plot showed the weakest visual trend. Most Ce anomaly values were more tightly grouped, and the trend lines were mostly flat, suggesting no clear visual relationship between Ce anomaly and age.

Linear regression was used to quantify these relationships. The temperature model showed a positive relationship with age, with a slope of 1.6921, meaning that for every 1 Ma increase in titanite age, temperature increased by about 1.69°C on average. This relationship was statistically significant, but the R² value was only 0.1083, meaning age explained about 10.8% of the temperature variation. The Eu anomaly model showed a negative relationship with age, with a slope of -0.0157, meaning Eu anomaly decreased by about 0.016 for every 1 Ma increase in age. This relationship was also statistically significant, but the R² value was 0.1173, meaning age explained only about 11.7% of the variation. The Ce anomaly model showed no meaningful relationship with age. Its slope was nearly zero, the confidence interval included zero, the p-value was 0.934, and the R² was 0.

Overall, the results show that titanite age is statistically related to temperature and Eu anomaly, but age alone does not explain most of the variation. This suggests that other factors, such as sample identity, magma composition, titanite generation, crystallization environment, and hydrothermal alteration, are likely important. Ce anomaly may still be useful as a redox proxy, but in this dataset it does not appear to change systematically with age.

An improvement for this project would be to include additional statistical tests, such as ANOVA, to test whether the samples are significantly different from one another. A multiple regression model including both Age_Ma and Sample_ID would also improve the analysis because the plots show clear sample clustering. Finally, I could have checked regression assumptions using residual plots and explained more clearly that significant p-values with low R² values mean that age has a detectable effect, but it is not the main control on the data.

## Presentation

Our presentation can be found [here](presentation/presentation.html).

## Data

Include a citation for your data here. See
<http://libraryguides.vu.edu.au/c.php?g=386501&p=4347840> for guidance
on proper citation for datasets. If you got your data off the web, make
sure to note the retrieval date.

## References

List any references here. You should, at a minimum, list your data
source.
