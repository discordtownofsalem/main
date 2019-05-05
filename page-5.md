
## Goal

Our goal is to create a discord bot that seamlessly integrates with an existing discord server to create a version of the popular party game ‘Mafia’ or its video-game adaptation ‘Town of Salem’.

### What is town of salem?

In Town of Salem, each player is privately assigned a role in the game with a specific goal, some of which possess unique abilities. Each player typically has an allegiance either to the townsfolk or the mafia. Each night, players with abilities may use them and the mafia decide which townsfolk they wish to murder.  During the day, each player then votes on a person to hang, with the goal of the townsfolk being to determine who is a member of the mafia and hang them for their crimes.

### Why discord?

There are 25 million Discord users worldwide, most of whom are avid gamers. By utilizing this popular social media platform, we can more easily bring our product to our target audience of young people between the ages of 14 and 35 years old and make it convenient for them to use. As many of them already possess accounts and servers of their own, all it would take would be for them to add our bot to their server and they can instantly create a curated and engaging gaming experience.
The online platform and persistent nature of the discord server will also allow us to create unique versions of the experience by adjusting the timeline of the game to take place over a longer period than the traditional versions, if they so choose. Rather than the typical experience which takes place over the course of about an hour (often less), our version could take place over days or even weeks.

### What will the project entail?

The project will require an intermediate understanding of the node.js programming language, along with a basic grasp of game design concepts.
The project may also utilise some creative writing, art, audio and/or video assets to help enhance the user experience.

### How will it work?

Upon adding our bot to the server, the bot would need to begin by prompting players with some basic commands that would allow players the ability to begin or cancel an instance of the game.
Upon beginning a game, if using this as a starting feature, the bot would need to prompt the users to determine which of a set list of time-frames over which the game will take place.
After that, it would need to determine which users in the server will be participating in the game and add them to an array.
Then, the game will need to randomly assign roles to each of the players and store their role data to determine their allegiance and abilities.
Some starting example roles are:
- The Doctor, who is capable of choosing one person per night they wish to prevent from dying.
- The Sheriff, who can choose someone to investigate at night, and thus determine if they are either a mafioso or a member of the townsfolk.
- The Framer, who, at night, can choose to make anyone appear guilty to the Sheriff.
- The Jester, whose has no allegiance but instead has the goal of trying to get themselves lynched.
The bot should be able to implement these features through private message and public posts to the server as the players vote and/or communicate the actions they wish to take.
As private messaging is an existing feature on discord, it will allow players to both interact with the bot as well as covertly discuss the game with one another, thus enhancing the subterfuge inherent in the game’s concept.
If a player is either hanged or killed by the mafia, the game will be able mute them in the discord channel so that they cannot publicly interact with the game.
After our prototyping, the group will be able to iterate on the product by adding new features such as alternate timeframes, more roles, allegiances, and any other features we feel may enhance the experience.


### How will the team accomplish its goals?

By distributing the work amongst the group, we will be able to maximize productivity and limit interference between group members. We can isolate content writing, asset generation/curation, coding and code review to give each member a clearly defined role. This approach combined with regular meetings and peer review should enable us to achieve our goals.


