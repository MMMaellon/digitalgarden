---
{"dg-publish":true,"permalink":"/vrc-projects/rot-heart-s-pirate-curse/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true}
---

# RotHeart's Pirate Curse
You and our pirate crew have discovered the cursed treasure of the legendary Robby RotHeart. RotHeart's curse poison's sailors' hearts and turns them on their friends and fellow crewmates. Fortunately, you know a skilled Witch who can reverse the curse.

The entire ship makes a pact to throw any cursed sailors overboard and to take turns filling the role of *Captain* and *First Mate* until they can reach the Witch's island. By cycling the *Captain* and *First Mate*, the crew hopes to prevent the cursed crewmates from working together to overthrow the ship.

# Gameplay
At the start of every day, a new person becomes the *Captain* who then chooses a *First Mate*. The *First Mate* scouts the 3 randomly generated **routes** for the day and picks 2 to show the *Captain*. The *Captain* makes the final decision on the **route** to take which will be one of the following:
1. Spend the day fishing
	- Make no progress towards the Witch's Island, but collect Fish for 3 minutes.
	- 1 fish feeds 1 crewmate for 1 day
		- Eating fish doesn't prevent **scurvy**
		- Every time the number of fish hit 0, one random non-cursed crewmate dies of starvation
	- Dark spots appear in the water around the ship and each player must throw fishing lines to catch fish. Just like in Animal Crossing.
		- Dark spots are randomized and local only so cursed crewmates can pretend to fish and intentionally miss their fishing lines.
2. Sail through pirate-infested waters
	- Make progress towards the Witch's Island, but you have to fight another pirate ship
	- 2 Giant Health Bar appear - one for your ship, one for enemy ship
		- Enemy attacks at a constant rate, so your health will always deplete after 5 mins.
		- Your ship only attacks when someone loads a cannon. If you kill the enemy ship before your health runs out, you can end the encounter early.
	- Every time your ship gets shot, you lose some fish
	- At the end of the encounter a message appears
		- If the enemy pirates won, the message is "Enemy pirates made off with a portion of the treasure and XXX fish"
		- If you win, the message is "You vanquished the enemy pirates, but not before losing XXX fish"
	- NPC pirates jump onto your ship and shoot people which downs them for 10 seconds.
		- You have to shoot them back to kill them
3. Stop at a trading port
	- Make no progress towards the Witch's Island but you get to trade fish for **scurvy** meds
	- Captain chooses the amount of med packs to buy and has to lock in the amount before the crew votes to haggle.
	- Price for meds is randomized. It's between 5 and (5 * player count) fish for 1 med pack.
		- Players can vote to haggle two more times. Haggling randomizes the price again.
	- 1 med pack prevents **scurvy** for the entire crew for 1 day
		- When there's no med packs left, a random non-cursed crewmember is given **scurvy**.
		- Crewmates with **scurvy** spew gross particles everywhere and die in 2 days if they don't get more meds
4. Fight the Kraken
	- Make no progress towards the Witch's Island, and have to fight a giant tentacled monster
	- Basically the worst option
	- 2 Giant Health Bar appear - one for your ship, one for the kraken
		- Kraken attacks at a constant rate, so your health will always deplete after 5 mins.
		- Your ship only attacks when someone loads a cannon. If you kill the Kraken before your health runs out, you can end the encounter early.
	- Kraken randomly appears in a space around the ship and players have to load the correct cannon aimed at it to do damage
	- Whenever the Kraken isn't taking damage, it reaches a tentacle over the ship and knocks down a player for 10 seconds and steals some fish.
	- At the end of the encounter a message appears
		- If the enemy pirates won, the message is "The Kraken eventually left, stealing XXX fish"
		- If you win, the message is "You vanquished the Kraken, but not before it stole XXX fish"
5. Take a shortcut through a storm
	- Make 2 days worth of progress towards the Witch's Island, but have to battle a storm
	- Giant waves wash over the ship from all directions and everyone has to run around on the ship to avoid them
		- Every time a person is hit, they are downed for 10 seconds and lose 1 fish

After every day, the captain has to nominate someone to vote off of the ship. The crew takes a vote and if it passes, that person has to walk the plank. The crew can also hit a **mutiny** button that votes the *Captain* to walk the plank. A vote has to happen though.
 - When someone walks the plank, they are teleported to the plank and prevent from leaving by an invisible collider. They can either choose to walk off, or the captain can pull a lever which makes the plank disappear and they fall to their death.
When enough players die that cursed players make up half the crew or when all cursed players are voted off, the game ends - Just like Among Us.
 - I think it might be cool to keep the game going even after all the cursed players are voted off because it'd be funny to see crewmembers suspect innocent people and possibly still lose by running out of fish, but it might take too long and not be worth it.