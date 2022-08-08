Example one: Valubale varriables for housing market investments in aarhus 

```{r}
install.packages("leaflet")
require(leaflet) 
```

```{r}
##Adding an interactive map to your markdown using leaflet56.16992908061329, 9.346352777934538
m <-   addMarkers(addTiles(leaflet()),lng = 9.346352777934538, lat = 56.16992908061329, popup = "Where we are right now!")
  
m  
```
