### Capstone_GameplayFeatures

Simon Anderson

#### Executive summary

Objective: Identify the specific in-game mechanics that drive that retention.

What We Did: We processed raw player telemetry data and trained a Random Forest machine learning model to uncover the hidden patterns in player behavior.

What We Found: * Our initial model was highly accurate (98%) but relied too heavily on "Total Time Played." Because simply telling players to "play longer" isn't a usable design strategy, we removed time-based metrics to find the root cause of that engagement.

By forcing the model to look only at actionable gameplay, we discovered that Quest Starts and In-Game Economy (Gold/Items) are the true drivers of player retention.

#### Rationale
Finding out what actually drives retention is incredibly import for generating new content in the game making the wrong content can adversely affect game health

#### Research Question
The question I am trying to answer is what parts of the game actually boost retention. 

#### Data Sources
We processed raw player telemetry data from the game collected over the last few years of the games life

#### Methodology
What methods are you using to answer the question?
I trained a Random Forest machine learning model to help find the features that are best suited to driving retention.


#### Results
Recommendation: Game design and product teams should shift focus away from trying to artificially inflate session lengths. Instead, prioritize optimizing the early-game funnel to remove friction and encourage new players to start their first few quests and interact with the economy as quickly as possible.

#### Next steps
What suggestions do you have for next steps?
The next steps are to include more features or columns of data. It currently has about 20 but could be expanded to capture many more aspects of the game. 
After that I would recommend more tuning of the model to see if it can be improved. 

#### Outline of project

https://github.com/simes007us/Capstone_GameplayFeatures/blob/main/Capstone.ipynb

##### Contact and Further Information

Simon Anderson
simes007us@gmail.com
