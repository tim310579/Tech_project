# Tech_project

## There are all 9 Datasets: 

## FordA, FordB, SCP1, SCP2, Motor, A_DeviceMotion_data, basketball, ADL, Falls

### For SPN's execution step

1. `python3 snippet_extractor.py [Dataset_name]` e.g., `python3 snippet_extractor.py FordA`

2. `python3 sel_predictor.py [Dataset_name]` e.g., `python3 sel_predictor.py FordA`

3. `python3 sel_evaluation.py [Dataset_name]` e.g., `python3 sel_evaluation.p FordA`

#### There is a script that can execute all steps in SPN, just type in command in terminal as below:

`./run.bash sel [Dataset_name]` e.g., `./run.bash sel FordA`

### If you want to run all datasets at once, type in this command:

`./run.bash sel ALL`

### If the models are saved, there is another script to do inference

`./quick_run.bash sel [Dataset_name]` e.g., `./quick_run.bash sel FordA`

### Or inference all datasets at once, type in this command:

`./quick_run.bash sel ALL`
