# citybikes-algorithm

> These algorithms, given the dataset of the user's unlocks,  
> its location, the time and the day of the week, try to predict  
> the station where the user will probably go.  

**Course:** Recognition theories and techniques  
**School:** University of Trento  
**Year:** 2° (actually, anticipated third year course) . 

### The features they use are:
- user's location
- time
- day of the week

### Datasets:
- one small (300 unlocks)
- one big (1134 unlocks)

### Datasets' informations:
- departure stations' names
- arrival stations' names
- release time
- release date
- duration of the trip

[ note: the dataset provided by the company that owns  
the service has only unlocks, not trips, that have to  
be computated, matching differents unlocks. Moreover,  
the unlocks history is incomplete. ]

### Other information (calculated):
- location of the stations
     - calculated via API
- day of the week
- arrival time

### Algorithms tried:
- Bayes
- KNN

### Others:
- polyfit
     - try to use bayes on a continuous scale, instead of discrete
