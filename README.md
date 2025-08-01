# Testing-the-waters-new-relationships

### TTW_BIOLET.RMD - R markdown file with code to reproduce all analyses and figures

### 2021_TTW.csv - edgelist of social interactions (includes bird attributes)
#### columns 
sessionKEY - date_observerID

round.dt - rounded date time by five-minute timebin of observation

actor - bird ID

subject - receiver bird ID

dyadID - directed dyad; actor and subject ID 

behavior - interaction; NN (nearest neighbor); s2s (shoulder to shoulder contact); allop (allopreen); beak_touch); alloF (allofeed); cop (copulation)

actor.sex - sex of the actor 

actor.site - capture site of the actor

subject.sex - sex of the subject 

subject.site - capture site of the subject

n - count of interaction per timebin

date - date of interaction

undir.dyad - undirected dyad; actor and subject ID ordered alphabetically

new.dyad = T/F; whether dyad were stranger/familiar

opp.sex = T/F; whether dyad were different/same sex


### 2021_preperturbation dyad list.csv - list of birds during the experiment and all possible combinations of directed/undirected dyads (indcludes meta data)


#### columns

dyadID - directed dyad; actor and subject ID 

actor - actor bird ID 

subject - receiver bird ID

undir.dyad - undirected dyad; actor and subject ID ordered alphabetically

new.dyad = T/F; whether dyad were stranger/familiar

opp.sex = T/F; whether dyad were different/same sex


