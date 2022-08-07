# Poisonous/Edible Mushroom Classification 

View the report [here](link.com)

## 
This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family (pp. 500-525). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. Source: Mushroom records drawn from The Audubon Society Field Guide to North American Mushrooms (1981). G. H. Lincoff (Pres.), New York: Alfred A. Knopf 

### Get the data here
The data comes from [Mushroom Data Set](https://www.kaggle.com/datasets/uciml/mushroom-classification). 

### Data Dictionary



| Attribute | Description | Values
|:---------|:-----------| :----------
Cap shape | The shape of the top part of the mushroom | bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
Cap surface | The surface of the top part of the mushroom|fibrous=f,grooves=g,scaly=y,smooth=s 
Cap color | The color of the top part of the mushroom |brown=n,buff=b,cinnamon=c,gray=g,green=r, pink=p,purple=u,red=e,white=w,yellow=y
Bruises | Whether the mushroom is bruised or broken | bruises=t,no=f 
Odor | How the mushroom smells | almond=a,anise=l,creosote=c,fishy=y,foul=f, musty=m,none=n,pungent=p,spicy=s 
Gill attachment | How the thin, papery structures that hang vertically under the cap. Responsible for producing spores.| attached=a,descending=d,free=f,notched=n 
Gill spacing | How closely spaced gills are | close=c,crowded=w,distant=d 
Gill size | Whether gills are narrow or broad |  broad=b,narrow=n 
Gill color | Color of gills |  black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e, white=w,yellow=y
Stalk shape | Whether the leg of mushroom is tapering or enlarging|  enlarging=e,tapering=t 
Stalk root | Shape of the stalk's root | bulbous=b,club=c,cup=u,equal=e, rhizomorphs=z,rooted=r,missing=? 
Stalk surface above ring | How the stalk's surface feels like above the ring | fibrous=f,scaly=y,silky=k,smooth=s 
Stalk surface below ring | How the stalk's surface feels like below the ring | fibrous=f,scaly=y,silky=k,smooth=s 
Stalk color above ring | The stalk's color above the ring | brown=n,buff=b,cinnamon=c,gray=g,orange=o, pink=p,red=e,white=w,yellow=y 
Stalk color below ring | The stalk's color below the ring | brown=n,buff=b,cinnamon=c,gray=g,orange=o, pink=p,red=e,white=w,yellow=y 
Veil type |The veil is a temporary structure (membranous tissue in universals) found on the fruiting bodies| partial=p,universal=u 
Veil color |Color of veil| brown=n,orange=o,white=w,yellow=y
Ring number | How many rings found on the mushroom's stalk | none=n,one=o,two=t 
Ring type | Shape of rings | cobwebby=c,evanescent=e,flaring=f,large=l, none=n,pendant=p,sheathing=s,zone=z 
Spore print color | Color of spores produced by gills which are used for reproduction | black=k,brown=n,buff=b,chocolate=h,green=r, orange=o,purple=u,white=w,yellow=y
Population | How scattered or grouped the mushrooms are | abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y
Habitat | Where mushroom populations are found | grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d 






### Goals
- Presenting findings gathered from analysis in a report format.
- Building a robust machine learning model capable of accuractely classifying poisonous and edible mushrooms.
- Interpreting classification results and model performance metrics. 

## Content 

```bash
./
│   README.md
│   
└───data/
│   │   mushrooms.csv
│   
└───presentation/
│   │   
│   
└───src/
    │   data_processing.ipynb
    	mushroom_classification.ipynb 
```

## Used Libraries
`pandas` 
`numpy` 
`matplotlib`
`seaborn`
`sklearn`
`janitor`

