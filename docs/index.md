# Phase 1 - Design Phase (25.02.2026 - )
## Scope
The scope of this project is to have a substantially large database of Pokèmon for me to learn from. I shall allow for manual and automatic entries to speed up the process of entering data. I would like to add minigames to this project to test my memory and help me learn more about Pokèmon.

This will also aid me in learning HTML, CSS and JS, as well as a new workflow to me called Django, which is a framework that makes website-database interactivity easy. I have always struggled with HTML and CSS as they are not procedural programming languages and focus more on the frontend of projects which I tend to avoid.

I would like to also keep a through documentation of this project to assist me in idea generation, problems, fixes and to look back on where I started.

## What information will be held
After going through the official [Pokèdex](https://www.pokemon.com/uk/pokedex), information required for each Pokèmon are:
- Name
- ID
- Height
- Category
- Weight
- Abilities
- Gender (Male/Female)
- Type
- Weaknesses

| Parameters           | Description                                                                                                                                 |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Name                 | The name of the Pokèmon.                                                                                                                    |
| ID                   | An ID assigned to each Pokèmon, I will be using the ID that is in the official Pokèdex.                                                     |
| Height               | The height of the Pokèmon in meters.                                                                                                        |
| Category             | A classification of the Pokèmon, does change between evolutions.                                                                            |
| Weight               | The weight of the Pokèmon in kilograms.                                                                                                     |
| Abilities            | Abilities are a possibly passive trait for the Pokèmon. For example, doing more damage when health is low. These are shared across Pokèmon. |
| Gender               | Some Pokèmon have a unknown gender, are only one gender, or have both genders. There are also gender ratios.                                |
| Type                 | A further classification of the Pokèmon, depicting the affect it gives off.                                                                 |
| Weaknesses           | What the Pokèmon is weak to.                                                                                                                |
| Generation           | Which generation the Pokèmon was introduced.                                                                                                |
| Evolves from         | What this Pokèmon has evolved from.                                                                                                         |
| Evolves to           | What this Pokèmon evolves to.                                                                                                               |
| Base HP              | Thebase HP of the Pokèmon.                                                                                                                  |
| Base attack          | The base attack of the Pokèmon.                                                                                                             |
| Base defense         | The base defense of the Pokèmon.                                                                                                            |
| Base special attack  | The base special attack of the Pokèmon.                                                                                                     |
| Base special defense | The base special defense of the Pokèmon.                                                                                                    |
| Base speed           | The base speed of the Pokèmon.                                                                                                              |


After further research, the type of Pokèmon dictates what it is weak to so all fire type Pokèmon are weak to ground, Rock, and water for example. So each Pokèmon will not have to store its weaknesses, only the type.
