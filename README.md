# Studying about Dagster 
    - Dagster takes care of the whole end to end pipeline 
    - It's for Data Engineers who want to guarantee quality data over the pipeline. 
    - And many more...
# Installing Dagster
[Install Guide](https://docs.dagster.io/getting-started/install)
I had a problem trying to run in Macbook M1 that was :

``` Corruption of free object 0x15164f700: msizes 8/7 disagree python3.8(49407,0x1f4b06500) malloc: *** set a breakpoint in malloc_error_break to debug [1]    49407 abort      DAGSTER_HOME=~/.dagster dagit```

Resolution: 
    Put it in your user settings json in Vscode ```"terminal.integrated.env.osx": {   "MallocNanoZone": "1",} ```
# Running Dagster 
- Just run ``` dagit -f hello-dagster.py ```