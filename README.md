# BlizzardWarcraftAPI

![image](https://drive.google.com/uc?export=view&id=1bwLWgLTIHPy23sTfufMNV9NHhvQ4vQ1y)

BlizzardWarcraftAPI is a Python library designed to interact with the official World of Warcraft API provided by <a href="https://develop.battle.net/documentation/world-of-warcraft">Blizzard</a>. Although it is still a work in progress, active development is underway. It's important to note that this library is not an official Blizzard product, but rather the result of an independent developer's efforts.

BlizzardWarcraftAPI aims to provide a convenient and user-friendly interface for developers to access and utilize the wealth of data available through the World of Warcraft API. With this library, you can retrieve information about characters, items, quests, guilds, and more. It abstracts away the complexities of making API requests and handling responses, allowing developers to focus on building their applications or tools.

By leveraging Blizzard's official API, BlizzardWarcraftAPI ensures that the data obtained is accurate and up-to-date. As the library continues to evolve, additional features and enhancements will be added to expand its capabilities and improve its usability. Developers interested in utilizing the vast resources offered by the World of Warcraft API will find BlizzardWarcraftAPI to be a valuable tool in their projects.

# Installing
Install and update using <a href="https://pip.pypa.io/en/stable/getting-started/">pip</a>:
```shell
pip install BlizzardWarcraftAPI
```

# A Simple Example

```python
from BlizzardWarcraftAPI import BlizzardWarcraftAPI, BlizzardAuthToken

token = BlizzardAuthToken("ClientID", "ClientSecret").get()

warcraft = BlizzardWarcraftAPI(token, region, locale)
warcraft.get_AchievementCategoriesIndex
```

# [APIs](https://develop.battle.net/documentation/world-of-warcraft)

## [Game Data](https://develop.battle.net/documentation/world-of-warcraft/game-data-apis)

- [x] Achievement
- [x] Auction House
- [x] Connected Realm

## [Profile](https://develop.battle.net/documentation/world-of-warcraft/profile-apis)

- [x] Character Achievements
- [x] Character Appearance
- [x] Character Collections
- [x] Character Encounters
- [x] Character Equipment
- [x] Character Hunter Pets