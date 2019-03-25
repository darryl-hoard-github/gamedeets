# gamedeets

Card/Board Game:

Each players goal is to defeat the opponent by winning the game.

Game is won by satisfying a win condition

How to achieve this condition is through the building/upgrading of a “machine” (computer thing), represented by tiled section of the players board. A machine is not a win condition, the “machine” is a game mechanism that forces that player to decide how to divide and manage resources in conjunction with a modeling of a deck, that should A) support the “machine” in it’s improvement throughout the game and B) have a win condition that is supported by a particular machine condition/“program” execution.

Each tile represents a particular component’s functionality of the machine. Each opponent has their own components, which contribute to their machine.

Tiles that a player begins with:

Power: the central resource of the game. Power is generated for each player at the beginning of that player’s turn, and then needs to be routed to the other components, which creates component units, that can be used to pay for effects. When routed the power can then be used for cards of that component’s type, i.e. on the first turn for the first player, a power is generated and routed to the processing component. Now a processing card that cost 1 processing unit, can be used by using that resource, the card is then discard into “memory”

Processing: ??? 🤔 who knows. 
    -Maybe general effects on the game, like drawing cards and tutoring.
    -Maybe an analogous of “instants” in magic, where processing is the only cards that can be used during your opponents turn.
    
    -Perhaps a resource that can be dedicated to a “bank” each player has that lets them wager on actions. I.e. Player A starts their turn, gets power, and routes it to components, use component units generated to use a card from hand, processing units from Player B, could be used to attempt to stop this action by means of a wager, offering a certain number of these points to be matched or declined, and Player A could either allow for the action to be stopped, or match the amount of processing units put up by Player B. 
        -Seems to be the best option right now. Gives all decks a way to interact inherently with their opponent, and acts as another option to consider routing power to. As power is provided only in a finite amount, a player using power in processing, is not developing their machine, or using commands from hand.
        - This also encourages players to play additional power/component unit sources in their deck to have access to more processing power, either to interact more with opponent's or prevent interaction
        - Could also be a combination of this option and one of the previous suggestions to put an even greater tax on the resources

Terminal: Area in which individual program cards are compiled into programs and then run
    - Programs: combination cards. These cards when assembled with other program cards will produce game changing effects. Programs are assembled over multiple turns, by removing cards from hand and adding them to a private program pile. When a program pile is complete, it can be revealed anytime thereafter, once it's "Control" condition has been satisfied, have its effect, and the contributing program cards are moved to “memory”

Network: ability to interact with the opponents machine as well as defend your own. This may include, one time bonuses to other components, or players, or altering opponent’s components.

Memory: represents each player’s discard pile. This is where used/removed/discarded components and cards are moved to and remain unless otherwise affected by other effects. This should be highly integrated into the game and encourage interaction by a number of unique archetypes that are able to utilize this component in unique ways.

Graphics/Mining: cards within the deck, and special effects will cost currency, $/credits. The mining unit converts power provided into currency, that can be spent on additional components/modifications, and for other effects.

Additional Components: Space where new components can be added to the machine. Power can be routed to them and they could either generate units for a different component, or some kind of bonus or effect. This zone begins as empty, but can be added to via component cards drawn from the player’s deck


Players also play with decks of cards which should allow the player to:

    - use specific component units for an effect (one time effects)

    - removal for permanent components

    - interaction for programs being compiled, destroy, look, remove piece, and add piece

    - protection pieces from attacks on components

    - Add new components/modifications to their machine (sustained/continued effects)

    - upgrades to the base components


    - Attempt to modify their own or opponents components, permanently and temporarily


    - Have an effect on either of, or both players and or their decks


    - Contribute to larger card combinations that will represent “programs”, which will be prepared secretly, and revealed in the desired combination.

How To Win: 

Overheating, temperature of the machine is measured and effected by components added and programs running. Opponents can interact with components or directly affect the heating of a machine to cause it to overheat and fail. Temperature would act as an effective “life total” in that it starts at a number, and has an upper limit that once exceeded, causes the game to end for that player. 
    
    - (this would open up space for “cooling” components to be introduced, that would counteract the rising temperature costs of all other components)

### Another possible win condition that I have been toying around with is the idea of an "important file". Each player would have a card that represented this in their deck and both players would reveal that to their opponent at the beginning of the game. The win condition would then be to extract this card from your opponent's deck. If this "important file" was optional, no one would ever play it without a large incentive to do so. So it would most likely need to be mandatory if implemented. 


Card Types:

Commands: cards that can be used from hand. Costs are paid in the resources generated from components. When commands are used they are moved to Memory
    - defeault resources produce:
        processor - processing units
        miner - $
        network - network units
        terminal - program units

