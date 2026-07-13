# Pokemon-IF-Drafting-Lab
This program takes a list of pokemon and outputs all valid fusion combinations including pokemon head, pokemon tail, cost, typing, stats, abilities.

# Settings
- First row is for the settings
- FusionCost is the max total cost of fusions
- MaxPokemonCost is the max individual pokemon cost
- MinPokemonCost is the min individual pokemon cost
- Default: [FusionCost=24, MaxPokemonCost=18, MinPokemonCost=0]
# Example Input:
[FusionCost=10, MaxPokemonCost=, MinPokemonCost=]

PokemonName	DraftCost	Type1	Type2	HP	ATK	DEF	SPATK	SPDEF	SPEED	BST	Ability1	Ability2	HA

Bulbasaur	1	Grass	Poison	45	49	49	65	65	45	318	Overgrow		Chlorophyll

Ivysaur	2	Grass	Poison	60	62	63	80	80	60	405	Overgrow		Chlorophyll

# Example Output
Bulbasaur	Ivysaur	3	Grass/Poison	50	57	58	70	70	55	360	Overgrow, , Chlorophyll, Overgrow, , Chlorophyll
