# Lead-Time-Manager
v. 2015.10.25

Design & code by Dr. Jordi Weiss.

Based on the "Operations Management" course by Prof. Suzanne de Treville at the University of Lausanne around 2015 to 2022.

This simulation-game illustrate our research insights about the impact of lead time reduction on volatility exposure and cost of mismatch between supply and demand.

This is an EARLY version of the program. 

A more current version can be found at: https://forio.com/app/lausanne/new3

Additional material is available at: https://oplab.ch/game

In this simulation-game, the player takes the role of a manager faced with a supply and demand problem. The shop sells two types of ski jackets: Fashion and Standard, with different cost, price and demand volatility characteristics. Each jacket has a variable demand each season, for which the mean and median are given.

The manager can choose to order offshore to a long lead time supplier, or to develop a local production. When ordering offshore, the order must be done before demand for the season is known. When producing locally, employees are hired and machines are bought, creating fixed costs, but production can be done on-demand.

Trial and errors make the tradeoff between lower unit cost and longer delay very palpable.

--------------------------------------------------
## Instructions:

### Read the introduction of the game :

-	You are a ski jacket retailer.
-	You sell 2 different models, one is fashionable, overstock at the end of a season is lost.
-	The other one is standard, overstock can be stored (at a cost) and sold on next season.
-	You can choose to produce on your own local factory, or to outsource offshore.
-	Demand is only known after the season has started.
-	Offshore, you must order 4 months before the season beginning, so with unknown demand.
-	Locally you can produce during the season, so with a known real demand.
-	Use the clock on the right to keep track of the stage that's currently active.

### The game starts in period 1, pointer of the clock on "LLT Order" (LLT=Long Lead Time=Offshore factory)

-	Place your offshore orders for both of the jackets.
-	The cost per unit for each is indicated in the "Offshore" box (top left).
-	You have no information about demand.
-	Also, you can manage your local capacity, the production capacity you will have in period 2.
-	Increasing capacity just adds fixed costs, but getting rid of capacity is quite expensive.
-	Press the [Enter] key of your keyboard to validate your choices.

### Then comes period 2, pointer of the clock on "SLT Order" (SLT=Short Lead Time=Local factory)

-	Place your local orders for both of the jackets.
-	The cost per unit for each is indicated in the "Local" box (top right).
-	Notice that you now know the demand (second line of the central table or "Shop" box).
-	You can then complete your LLT orders to meet the demand.
-	But your local capacity is limited to what you chose in period 1.
-	Press the [Enter] key of your keyboard to validate your choice.

### Then comes period 3, pointer of the clock on "Results"

-	You can now analyze the full result of the season in the central table.
-	Press the [Enter] key of your keyboard to start a new season.
	
### Advices

-	Think twice about the margins you make on each of the 2 products. Which one should be your priority ?
-	Consider what you lose by ordering without knowing the demand.
-	Consider the increase of your local capacity as an investment to improve your flexibility & reduce your mismatch costs.
