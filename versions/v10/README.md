# Beesness v10

There are many sub-versions of v10.

## What they have in common

Everyone starts with the same _startup capital_: some bee cards (workers, drones and queen), some flowers and some honey.

Each player can play only one card per round. Place your chosen card face-down, and when everyone has made their choice, reveal the cards simultaneously, and resolve their actions in this order:

1. Queen(s can hire other bees. _Full-time_ = play & take back
2. Worker(s) can pick flowers. _Freelance_ = play & discard
3. Drone(s) sell flowers for honey (also freelance)

You get the maximum return for your chosen card when you're the only one playing it in a round. The more people play the same card, the less they get out of it.

## What they don't have in common

### [**v10.1**](v10.1.md), aka *The Fixed Term*

* 12 flowers in the garden to start with
* 9 rounds, whoever has the most honey at the end is the winner
* No *beesaster* (see below)
* No flowers replanting at the end of each round
* Flowers <-> honey conversion chart
* In the last round workers become *gamblers* and queens become *speculators*

### **v10.2**, aka *The Convoluted*

* 12 flowers in the commons to start with
* As many rounds as it takes the winner to get to 36+ honey
* Replanting 1/3 of flowers left at the end of each round
* Flowers <-> honey conversion chart
* Compulsory die roll at the end of each round. if rolled number is bigger than flowers left, the game is over and everybody loses (aka **beesaster**)
* *Beesaster* referendum with game-theory-style pay-offs.

### **v10.3**, aka *The Realpolitik*

* 9 flowers in the commons to start with
* As many rounds as it takes the winner to get to 36+ honey
* No Flowers <-> honey conversion chart. Instead, *honeypot* is 18H - number of flowers left in the commons
* Blind bid for honeypot: winner takes it all, and losers still lose the flowers they committed
* No flowers replanting at the end of each round. Instead, roll a special 6-sided die with numbers ranging from -3 to +2 (including 0), which determines how many flowers will be removed/added to the commons
* *Beesaster* happens if the commons run out of flowers (either picked by players or decided by die roll)
* *Beesaster* referendum with game-theory-style pay-offs & anyone can call a ref before the end-of-round die roll

### **v10.4** Foragers, workers and drones

* Foragers pick flowers. 3 max, -1 for each other active forager.
* At the end of each round, replant a flower for each forager active on that round. This means that the mechanism to replant the commons already exist, but you need consensus to make it happen (and there could always be someone who uses a different card to take advantage of the situation).
* Workers transform flowers into *products* (coloured boxes). 3 max, -1 for each other active worker.
* There is no queen so all bees are full-time.
* Drones sell products (instead of flowers). Sold products go into the commons, becoming a sort of landfill.
* Blind bid for honeypot: winner takes it all, and losers still lose the flowers they committed.
* Honeypot: 18 - F
* Beesaster: if all flowers run out. Or if there is too much landfill (ratio between flowers and sold products)?

### **v10.5**

* Each player starts with
	- 3 worker cards (instead of 2)
	- 2 drone cards
	- 1 queen card
	- 2 pieces of stuff to sell (see below what I mean by stuff)
	- 0 honey, no honey, nada, you’re a lean startup beesness
* Bees deck starts with
	- 3 worker cards (instead of 2)
	- 2 drone cards
* Commons start with **9 flowers**.
* Honeypot is **12 - flowers left** in the commons. 	
* Workers pick flowers. Flowers allowance = total players - active workers (as usual)
* At the end of each round, **replant 1 flower for each worker active on that round**. You could think of it as pollination. The more workers go out in the commons, the more they pollinate, and the more flowers will grow in the future. Crucially, this means that replanting the commons (to avoid its depletion and prevent Beesaster) is possible. Using many workers, ideally all players agreeing to choose the worker for a round. In that case no flowers would be taken from the commons, and many would be replanted (as many as there are players). With this rule there is no need for a referendum mechanic, but players need consensus to make it happen and there could always be someone who chooses a different card to take advantage of the situation. This change prompted me to increase the number of workers, to incentivise their use as a vote2replant card.
* **Beesaster** still happens if the flowers run out, but instead of triggering game over and loss for everyone, it **eliminates only the player who took the last flower**. The underlying tension between depleting the commons to maximise profits and keeping it afloat should remain, but by eliminating only one player instead of all, I hope to remove the threat of “disgruntled players screwing everyone over”. This will likely require a clarification: when playing the worker, you don’t have to take all the flowers you’re entitled to take. Maybe players could take precedence by paying honey (just like irl).
* **Flowers and stuff** Workers pick flowers (green tokens) from the commons and they immediately turn them into _stuff_ (coloured cubes). This is to visualise the process of transformation of natural resources / raw materials (the flowers) into products for the market (the stuff). Drones then will sell stuff instead of flowers (which confused quite a few playtesters). Sold stuff will go into the commons (middle of the table) and becomes landfill. It works as a visual reminder of who sold what. There could be room to experiment with “recycling the stuff”. Maybe the more landfill there is, the harder it becomes to grow flowers, or there could be another beesaster triggered by too much landfill.
* **Freelance bees** Hiring bees becomes increasingly expensive depending on the amount of honey held by the hiring player. It goes like this
	- you have between 0 - 9 honey -> hire bees for free
	- 10 - 19 -> bees cost you 1 honey each
	- 20 - 29 -> bees cost 2 honeys
	- 30 - 39 -> 3 honeys
	- etc.
	This could be a nice come-back mechanic.




## Why so many versions?

**v10.1** was the first version of Beesness I wasn't ashamed of. Fellow designers at the PlaytestUK meetup in London really liked it, and so did friends & friendly strangers at several playtest sessions. The **simultaneous-action mechanic** (one card per round) produces quick and intense games, and everyone is constantly engaged as their actions depend on the other players. Also, the variance between player scores tends to be small, which means games are still open to at least two players until the end.

So that's a fun game. However, while optimising the *entertainment*, I parked element of the game which I still consider important. Let's call them the *critical* components: a collapsing ecosystem leading to *beesaster* (game over + everyone loses) and the democratic possibility of avoiding beesaster (through referendums).

I had a refreshing chat with Andrew Sheerin (designer of the infamous [War on Terror](https://www.terrorbullgames.co.uk/games/war_on_terror_game.php) and other brilliant games) about my struggle to combine a fun game with a critical agenda. His feedback was illuminating:

1. *Beesaster* in previous versions was the individual responsibility of the player who happened to be in the position to take the last flower. That gave such player the supreme power to end the game (and potentially ruin it for everyone else, which is why the PlaytestUK peeps didn't like it). Andrew suggested that it should be a collective responsibility.
2. The game should encourage players to stress-test the ecosystem. Andrew suggested to try and link the flower return to the number of flowers left, somehow. That way, players would be encouraged to starve the commons in order to maximise their returns.
3. Andrew also suggested to experiment with strong incentives to sell as little flowers as possible.

In short, adding interesting choices for players around the *beesaster*-related parts of the game. The aim is to create a tension between the selfish+competitive player motivation (aka the capitalist mandate) and the need to balance the ecosystem.
