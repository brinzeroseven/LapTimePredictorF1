# F1 Lap time predictor
A machine learning project exploring F1 lap-time prediction using real race data from FastF1 API

Goal is to predict the next lap time from current race state, race information, and recent lap history, the "longer" term aim of using these predictions as part of an F1 race strategy machine learning model

### Models:
- Random forrest regressor: baseline (alongside just using previous lap as a prediction)
- ANN:
- LSTM: Sequential deep-learning model, more applicable to the situation as has a hidden state which can learn patterns overtime
- GRU: will learn

### Data:
Data is collected using FastF1, providing access to:

Lap times and timing data
Tyre compound and tyre life
Driver and circuit information
Race position
Track status / safety-car conditions
Weather conditions
Stint information

Current dataset focuses on all full race sessions (i.e not sprints) from 2022-2025
  -> plan to include 2018-2021 as well

### Some cool papers:
https://arno.uvt.nl/show.cgi?fid=180319
https://ieeexplore.ieee.org/document/11427134
https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1673148/full

### Future work:
- a lot
- Improve lstm
- Learn and implement GRUs
- Compare all the models
- Use predictions for a pit-stop strategy simulation
- Integrate into an eventual pit-wall project
