# Pokemon Data
## Data Story
In the enchanting world of Pokémon, trainers and creatures coexisted harmoniously, embarking on quests to become Pokémon Masters by capturing and training diverse species. Within this data story, we delve into captivating insights and trends that unfold in the vast Pokémon universe.

## Data Correlation
I found out that the "Total" attribute of Pokémon has a strong positive correlation with both the attack and defense attributes. The correlation coefficients provided indicate the strength and direction of the relationship between the "Total" attribute and each specific attribute.

In this case, a correlation coefficient of 0.73 between the "Total" attribute and attack attribute suggests a relatively strong positive relationship. Similarly, a correlation coefficient of 0.72 between the "Total" attribute and sp.attack (special attack) as well as sp.defense (special defense) attributes also indicates a strong positive relationship.

However, the correlation coefficient of 0.64 between the "Total" attribute and defense attribute suggests a slightly weaker positive relationship compared to the other attributes.

Overall, these correlations suggest that as the "Total" attribute of a Pokémon increases, there tends to be a corresponding increase in the attack, special attack, and special defense attributes. The defense attribute, while still positively correlated, may have a slightly weaker relationship with the "Total" attribute.

## How speed of Pokemon relates to various base factors?
Some insights that we can get from this  are:

- Attack: A pokemon's attack capacity slightly depends on its speed some of the pokemons like mewtwo mega mewtwo X have moderate speed but a good attack capacity, some are very fast yet lacking in their attack capacity.

- Defense: For a pokemon's defense speed is not that much required from the above Speed vs Defence plot that, pokemon's which are slower possess more defense capacity. e.g Eternatus Eternamax has high defense of 250 but low speed of 130.
- HitPoint: the hitpoint of a pokemon highly affects its speed from the speed vs HP plot, pokemons with high HP possess less speed e.g Blissey with high HP of 255 has a speed of 55.

## The most wide spread types of pokemon
The most commonly found type of Pokémon is Water type in Type1, while Flying type is the most prevalent in Type2. It should be noted that since Type2 is an additional type, many Pokémon do not have a Type2 and therefore the prevalence of this type may be lower compared to Type1.

## The Least Spread Type of Pokemon
The least commonly found types of Pokémon are Flying type in Type1 and Bug type in Type2. It is interesting to note that although there are more Pokémon with Flying type as their Type2, the Flying type has the fewest number of Pokémon in Type1.

## The Strongest Pokemon
Comparing all the base strengths,we have Eternatus Eternamax at highest strength,followed by mewtwo mega mewtwo X. To determine the strongest Pokemon, we summed up the base statistics for each species. While our metric approached Pokemon strength objectively as possible, in the end, it may not be meaningful to all players.
Therefore, the player's selection of moves, attack and defense points during the battle is ultimately a bigger factor in determining success than the strength of the Pokemon chosen. And hence the developers have made Pokemon a game that is more than simply optimizing statistics and strength, but is a tactical and personal experience.

##  Which Pokemon is the Weakest
Based on the plot above, we can observe that Wishiwashi solo form has the lowest base strength, followed by Sunkern. To identify the strongest Pokémon, we calculated the total base statistics for each species.

When creating this Pokémon data story, we took into account the essential elements and aspects that make the franchise captivating and beloved by fans. With this dataset, our aim was to create a resource that would assist Pokémon enthusiasts in identifying the best Pokémon with exceptional abilities, while also appealing to fans of the Pokémon cartoon and game.

- Understanding the Pokémon Universe: To begin, we immersed ourselves in the Pokémon franchise, delving into its history, gameplay mechanics, and various forms of media. This allowed us to grasp the context and significance of the different data points.
- Defining the Story's Focus: We chose to center our data story around the theme of battle strategy. This exploration involved analyzing Pokémon types, strengths, and individual powers.
- Data Analysis and Visualization: We conducted a thorough analysis of the given data, identifying intriguing patterns and insights. To effectively communicate these findings, we utilized data visualization tools.
- Visual Design: Our visual designs were carefully crafted to be visually appealing and informative, supporting the narrative of our data story. We employed appropriate charts, graphs, and images to effectively convey the data. Additionally, we considered the use of colors and layouts to enhance the storytelling experience.
- Concluding Insights: We highlighted the key insights and takeaways from our data analysis, emphasizing interesting patterns and correlations discovered during our exploration. These insights contribute to a deeper understanding of the Pokémon universe.
By following these steps, we aimed to create a data story that would not only inform and engage Pokémon fans but also provide valuable insights into the Pokémon universe.

## Algorithms / Libraries used for the Visualization
- pandas 
- Numpy
- seaborn 
- pyplot 

## Screen Recording of Visualization
(https://www.loom.com/share/ea3bd92f98924a638421e81cb70ffe5e?sid=b009de8a-843d-4c7a-a43d-951341073d53)
## Conclusion
In summary, the Pokémon franchise has captivated a global audience with its expansive universe of creatures, trainers, and exciting journeys. Through our analysis of Pokémon data, we have uncovered intriguing insights and trends that illuminate various aspects of this adored franchise. By examining the distribution of Pokémon types, we have identified the most common and rarest types, which can aid trainers in devising effective team strategies and anticipating the strengths and weaknesses of different types. Our examination of Pokémon attributes and characteristics has provided valuable insights into power dynamics and battle strategies. By comparing these attributes across types, trainers can make well-informed decisions regarding team composition and combat tactics. This data story has deepened our understanding of the Pokémon universe and its profound impact on fans worldwide. Whether you are an ardent Pokémon trainer or simply curious about the franchise, delving into the data behind Pokémon offers captivating insights and fosters a greater appreciation for this cherished world of creatures and adventure.
