# ARSET training at Fort Collins

## 3/5
### monday half day

#### individuals short background
cindy - positino in the eco group

amber - drought in navajo

brian miller - north science cliamte center

Lidnesy - NCSC masters student: science communication in specific situtations

robin: NCSC director

Yuki: argon nl, natural resource RS, mongoose in japan; maintaining habitat

Muleken: EPA watershed modeling; endangered fish in kansas

Nanette: denver zoon; gis connectivity, vultures in mongolia

Rodger: CSU cra - air quality modeling; snowpack, air quality and human/ecological health

tony: GIS UFW carsbad distract; habitat evaluation plans;

carl bowen; NPS vegetation modeling, snowpack management valles caldera ,

brian: nature conservaty; spatial scientsit; long billed bird.

tammy: NPS, veg mapping harmony&lemey

Michelle: World wildlife; changes in mangroves

Danielle: brox zoo; wildlife conservation; climate changes effects of bys - salty wetlands

MIchelle Vershez; gypsum; nurse. wildlife urban interface fire

Yong : tree regeneration after big fires, fire regime change in climate  

Ryan: WWF, ag supply chain, ag area response to climate change

Mona: conservation ecologist - species in the SE, induced species

gregory ---; NPS research ecologist, works alot with brian miller

#### General info
GAP was combined with landfire for a seemless veg layer, most imagery is from 1999-2001
- landfire has a historical dataset
- gap is more a recent classification scheme.

*NASA spatial extent limit*

there is a non compete clause where NASA can not go lower then 30m spatial res.

fort morgan area might have lidar data for the courses. THere is a 1m dem for that region, I just dont know how far off the river it extends

**jeff morsett**
expanding conservation horizons: setting vulnerability assessment in conservation


**exersice 1**
the gap analysis tool allows you to select land cover are various group levels. 4 degrees of specificity

**Helen**
climate data and projections
 - how to deal with a netcdf file? can check in with helen over the course of the week

 - identify the key climate drivers of the system, that is what should be focused on.
 - gridded data is most impacted by topographic conditions because that is where climate changes the most
 - interpolations are generally based on the average elevation data.
 - GCM are often biased corrected and downscaled
 - patterns at broad spatial scale and match to finer scales and know locations
 - prism data is not really appropriate for trend analysis because of variability in inputs over time
 - the Maurer data set would be more appropriate
 - use GCM to inform parameters of a sensitivity analysis;
 - not recommend to ensemble the climate data first; that is don't take the mean of multiple models and use that. It's better to run a sensitivity analysis across
 - to conduct the sensitivity analysis it can be as simple as adding a +1 +2 +3 degrees across all the data
  *this is similar to the delta method, where the known distribution is shift proportionally*
 - **statistical downscaling is not meant to improve the signal of change**
 - even if it does change it is hard to know if those changes are accurately a plus.
 - **dynamic downscaling using local observed data can be helpful**

 - Water Balance; Potential Evapotransparation (PET) is a climate variable
  - (PET) is built on: temperature, wind, rain, precipitation
  - actual evapotranspration has to be less then potential.
  - Really against the kitchen sink approach, you need to define what is important


## 3/6/2016

### risk framework
[Exposure] + [Sensitivity] = [Potential Impact] - [Adaptive Capability] = Vulnerability

### scenario planning
**Brian Miller**

scenario planning is the attempt to account for uncertainty
 - scenarios are ranges of plausible futures, they are stories of what could be.  

Rowland E. paper in slide details the scenario planning process
- scoping and preparation
- creating scenarios
- applying scenarios to predict impact

**creating scenarios**
start with critical forces: high impact and high uncertainty
define two - three and plot them as an axis with details and names

**good scenarios**
- plausible
- challenging/provocative
- relevant
- different from one another
- good and bad parts
- defining winners and losers
- plot lines

I really like this idea of story telling in science it is nice to hear how much of a part it is in this very specific science, makes me more and more interested in writing and blending those features

**applying scenarios**
- scenario implications: indirect effects
- management response: thought exercises of response; aligning goals and action

*NPS has a scenario planning product that is a little more approachable*
really promote the imaginative aspect of the scenario planning. LEt go of the day to day and pretend

### Southwestern South Dakota
mostly grasslands - relationships between; bison, prairie dogs, ferret
ridge road is over the easily erodible

*climate Scenarios*
spring precip(apr,may,june)
grow season onset (temperature threshold)
Heavy precipitation

Limiting the number of models you can use
- 4 models is pretty much the sweet spot. There is a limit of what the individuals can understand.

Plot of model prediction against memorable past event years  
,
extreme precip is tough because it is built from point based data, so the interpolation results in
- less extreme events
- more days with lower rain events
- climatologist advise: speak about the 95 percentile of the rain event distribution rather then the very far end.
this is really due to the convective character of thunderstorms

Create the summarys of all scenarios on a single page

uncertainty in models appears in the next 50 years, uncertainty from Global emission plans comes into play at 100 years or so

**peter schrtws** quote on scenario planning


### management part 2



## 3/7/2018
### Species Distribution Modeling

the habitat modeling framework takes geographic information regarding the distribution of presence or absences point into environmental space represented by variables, and projects that back to geographic space

**assumptions of habitat modelling**
- species are in equilibrium with the environment
- location data are spatial unbiases
- predictor variables capture constraints on species distributions
- the mathamatical relationships are acurate
- presence of a species implies that it can bread and survive in those locations

### SAHM
You can drag your model runs on top of current model to highlight the change in the features

- Template layer
No data cell will carry through the analysis,so you need to ensure that they can

- predictors
no more then 1 predictor for 10 locations

- calibration plots
If the features falls within the 0.5 line, you can say that your model is representative of probability of finding that species at that location if not it is just a relative relationship

- variable importance
done by switching the presence and absence for a specific predictor and determines how much that influences the values

- MESS Map
Shows area of extrapolation,

## 3/8/2018
### state transition modeling
