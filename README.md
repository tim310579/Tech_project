# Tech_project

## There are total 9 Datasets: 

## FordA, FordB, SCP1, SCP2, Motor, A_DeviceMotion_data, basketball, ADL, Falls

### For SPN's execution step

1. `python3 snippet_extractor.py [Dataset_name]` e.g., `python3 snippet_extractor.py FordA`

2. `python3 sel_predictor.py [Dataset_name]` e.g., `python3 sel_predictor.py FordA`

3. `python3 sel_evaluation.py [Dataset_name]` e.g., `python3 sel_evaluation.py FordA`

### There is a script that can execute all steps in SPN, just type in command as below.

`./run.bash sel [Dataset_name]` e.g., `./run.bash sel FordA`

### If you want to run all datasets at once, type in this command.

`./run.bash sel ALL`

### If the models are saved, there is another script to do inference.

`./quick_run.bash sel [Dataset_name]` e.g., `./quick_run.bash sel FordA`

### Or inference all datasets at once, type in this command.

`./quick_run.bash sel ALL`

## 

### For KGNA's execution step

1. `python3 snippet_extractor.py [Dataset_name]` e.g., `python3 snippet_extractor.py FordA`

2. `python3 backbone_pretrainer.py [Dataset_name]` e.g., `python3 backbone_pretrainer.py FordA`

3. `python3 state_generator.py [Dataset_name]` e.g., `python3 state_generator.py FordA`

4. `python3 kgea_optimizer.py [Dataset_name]` e.g., `python3 kgea_optimizer.py FordA`

5. `python3 kgea_inference.py [Dataset_name]` e.g., `python3 kgea_inference.py FordA`

### There is a script that can execute all steps in KGNA, just type in command as below.

`./run.bash kgea [Dataset_name]` e.g., `./run.bash kgea FordA`

### If you want to run all datasets at once, type in this command.

`./run.bash kgea ALL`

### If the models are saved, there is another script to do inference.

`./quick_run.bash kgea [Dataset_name]` e.g., `./quick_run.bash kgea FordA`

### Or inference all datasets at once, type in this command.

`./quick_run.bash kgea ALL`