Programs: multi part cards from library that may have very small negligible effects by themselves, or no effects, but can be “compiled” stacked together to create large effects 
    -Control, Effect, Close: 
        -“Control” type program cards provide the loop, or condition that a program card is triggered on, or iterates over. 
        -“Effect” type program cards provide the effect to be repeated, or triggered by the control type card. “Effect” cards may have a “Close” clause, which is an added step to be taken. 
        -Not all “Effect” cards will have a “Close” clause. All programs (combination of cards in the program stack) need a Close clause/card to successfully run.
    -Individual program cards will either need to have a cost to be added to a program, or the program must have a cost when run that is the combination of it's parts, this way, costs of indiviudal program parts based on power level can by extension balance programs
        - For example, all program cards may have a "program" cost that totals with the other individual cards in the program, and require that many power units to "run"
    -A few examples, each are examples of 3 card combinations that run as a single program
        Control: If you have 10 or more cards in memory
        Effect: Return two cards in memory to your hand.
        Close: discard a card.

        Control: Pay any amount of life, that amount = L
        Effect: Deal L damage to an opponent's component 
        Close: Put the "Control" of this program on the bottom of your library

        Control: For each component that you control
        Effect: Each player draws a card /Close Cause: Each player's machine temperature increases by 5 

Bots(TBD): "creature"/"minion" equivalents? Cards in the opponent's deck that can be played to the board by paying their costs. These cards once played will remain on the board until removed by another effect. These cards can directly damage components, and increase the temperature of an opponent's machine. They can also prevent this from occurring by blocking attacks by opponent's units. (This may add a lot of added complexity to many of the game systems, possibly unncessarily.) 


Modifications: cards that can make changes to already existing components. These effects remain on the component until it or the component is removed from the board. When a modification or the component it is modifying are destroyed, they are moved into memory. 

Traps: cards that should exist for each component unit cost, but with a focus on Network cards. These cards allow you to protect components preemptively, and attempt to affect opponent's components. Trap cards are placed on the relevant component face down and wait to be revealed until the component is targeted by an opponent's effect.

Components: card that represent additional components that can be added to the board via paying their costs and playing them from hand. Components can either be place in the "Additional Components" section of the board, or can replace the default components on the board. Whenever a component on the board is destroyed, or otherwise removed or replaced, it, and all modifications on it, are placed into memory, unless otherwsie stated. 


Additional considerations:

-Tutoring, searching a library or component for a card should be a HUGE part of the game. Attempt a way for it to benefit multiple archetypes and not just the ones focused on assembling particular pieces for a game win. A possible method to balance is to only allow 2 copies of the same card in the same deck, and broad tutors to be limited.

-Depending on the method by which the power resource is provided to the player, and how that power is replenished each turn, and used to create component units, it may be necessary to introduce a factor to limit the ability of the best strategy to simply be the deck with all the best cards. The current idea is to generate power for the player in incrementally increasing amounts for the first 3-5 turns of the game. And then provide a flat amount of power for the rest of the game. This would require decks that want to use cards that have various component unit costs to play sources of power or component units in the deck to use in addition to the provided power.

Power provide idea #1

Required to track turn numbers, Each turn includes both players' turns. 

At the start of each player's turn, that player receives "Turn #" - "The Amount of Power/ComponentUnits that player has on the board" in power units.

###Using this method, has these effects:
     - power production in later turns can be quite large, benefiting the player able to take advntage of using all of the power given each turn. 
     
     - can allow one deck to play all "the best" cards, independent of what their unit cost is
        - component unit costs are generated by routing power units to a particular component. Since power is generated in it's raw form, it can be routed to any components to generate any units necessary for the cards in hand, thus a deck can emerge that just plays all of the best cards.
     
     - this does not require any decks to consider auxiliary power/component unit sources.
        - this can help contribute to less efficient, less consistent decks, and more interaction between opponents. 

     - Punishes stockpiling of power/component units

    Possible Balance Options: 
        - Set a cap to the amount of power that can be provided in a turn, 3-5. 
        - Make card costs very restrictive (yuck)  

Power provide idea #2

Required to track turn numbers

At the start of each player's first 3 turns, that player receives power units = Turn #. For the rest of the game, 3 power units are provided at the beginning of each player's turn.

###Using this method, it will most likely be necessary to bake in some balance, as it benefits decks that only need 3 power units a turn and below to operate. Possibly unused power and component units will need to be cleared at the end of each turn cycle.

Power provide idea #3

Lag in component unit production.

On each player's first turn, they would receive a power unit, that could then be placed on a component to signify the component has been powered, which would then immediately generate a unit that that component generates.

At the beginning of each player's turn, other than the first, they receive a component unit for each component that has a power unit on it. The player then clears all power units, and receives X amount of power units and assigns power units to components to signify that they are being powered.

### Considerations for this configuration:
    -The amount of power that is provided each turn is not determined using this method.
        - Could be combined with methods #1 or #2 to provide this answer. 

    -The largest issue with this method is the confusion of the rules (due to a difference in how component units are generated on the first and subsequent turns of the game).

    -This configuration requires each player to plan ahead for the component units that will be necesary to generate. It also limits interaction between players using processing units during the first few turns of the game without sacrificing development.  

Combined #1 and #3:

Required to track turn numbers

On each player's first turn, that player generates a power unit, which is then assigned to a component, which immediately generates a component unit. 

At the beginning of each player's subequent turns, before any action can be taken by either player 3 events happen: 
    - All unused component units and power units cleared. 
    - a component unit is generated for each component that player controls  with a power unit on it. Then, all power units are cleared from all of that player's components. 
    - Power units = Turn # are generated, no greater than 3, and provided to the player in the "Power Supply" component zone on the board
