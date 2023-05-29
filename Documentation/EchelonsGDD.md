![2022-12-24-22-38-57-2-Echelon_Deception_and_Survival-1740460400-scale8 00-k_lms-v1-5-pruned-emaonly](https://user-images.githubusercontent.com/22458343/222296043-c3471d85-0686-4242-8762-5c27acfb7a25.png)

>> ### *Echelons of Deception and Survival*
>>>> #### *Game Design Document*
>>>>>>> ##### [**`@n8bot`**](https://github.com/n8bot) 2023


#### Roleplay as a productive member of society — or not.


### Introduction

*Echelons of Deception and Survival* is a semi-competitive third-person roleplaying game with elements of social/urban survival, social stealth, social deduction, immersive sim, and battle-royale gameplay.

Between two and eight players compete for survival in a small, contained economic simulation populated with mostly NPC characters — up to 32 total including player characters.

When a player character dies, the player does not respawn as that character. Instead, the player possesses some other existing character in the world.

Tasks must be performed by characters, both NPC and players, to maintain the economic/survival needs of the setting.

In addition to completing tasks, players must navigate the potentially treacherous environments, and avoid/overcome the fully-NPC guards. Players can choose to engage in combat, but weapons and ammunition are scarce and combat is very lethal.

Four game modes, in order of priority:

1. Last One Standing

   Player identities are concealed. Players must survive as long as possible while dying the fewest number of times.

1. Casual Free Mode — RP

   The economic simulation is given as a sandbox to players. New characters can be regenerated upon deaths to keep the scenario going as long as desired/achievable.

1. Team Target Elimination

   Same character respawn rules as LOS, but players are split into teams, players and developers, and a designated "king" is targeted for assassination. First team to eliminate the opposing king wins.

1. Hitpersons

   Same character respawn rules as LOS, but players are given a list of characters to eliminate — some are NPC, some are other players. First to complete their list wins. (The list transcends character death, stays with the player.)


#### *Echelons of Deception and Survival* key points:
- open source — open to contribution
- cross-platform (Windows/Linux now, others to come)
- online multiplayer
- round-based/non-persistent
- competitive or casual modes
- third-person
- roleplaying
- social/urban survival
- battle-royale
- immersive sim
- social stealth
- social deduction
- multitude of environments


#### *Echelons of Deception and Survival* uses:
- Unreal Engine 5
  - Lumen, Nanite, et. al.
  - Lyra framework
  - EOS/null online subsystems (for online server browsers, and offline+LAN, respectively)
  - Metahumans
    - default for NPC/Players
    - custom for villain (Ulon Mars)
    - extensive use of all available clothing and accessory options for in-game swapping
  - Marketplace assets
    - free, free for the month, etc.
  - new and existing open source assets

All characters are controlled automatically by typical game NPC logic performing daily routines and tasks

NPC decisions are made based on randomized/probabilistic personality traits determined at round start — using Maslow's hierarchy, the biopsychosocial model, and the stress and coping model of human behaviour

Players are assigned a single character at the beginning of a session. They can simply let the NPC act automatically, choose to make small decisions, or take full control of the NPC at any time

If control is taken from NPC, NPC control does not return until a full night's rest (or medication)

Tasks are difficult to perform manually

(The player control is a metaphor for mental illness/psychosis/some other form of mind control)

The first and only setting of the first version will be a small contemporary Martian gambling resort colony. This first environment will be used to discover and explore potential gameplay mechanics/elements.

Economy of the small setting is fully simulated

Economic inputs are mostly imported

Economy is sensitive to changes/disruptions in the supply of goods or performance of tasks

Day/Night cycle, compressed time scale

Characters need food, sleep, mental stimulation/wellness

Certain roles/access to certain areas is dependent on cleanliness and dress code

Starting locations of shops/services will be randomized among eligible "real estate" slots

Starting locations of character/roles will also be randomized

Starting stats and traits of characters randomized

PVP is discouraged through game design, but always possible

Players must deduce who is AI-controlled or player-controlled character


#### Characters

A character is defined uniquely by its Metahuman name and face

Upon initialization, a character is automatically given a set of traits — both physical and personality.

Metahuman body combo (Tall/Average/Short & Underweight/Medium/Overweight):

|               | Short<br />Feminine | Average<br />Feminine | Tall<br />Feminine | Short<br />Masculine | Average<br />Masculine | Tall<br />Masculine
---------------:|:--------------:|:------:|:---------:|:------------:|:-------:|:-------------:
|               | 149 cm<br />(4 ft 11 in) | 160 cm<br />(5 ft 3 in) | 168 cm<br />(5 ft 6 in) | 165 cm<br />(5 ft 5 in) | 172 cm<br />(5 ft 8 in) | 180 cm<br />(5 ft 11 in)
**Underweight** | 40 kg<br />(88 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235524888-0bed886d-6e2a-4b7f-872e-cc319c0baab5.png) | 45 kg<br />(99 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525199-f33753b8-d04f-415b-a3e3-49d266063fc4.png) | 50 kg<br />(110 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525524-076dc63e-05e3-4cc4-80f6-e69b51a88353.png) | 55 kg<br />(121 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235527824-9f4288b4-146d-40f8-9cae-2b8dae43ab65.png) | 60 kg<br />(132 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235528027-e72b9f51-fce2-4a0a-9f83-93a929230bc9.png) | 65 kg<br />(143 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235528509-dfdddd19-7ae5-4868-b4f4-f5bc97aca6fb.png)
**Medium**      | 50 kg<br />(110 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235524958-3e6da5fc-20b3-41b1-9edc-29c74e0d5b96.png) | 55 kg<br />(121 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525355-14ae6996-b1cc-4e32-9268-f04a5e9d5c8b.png) | 60 kg<br />(132 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525596-70a3dff8-b4ea-4ba0-86c1-294c0f0f0714.png) | 70 kg<br />(154 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235527876-be23e3ce-b9f9-4c83-b124-621e16d9ff7e.png) | 75 kg<br />(165 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235528302-af852d4f-7391-4198-b89c-ba06846b27fa.png) | 80 kg<br />(176 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235528570-e5835cdd-98e6-4829-9a23-1b6679302742.png)
**Overweight**  | 60 kg<br />(132 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525037-6a759ad5-6a24-4347-bd35-043d238afe51.png) | 70 kg<br />(154 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525428-ad35830f-4760-4d1e-8595-b13089bb33cc.png) | 75 kg<br />(165 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235525649-df00a739-7006-4e6d-9153-ca6585bd3482.png) | 80 kg<br />(176 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235527921-3ddcbe1c-1934-47e5-9b7b-f1d5a4962ff3.png) | 90 kg<br />(198 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235528362-a630f1a4-5473-4553-80ba-4743831a5188.png) | 100 kg<br />(220 lb)<br />![image](https://user-images.githubusercontent.com/22458343/235528636-681e0ea7-0a4b-4c9e-9619-b291ba41b32e.png)

> **Note:** Images are not exactly to scale (camera position/focal length changes).


#### Food

|                      | Restaurant         | Cafeteria            | Home Cooking
---------------------: | :----------------- | :------------------- | :-----------
**Ingredients**        | wholesale          | food waste           | groceries
**Recipes**            | proprietary        | N/A                  | free/whatever/good luck
**Processing**         | skilled worker     | unskilled worker     | self
**Waste**              | food/packaging     | none                 | food/packaging
**Speed/Availability** | fast/always        | fast/scheduled       | slow/always
**Nourishment**        | pleasing/unhealthy | unpleasing/unhealthy | depends
**Cost**               | $$$$$+             | free* (with job)     | $ -> $$$$$+

#### Clothing:

|                      | Default      | Work uniform | Fashion
---------------------: | :----------- | :----------- | :------
**Durability**         | fair         | poor         | poor
**Dress Code**         | basic access | work access  | all access*
**Cost**               | free*        | $$$          | $$$$$+

> **Note:** Clothes must be cleaned in order to maintain dress code access. This can be done manually at home or via paid laundry service.
> 
> Fashion-based access is subject to the taste and discretion of the character or robot granting access.

#### Robots and weapons/amo

The physical security is all taken care of by extremely lethal humanoid robots armed with firearms and grenades

The robots also serve as the rules of play for the gambling operation robot battle arena — simple wagers are placed on the outcomes of robot battles

The entire colony is built upon this gambling operation — massive amounts of energy and money are spent keeping this running

In secrecy, some of these robots and weapons are being manufactured in excess and used for some other purpose or sold for profit — this is one of the meanings of "Echelons of Deception" — the entire colony is essentially an overall giant deception, with layers of micro-deceptions the whole way down

The rules of the colony will disallow any human from possessing weapons, but of course some people are criminals and will possess them anyway — and some people are VIP and deemed so important that rules basically don't apply to them — unofficially "allowed to have weapons, but can't shoot them"

The rules in general are very selectively enforced — mostly as a way to keep the poor servants of the lower echelons of the colony in check

#### General economic goods/services

- cleaning supplies
  - personal hygiene contributes to access similar to dress-code
- medication
  - robots also administer medication and health services
- rent/real-estate
- power bills
- water bills
- household items/other entertainment goods and services
- spa/makeup/hair styling

#### Black market

- drugs
  - allow players to require less sleep/food/etc., with side-effects
  - allow players to enhance some traits, with side-effects
  - make money by selling to whales/etc.
  - drug labs from obscure input products
- illegal imported weapons


#### Character roles:

Loosely based on chess pieces

Chess   | Echelons
------- | ---
pawns   | unskilled workers
knights | moderators
bishops | business operators
rooks   | VIP hosts
queens  | whale guest
kings   | whale guest*

> **Note:** King/queen does not translate to any gender in echelons. The only thing that distinguishes a king from a queen is that the king is chosen as the mark for elimination while in TTE mode.

1. #### unskilled workers — pawns:
   1. weapons/ammo manufacturer
   1. robot manufacturer
   1. facility maintainer
      - glass repair
      - general colony equipment repair
      - air conditioning repair
      - sewage repair
      - power distribution repair
      - general janitorial cleaning
      - gardening
   1. cafeteria worker
   1. logistics worker

1. #### skilled workers — pieces
   1. moderators (managers of the robot security force and bodyguards of whales) — knights
   1. independent business operators (managers of the shops, restaurants/cafes, and other amenity businesses not related to the colony, robots, weapons, gambling, etc.. LOL. maybe they are owner-operators!!! living the dream! llmao! They are just pawns but pretend to own things.) — bishops
   1. VIP hosts (the managers of the casino, the colony as a whole, etc. but they are pre-occupied catering to the whims of the whales) — rooks

1. #### guests
   1. whales 
      - purely non-worker citizens, who have lots and lots of money who were sold a one-way ticket to the colony as permanent tourists — kings and queens

> **Note:** Whales are essentially employees of the VIP hosts/colony. If they don't gamble, they lose their status as VIP — similar to losing employment status. They lose access to their echelon, their private gambling salon, their comped food, etc.

All these roles are merely defined by tasks. There is no "official hired or not" status. Hired is a concept mutually agreed upon by the employee and the employer. It depends on attendance, performing the task in question, etc.

This is a *tasks* system, not a *roles/jobs* system. Everyone is technically the same. Skill in certain tasks might be required and can be gained somehow.

This is how criminality works. The roles on the black market are not defined "officially," they simply emerge from the market economics (and the AI inclination to perform certain tasks based on toxic personality traits and a probability).

It may include monetization strategies such as in-app purchases or microtransactions, but not until the game is mature.


#### Strategies of the game may involve:

- concealing one's identity
- deducing other players' identities
- sacrificing a character/life, and/or setting up favourable conditions for future character lives
- eliminating players through surreptitious action, while attempting to avoid loss of NPC life — there is an advantage in keeping as many NPC as possible, to operate the economy and provide potential extra lives
- players may try to acquire weapons and attack other players directly — however, weapons are scarce and combat is lethal, so players must weigh the risks vs benefits of such actions
- as characters die, the colony's economy is impacted, leading to a balance of cost and benefit in all actions. Players must carefully balance their actions in the colony, as the economy and infrastructure are fully simulated. Decisions made can have long-term consequences, and players must consider the cost and benefit of their actions.
- throughout the game, players must also be mindful of their own safety, as there are many ways to accidentally kill their character. The environment itself is hostile and dangerous, and players must always be on their guard.

Multiplayer non-serious economy/crime simulator RP. martian outpost that is privateer-based, capitalist pay your way kinda thing to support Ulon Mars’ martian robot fighting league, formerly Unreal Tournaments he bought from Epic Games.

Villain's name is Ulon Mars

People act confused when they hear the name and someone is like "Yeah he changed his name" and they're like oooh yeah yeah ok but we never say the old name.


### New Notes

#### Ontology

Ontology plays a large part of the themes and tone of the game. The ontology will be precise, yet ambiguous. As in, each use of a term will be well defined, but there will be many uses of a single term all of which can only be determined based on context.

E.g., the word echelon itself. It will be used to describe so many things — upper and lower echelon character roles, numbered echelons of player deaths, referring to physical stories of a building, referring to other individual objects. There could be several ways to use these different terms. Upper/lower echelon, echelon 1, 2, 3, or 4. First echelon/Second echelon. Echelon A, B, C. Your echelon, their echelon.

This kind of ambiguous wordplay will be everywhere.

The term neutralized can be used for character death. This acts as a euphemism and also as a play on the other use of the word neutral for character traits described below.


#### Tortoise-TTS

Text to speech using [TorToiSe](https://github.com/neonbjb/tortoise-tts)?

Oh wow yes.


#### Host Migration

If a player dropped out early, and they happened to be the host, the game is ruined. We should plan for host migration, dedicated servers, or have all players in session share hosting duties. Every client is also a server? Madness.


#### Personality Traits

Perhaps a simple positive/negative binary personality trait is determined for each AI character. It could be called "toxic personality" vs wholesome (or sweetheart).

Maybe there is Wholesome, Neutral, and Toxic. All AI character decisions could be based off of a probability weighted against this metric. Being toxic affects probabilities that would be deemed negative like crime, etc.

https://www.reddit.com/r/Twitch/comments/k77rt9/what_is_with_the_wholesome_and_toxic_community/


#### In the end quote

~~"In the end, it was echelons upon echelons of deception. Always has been."~~ "In the end, it was all Echelons of Deception and Survival the whole way down, always has been."


#### Last One Standing Game Mode additional scoring

Perhaps the total duration of time alive of all characters boosts the absolute score of any players in the game. Relative score, for the single game, is simply last one standing - times died. Across all games, the duration of all characters in an individual game, determines the overall absolute score placement across all games (of equivalent versions — leaderboards will be reset for gameplay changes). THIS COULD HAVE NEGATIVE CONSEQUENCES of play sessions being extended to seek leaderboard status. Boosting lobbies, etc. BAGH.


#### Speech-to-text for AI

Whisper.cpp for speech recognition for AI characters to detect spoken words.


#### Survival/MMO mechanics with quick play times

A very essential core part of this game is that the game can be played and fully enjoyed with play sessions of limited time.

Aspects of survival/MMO games seem very fun, but are inaccessible to people who do not have lots of spare time. Echelons is for them.

Also, the reason that VR is not an option for now. VR is a bit much for some people. This game is for them. This game is to provide the social gaming experience of some of the VR, MMO, and survival games, to people who have no time or energy for that lmao.

The game is like an MMO end game. The MMO is over... people can just RP and have fun before the server gets shut down.


#### Source/Sink

Terms to use for economy sim are source and sink. We want to actually avoid these concepts as much as practical/fun.

The outside economy, from which goods are imported (and exported?) needs to be "simulated" on a basic level, in the sense that it can not be an unlimited source or sink.


#### Server MOTD rules

The p2p lobby "server" MOTD with the semi-dynamic content, including server rules, can name the actual players in the lobby as the admins/owners of the server. Give real information to the players in this.

The rules can serve as game instructions. No shooting people (press X to shoot).


#### Robots can perform any tasks

Robots can be programmed, with the same internal game system, to perform any task/duty that the AI characters perform. They can perform it to much higher standards, and at quicker speeds, and with less instruction time. (The players have the worst speed, accuracy, and instruction time compared to robots and AI characters.)

However, the robots are typically never programmed this way by default. They perform two roles by default: security, and arena combat for rules of play. Only with non-obvious techniques can the robots be repurposed.

Also, a price-list can be discovered for the robots and weapons, but as they are never for sale it seems confusing — it's a price list for outside sales.


#### Different shoes have vastly different sounds

Some nearly silent, some really loud. Stylish ones are loud, worn out old ones are quiet but no access.


#### Round-based heatmap-generated "desire paths" aka worn areas

In dirt areas on the lower echelons. Indicates trends of character movement.


#### Toxic and Wholesome are two separate metrics

One can be fully toxic and fully wholesome or any combination. Some decisions might only rely on toxicity. Some rely only on wholesomeness. Neutrality is an emergent concept.


#### Only initial state is randomized

The values of GameAI traits, etc., only change based on systems. All randomization only occurs on initial state creation.


#### Character GameAI traits are based on experience/environment

The primary way that the traits of GameAI change is when they experience/see/hear events in their environment. The GameAI characters are very much products of their environment.


#### Combat stats affected by mental wellness

![image](https://user-images.githubusercontent.com/22458343/233700101-2756bd4f-0a0e-4274-9e63-564dfb8aeec6.png)


#### Player customization

Player customized content can be made tied to the player account of the creator for a limited time upon merge.


#### Turing test

The game ends up actually being kind of like a turing test. Spot the "AI" could be useful for marketing.


#### Voice system

Tortoise-tts is used to generate phrases for the NPC — either several consistent voices or just random voices always. 

The generated voices must to the player be exactly equivalent functionally as player voices. That is, they are treated the same way.

Character mouth movement is base on the audio which generates movement in real time, the same for both player and generated voices.

Whisper.cpp is used to listen for keywords — gameplay mechanics/scenario "rules" help to minimize the need or desire for communication — but some is allowed (for conducting transactions, work, gambling, etc.). 

Generated voices are listened to and interpreted just as the player voices are.

Voices are modulated in real time to alter the pitch up or down randomly/in line with the character, within a certain range, to try and obfuscate all voices.

The character voices are all generated based on text input from designers in easy-to-manage data structure.

New builds periodically re-generate voices so the sounds are not always identical and players can be challenged.

There are several variations of each utterance generated per voice, and they are cycled through in randomized order to attain as dynamic speech as possible.

Defects present in generated voices can be kept to simulate weird player behaviour.


#### Subjectivity

The concept of selling or buying or owning is up to subjectivity. If an NPC who owns a store sees someone with an item they sell in the store, they will expect money for it. Don't pull things out of your pocket at the wrong time.


#### Books

Books are the main form of allowed entertainment other than gambling. There is an eerie lack of electronics other than colony-provided devices.


#### Not about twitch reactions or shooting

The mechanics for shooting are favourable to the player being shot. Checks are made between all clients to verify mutually all kills. Animation/effects will hide the delay. Twitch shooting is not really helpful. It's more about deciding to take action and then seeing various results of those actions.

The game is more like playing in a hitman map multiplayer.


#### Character interactions rated

The personality traits are derived from character interactions altering them. NPC and players experience interactions. Some automatically apply buff or debuff to personality, other interactions can allow NPC or players to actively choose to rate another character as toxic or wholesome. This can be done with the expressions system. Facial expressions, etc.


#### Character collision capsule

Make the feet part of the capsule more tapered so it's easier to slip and fall off ledges. Foot IK will possibly help provide hilarious dynamic leg movement during the sudden unexpected fall.

Metahuman ragdoll example is key llmao.


#### Lack of variety

The lack of variety in terms of clothing options, hair styles, food, etc., will be masked by the difficulty in making the selections. Not difficulty directly, but in time and space. The player will be pre-occupied with other tasks, the character will not have time to go make these choices as they will be out of the way.

The characters will have a routine, which is somewhat hard to break.


#### NPC performance optimization

In an attempt to keep the number of metahumans in LOD0 and LOD1, the NPC will aggressively attempt to leave areas with large clusters of other characters. The ranges of each LOD from each player will be maintained, so that no more than about 4 are in LOD0 for any player at any given time.

This will provide somewhat of a gameplay element. Players can try to deduce who is another player based on their emulation or not of this tendency to leave the area when there are too many other characters. Also, the clusters forming around specific characters can perhaps be detected as well.

This is a feature, not a bug.


#### Wholesome/Toxic is seen as Snowflake/Cool

Players vs Developers. The same rating system is used for all characters. Players and developers each see the ratings conversely. While the Developers see Toxic behaviour, the players see cool. Wholesome is seen as snowflake. It is the same and affects decision making basically the same. The reactions by the character change. The emotions change. Mental health reactions are different


#### Mouth flapping

The visemes of the metahuman can be cycled through randomly while characters are talking. As long as the sound is coming through, the visemes are interpolation. However, the magnitude of the openness of the mouth is changed as the amplitude of the sound changes. The combination of the two provides for dynamic reaction to the actual sound, without marionette-like flapping. The visemes will shut the mouth somewhat, and change the lip shape, so that the audio's amplitude influence is hidden, and vice versa the amplitude of the audio hides the interpolation of the visemes. If the amplitude is low, the lips should barely look like they are moving. As if someone is just grumbling silently to themselves. The guards can detect this and say "No grumbling." Llmao.


#### Collision capsule reduced so that it is harder to balance on things

The character collision capsule should come to a smaller point underneath the character's center of balance. Then, the foot IK will hopefully make it seem reasonable for balancing on thin things. Could work. And make it hilariously fun to slip and fall.


#### Consider volume and concealment of all items the characters can have

Logistics should be a real concern. Moving basic items from one place to another is a task, especially if this activity must be concealed.


#### Electrical lines have individual runs from source to target or better organized network

The electrical lines go everywhere and be deadly if u touch them wrong


#### Speech interruption

Whether for Player or non-player character, if the speech/voice is interrupted by death before the sound file ends or the PTT button is released, this can be a trigger to raise suspicion of nearby NPC.


#### Ragdolls and balancing

Characters can lose balance. They can be pushed around by outside forces such as other characters. Ragdoll mode is ubiquitous. They can tumble, roll, and be injured on every hit all the way down. Jumping is entering ragdoll mode. Landing with a certain orientation will regain balance, otherwise full ragdoll — based on IK foot placement goals.


#### NPC Target pursuit

When NPC are pursuing a target, they should be targeting descriptive features that could cause them to mistake a different target for the same person. Tall, masculine, long dark hair, yellow shirt, etc.


#### The idea or concept of engaging in combat

Often in games this is on or off. An NPC is engaging or not in combat with another. Instead, this is a confusing grey area. Who to fight? Who is fighting? Who is friend? Do I fight, flight, or freeze?


#### Time scale

One day is scaled down to about 7.5 minutes. That game day is extrapolated to be a game week. Every day in the game, the characters progress their traits as if a week had progressed conducting that days behaviour.


#### DevAuth Tool/Account Portal analogues

In the game world, the characters can use account portal to enter credentials every time or they can use the devauth tool to automatically provide credentials.

LMAO... this Player/Developer thing is really coming together.

Player and Developer are called "Echelons" like houses in harry potter. Which Echelon are you? Player or Developer?

"I'm not even a Player, I'm just a user." "Don't say that." "I'm such a user."


#### Robot NPC Guards are called UBots

Ubot 101, 102, 103, 104, etc. Random hex number?


---

### Collections of Pre-existing Notes

Below is a collection of notes about the game.


### Notebook Notes

These notes are transcribed from handwritten notes, in the order they appear in the notebook. The order is not logical.


#### Unsorted

- Roles mapped to chess pieces — 32 Characters total
  - Upper echelon: Kings, Queens, Rooks, Knights, Bishops — VIP Whales, Operations Management, Security Management, Small Business Operators
  - Lower echelon: Pawns — Workers
- Mental health is modeled with medication as a pickup to buff/debuff certain stats simultaneously (restores mental health with side effects)
- Picture the routines of all the specific jobs/roles
- Characters must sleep  
  - While sleeping characters/players can use their electornic device (phone, "mental probe" implant, etc.) to perform online shopping and other activities
  - AI-controlled characters can also do this automatically to some extent
  - This mechanic adds to the narrative as well as gives players something to do when the character is sleeping
  - Perhaps sleeping pills are required to do activities while sleeping
  - Maybe other types of pills allow a character to forgoe sleep with some debuff side-effect
- Maybe the Knights are more like dedicated security/bodyguards for the VIP whales
- Currency? Digital/Cash?
  - "Mars Credits"?
  - Proxy?
    - Diamonds?
    - Bullets?
    - Pills?
    - Spices?
    - Booze?
- Chat? Voice? Text?
  - "SMS" via phone or "mental probe" implant?
- Social Credit?
- Player-paid billboard ads?
- Business reviews?
  - Message to/from businesses?
- Random business names
  - Players name theirs
- Battery on phone or "mental probe" implant depletes
- Camera movement lags AI movement?
- Phone/ID Device can be lost/stolen
  - Phone/ID Device is issued by the casino/house/management/colony
- Entire facility is put under lock down, red lights and sirens, if any glass is broken of the dome, etc.
  - Roof glass breaking mechanism: multiple layers of glass. Shards of glass rain down on characters causing damage. Red alert, lockdown. Always explained away as thankfully all the layers didn't break. Technical side: Glass planels never do break, they just spawn shards of glass for simplicity.
- Throwing system
  - Physical properties like hardness, weight, etc., affect trajectory and damage


#### What is the angle/take of the colony?

- Simply scamming the colonists with exchange rates sending money from earth, converting to Mars Credits and no facility to transfer back to Earth currency.
- Casino/House manipulated the digital currency?
  - Printing money?
- Ulon Mars is the mastermind
  - Mars Gambling Resort, LLC owns and operates entire facility except small independent businesses (which are owned by Mars Gambling Resort, but operated and rented by the Bishops/whomever)
    - VIP Guests Bring the money to keep the wheels greased — tons of it
      - Workers do all the work — tons of it
        - Robots combat as a basis for gambling and as physical security/police.
- "Amazing.com" PRIMO account gives you one-day delivery to Mars from their off-world distribution centers
  - Prices are inflated because Mars
- There is a weapons manufacturing facility and a humanoid robot manufacturing facility
- Ulon Mars has ulterior motives for the entire operation. There is an ultimate echelon of deception which is revealed for the first time when the player is victorious in a round.


#### Monetization

- MTX for players to be able to offer special items *for-sale* in their in-game shops
  - Has gameplay implications — users without assets will not be able to offer certain items for sale, and could reveal their identity easier


#### Mapping to Chess Moves

- Pawn — Worker: limited movement, but with a sneaky en-passant (the strategy employed by players)
- Bishop — Small Business Operators: large range of motion in a certain direction, limited to its domain (some special access, but not an "insider")
- Knight — Special Security: range is limited by policy, but can "pick" targets with special access (like jumping over pieces)
- Rook — House: large range of motion, domain is not limited — all access privileges
- Queen — VIP subset: nearly-unlimited range of motion, but ultimately tied to the King and their limitless resources (charm their way anywhere)
- King — VIP subset: debilitated by the stress and burden of the colony — remorse, sense of being scammed, shame, addictions, mental/physical health problems


#### Unsorted

- Package inspection game mechanic/duty/task/ability
  - A certain role or set of roles has the authority to inspect individual packages in logistics at will, searching for contraband or for any other purpose
  - Package contents are physically laid out and the individual items can be interacted with like normal
- The Weenie is the large structure at the center of the colony, which serves multiple purposes and is a very tall tower
  - The base of the Weenie holds the Emergency Escape Balls which will launch VIPs to safety in case of danger
    - They VIPs climb inside, and are launched into the air, away from the colony, and land back to safety on the Martian surface gently via parachute
      - They will never function when a person is inside — they will parachute perfectly every time they are launched empty
  - The Weenie also supports the protective cup — the glass dome around the colony, which provides the physical barrier to the deadly Martian atmosphere
- Possible mental model of AI/Characters whereby they self-rank themselves in terms of superiority — modelling complexes of narcissists and the opposite
- Mandatory "mental probe" implants (neurolink)


#### Game Types

- Last One Standing
- Team Target Elimination
- Hitpeople
  - All players are secretly hit persons. Crazy Ulon Mars has given them all tailored hit lists which contain some AI characters and also all other player characters, but without knowledge of which is which. Winner is the first to complete their list without getting hitted.
- Casual RP Mode


![image](https://user-images.githubusercontent.com/22458343/224476328-919a5534-0d16-4a9e-ad9e-42348b0ed29e.png)


---

### Use of the Lyra framework

Fully leverage the Lyra framework to find the fun. Do not re-invent systems. Build upon existing systems.

To build off of Lyra Sample Project


#### Sarcastic Server Rules banner

Maybe different random banners each time, with similar joke rules

Server Rules:
- No killing
- No guns
- No shooting guns
- No stealing
- No talking
- Go to your job
- No bad behaviour
- No selling stuff without permission from the mods
- No drugs
- No arguing with the mods
- Report to mods (there actually are no mods)


---

###### Copyright 2023 [**`@n8bot`**](https://github.com/n8bot). *Echelons*, *Echelons Online*, and *Echelons of Deception and Survival* are Trademarks of [**`@n8bot`**](https://github.com/n8bot).
