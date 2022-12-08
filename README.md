## Determining Inaccessible Public Lands
### View html file of Jupyter Notebook <a href="https://htmlpreview.github.io/?https://github.com/notchintags/CornerCrossing/blob/master/html/CornerCrossing.html"> here </a>
### Motiviation
The motivation to provide this analysis stems from a recent corner crossing case (https://wyofile.com/ranch-owner-corner-crossing-damages-could-exceed-7m/). HuntScore is providing this analysis and code as a means to help promote solutions to making public land accessible. In particular, an incosequential amount of public land is either entirely surrounded by private land or requires access via corner hopping (a still legal gray area). Hopefully this analysis and code can be used as a starting point to prioritize access through either public or private initiative.

### Datasets
Public land datasets can be found at https://www.sciencebase.gov/catalog/item/62226321d34ee0c6b38b6be3 which comes from the PAD-US files, you can learn more about PAD-US dataset here, https://www.usgs.gov/programs/gap-analysis-project/science/pad-us-data-overview.

The roads dataset comes from USGS and The National Map. The dataset is here https://prd-tnm.s3.amazonaws.com/StagedProducts/Tran/Shape/TRAN_Wyoming_State_Shape.zip and you can learn more about the transportation dataset here https://www.sciencebase.gov/catalog/item/5a61c942e4b06e28e9c3bddc


### Potential Uses
Hopefully this notebook serves as an example of how to identify different access modes by using graph networks. In addition, the graph structure could be useful to weight potential access paths, where more than one exists, to provide access to the optimal amount of public land. 

While the legality of corner crossing works its way through Federal court, there could many uses depending on the outcome. If found legal with a narrow prescriptive ruling where persons crossing a corner must be certain of the corner, the analysis could be used to identify the largest tracts of public land that could be accessible through corner crossing and help prioritize the placement of visible survey corners along the access paths. On other hand, if corner crossing is found to be illegal unless consent is obtained by all bordering property owners, a private or public entity could work to negotiate access with private property owners corners by merging in a private landowner dataset to this one.