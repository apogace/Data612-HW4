I decided to use two different datasets that were similar but different in exciting ways that show when being merged. 
The first dataset was a table of baseball players and their received awards and the year they received them. The other dataset is the same, but instead of baseball players, the reward recipients are baseball managers. 
First, I looked to see how many players and managers were in each dataset and see if any are duplicates. 
(there was one duplicate row, but it was dropped).
Then I used a one-to-one inner join by using the "playerID" field for both datasets for the join. 
The combined dataset only shows players who became managers and who won awards as players and managers. Nevertheless, this dataset is fascinating since one can see who had the best baseball careers on and off the field and the timeline of their accolades. 
Another exciting feature about the joined dataset is that if duplicate players are listed in the dataset, either the entry won multiple awards as a player or a manager, showing the individual's career prestige. 
After the join, I changed some column names to reflect the meanings of the fields better.
Next, I counted how many values were missing in each column in the dataset.
Two of the fields had no values present, while two other fields had some missing values. 
I decided to drop the two columns with all null values, while the other missing values I changed to 0 since simply filling forward or backwards would not apply to different players/managers.
