# CS-210-LOL-DATA-ANALYSIS
COURSE PROJECT
CS210 - COURSE PROJECT: League Of Legends Match Analysis
I used my own League Of Legends match dataset. League Of Legends (LoL) is the most popular moba game. It's format is 5v5, you have 4 teammate and 5 oppenent. There is ranking system it matches the people same rank as you. There are over 100 champions and 5 roles in the game. I used LoL's official API documentation web site to create my dataset. There are 2-3 steps to get a match data. First you need a key to access API. You need to regenarate it every 24 hours. After you regenerate the API key, you have to get your own match Id's with your puuid code which is another security step. You can Max get 100 matches per request. After you get your match Ids. Send math your matchId one by one to take the detail of your match. There are several entities in data so I do not need some of them I get what I need. I use excel to create my dataset. The last step was joining my match data with champion dataset in another website with cooparete LoL. Because I will also analyse my dataset with which champion I play. I used 2 links to create my dataset. LoL Official API website:https://developer.riotgames.com and https://leagueoflegends.fandom.com/wiki/List_of_champions which contains details of champions (alsa Official website of Lol(It is subdomain))

Below, you can find all the set of features, provided in the dataset:

IsWin: I win the match or not.
Duration: How many minutes the match last.
KDA: How is your game score. Formula is (Kills+Assits)/Deaths.
Role: What is your lane in the match.
ChampionName: Which champion did I played with.
Earn Gold: How much gold did I earn for the entire game.
Earn Gold Per Minute: Divide earn gold to duration.
Total Minions Killed: Minion is a soldier which is a npc. When you farm them you earn gold and experience.
Vision Score: There is ward which is an item in the game. It provides vision to your team. It shows how many ward did you use and killed enemy ward.
Vision Score Per Minute: Divide vision socre to duration.
Baron Kills: A numerical value representing the number of barons by killed your team.
Dragon Kills: A numerical value representing the number of dragons by killed your team.
Total Pings: A numerical value indicating the instrumentalness of the song.
Damage Per Minute: You hit the enemies with your skills and normal attacks. It shows how many deamage did you deal per minute in entire match.
Attack Range Of Champion: There is a restricotion to your champion attack range. If the length between your enemy is more than your attack range you cannot attack to enemy.
Adaptive Type: It spesifies the demage type of your champion.
Class Of Champion: It determines the play style of your champion.
Diffucult Rate: It's value possible values are 1,2,3. 3 is the most complicated champion. 1 is easy to play.

Conclusion:
  According my data analysis, objectives taken by team and the number of communication times between my teammate have strong positive correlation between increasing my win rate. Other datas are not the crucial point to improve win rate. 
All data that I used in my presentation taken from jupyter notebook.
