# bonkers
### Segment 1 "Presentation" Requirements:
The selected topic is Marathon Race Results and phenomenon of "bonking".

Bonkers team member, Noah, is an avid runner and likes to obsess over his race finishing times. There is a lot of thought that goes into preparing for a race like a marathon which includes creating and sticking to a 4 month+ training plan, getting proper running attire, and deteriming a nutrtion strategy for optimal fueling on long runs and during the race itself. A race as long as a marathon (26.2 miles/~42.1km), requires that runners eat and drink something while they run in order to keep up their energy. Their bodies can store a lot of energy from eating extra carbohydrates in the days leading up to the race, but, physiologically, it won't last them the entire race. Thus, if the athlete doesn't replenish their body's stores of carbs, they'll experience a rapid decrease in energy levels known among marathoners as "hitting the wall", or more generically as "bonking". The result of hitting the wall is almost unanimously a drop in their running pace. This sometimes has runners reduced to walking until their bodies are able to naturally produce sugar sfficient for them to begin jogging again, or they a reach a water station and food station along the race course.

The data for this project is three years worth race results of the Boston Marathon pulled from kaggle.com (https://www.kaggle.com/datasets/rojour/boston-results?select=marathon_results_2015.csv) in text csv files. The data includes the age, gender, total race time, city/state/country of origin, and split times every 5k from the start of the race to the finish. 

Team Bonkers has chosen to analyze the topic of race results of the Boston Marathon in hopes of accurately predicting whether a participant will "hit the wall" between kilometers 30 and 35, the most common distance for racers to bonk.

✓ Selected topic
✓ Reason why they selected their topic
✓ Description of their source of data
✓ Questions they hope to answer with the data

### Segment 1 Database Info

The database requirements for segment 1 is as follows:
	✓ Sample data that mimics the expected final database structure or schema 
	✓ Draft machine learning module is connected to the provisional database

In order for database info to work properly, a SQL database named "bonkers" needs to exist, and the pgAdmin password needs to be included in a config.py file under the variable name db_password.

Data is exported from Jupyter Notebooks to the SQL database as expected, and the provisional database is set up to be connected to the learning machine module as necessary. 

Therefore, both database requirements have been met.