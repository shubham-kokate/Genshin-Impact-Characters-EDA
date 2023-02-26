# Genshin-Impact-Characters-EDA
Genshin Impact is a MMORPG that is widely played for its great open world experience which you can take in with a great variety of characters.

This repositopry is just a fun EDA on how Genshin Impact Characters are divided among roles, element, weapon choices, ascension and how these different aspects affect their statistics such as BaseHP, BaseATK, BaseDEF, etc.

Dataset Used: <a href="https://www.kaggle.com/datasets/libbiebonevich/genshin-impact-stats">Genshin-Impact-Stats</a> by <a href="https://www.kaggle.com/libbiebonevich">libbie bonevich</a> on Kaggle

Data Summary:
- Character : name of the character (65 Unique Characters)
- Level : all levels seen for that character (1, 10, 20, and so on till 90)
- Rarity : how rare the character is (4 and 5 are the only available options)
- Element : the element associated with the character (7 Unique Elements)
- Weapon : the weapon weilded by the character (5 Unique Weapons)
- Role : the role associated with the character (4 Unique Roles)
- Ascension : the ascension available for the character
- BASEHP : the baseHP of the character at that level
- BASEATK : the baseATK of the character at that level
- BASEDEF : the baseDEF of the character at that level

Goals for Analysis:
- Visualization of Character Distribution by Levels, Roles(DPS, Support, etc.), Elements(Pyro, Cryo, etc.) and Weapon Choices(Claymore, Sword, Bow, etc.)
- In-depth character statistics by Roles and Visulization of how BASESTATS(ATK, DEF and HP) vary by Elements and Weapon Choices.
- Funnel Visualization of Ascensions possible according to Roles and Elements and how they affect BASESTATS
