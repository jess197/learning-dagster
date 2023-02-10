![Dagster Logo](/img/dagster-logo.png "Dagster logo")


### Studying about Dagster 
  - Dagster takes care of the whole end to end pipeline 
  - It's for Data Engineers who want to guarantee quality data over the pipeline. 
  - And many more...
  - Why Dagster? This article is good: [Who, What, and Why DAGSTER!](https://ajithshetty28.medium.com/who-what-and-why-dagster-c97f8c2335b1)
### Installing Dagster
Take this [Install Guide](https://docs.dagster.io/getting-started/install)
Tip if helps you:
 I had a problem trying to run dagster in Macbook M1 that was :

##### Error: 
``` Corruption of free object 0x15164f700: msizes 8/7 disagree python3.8(49407,0x1f4b06500) malloc: *** set a breakpoint in malloc_error_break to debug [1]    49407 abort      DAGSTER_HOME=~/.dagster dagit```

##### Resolution: 
   Put it in your 'User settings.json' in Vscode ``` "terminal.integrated.env.osx": {   "MallocNanoZone": "1",} ```

### Running Dagster 
- Just run ``` dagit -f hello-dagster.py ```

#### What is better for you Airflow or Dagster?
Dagster takes a radically different approach to data orchestration than other tools
[Dagster vs Airflow](https://dagster.io/blog/dagster-airflow)

This Study is based on getting started from Dagster: 
[Getting Started with Hello Dagster](https://docs.dagster.io/getting-started/hello-dagster)

- It's a simple test getting the TOP 10 storys from hacker news and running into dagster. 

#### Doubts or Suggestions? 
You can reach me via my social medias that are on my profile page or enter in Dagster community :) 
[Jess's Profile](https://github.com/jess197/jess197)
[Dagster Community](https://dagster.io/community)