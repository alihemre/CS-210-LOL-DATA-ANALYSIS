# CS-210-LOL-DATA-ANALYSIS
COURSE PROJECT
CS210 - COURSE PROJECT: League Of Legends Match Analysis
I used my own League of Legends (LoL) match dataset for analysis. LoL, the most popular MOBA game, features a 5v5 format where you have four teammates and five opponents. The game's ranking system matches you with players of the same rank. With over 100 champions and five roles, LoL offers a diverse playing experience.

To create my dataset, I utilized LoL's official API documentation. There are typically 2-3 steps to retrieve match data. First, an API key is required for access, which must be regenerated every 24 hours. After regenerating the API key, one needs to acquire their match IDs using their puuid code, an additional security measure. A maximum of 100 matches can be requested per query. Once the match IDs are obtained, each match ID must be sent individually to retrieve detailed match data.

Since the data contains several entities, I selected only the necessary elements for my analysis. I used Excel to compile my dataset. The final step involved merging my match data with a champion dataset from another website in collaboration with LoL. This step was crucial as it allowed me to analyze my dataset in relation to the champions I played.

For my dataset creation, I used two key resources: the LoL Official API website (https://developer.riotgames.com) and the League of Legends Fandom page (https://leagueoflegends.fandom.com/wiki/List_of_champions), which provides detailed information on champions and is also an official subdomain of the LoL website. Below, you can find the set of features provided in the dataset:

IsWin: Indicates whether I won the match or not.
Duration: The length of the match in minutes.
KDA: Represents your game score, calculated using the formula (Kills + Assists) / Deaths.
Role: Your lane in the match.
ChampionName: The champion I played with.
Earn Gold: The total amount of gold earned during the game.
Earn Gold Per Minute: The rate of gold earned, calculated by dividing total gold by match duration.
Total Minions Killed: Minions are NPC soldiers. Killing them grants gold and experience.
Vision Score: Reflects usage and destruction of wards, items that provide vision for your team.
Vision Score Per Minute: Calculated by dividing the vision score by the match duration.
Baron Kills: A numerical value representing the number of Barons killed by your team.
Dragon Kills: A numerical value representing the number of Dragons killed by your team.
Total Pings: A numerical value indicating the level of communication in the game.
Damage Per Minute: The amount of damage dealt to enemies per minute throughout the match, using skills and normal attacks.
Attack Range Of Champion: The maximum distance from which your champion can attack enemies.
Adaptive Type: Specifies the damage type of your champion.
Class Of Champion: Determines the play style of your champion.
Difficulty Rate: Ranges from 1 to 3, with 3 being the most complicated champion to play with and 1 being the easiest.                                                                                        Based on my data analysis, there is a strong positive correlation between team objectives achieved and the frequency of communication among teammates, and these factors significantly contribute to an increase in my win rate. Other data points do not appear to be as critical in enhancing win rate. All the data utilized in my presentation were sourced from a Jupyter Notebook.
