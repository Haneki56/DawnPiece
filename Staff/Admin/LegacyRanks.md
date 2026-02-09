# Legacy Ranks

This page explains everything a server administrator needs to know about setting up legacy ranks for new players. Please follow the steps below if you see a player opens a ticket to claim a legacy rank.

## Legacy Ranks Procedure

1. Check to see that the player has enough bounty to qualify for the respective legacy rank they are applying for.<br>

Command: /dp bounty check (name)

2. Check if the player fulfills the quest requirements. You can confirm this by using a Custom NPC wand, going to global settings, clicking player data and searching their quests completed. Trials Quest 4 is required to be completed for 1 Billion Belly Ranks, Trials Quest 7 is required to be completed for 2 Billion Belly Ranks and Trials Quest 9 is required to be completed for 4 Billion Belly Ranks.

3. Once steps 1 and 2 are verified, take the tribute from the player.<br>

1 Billion Belly Tribute (Item Sold in the Flower Capital Shops)<br>
2 Billion Belly Tribute (Item Sold in the Flower Capital Shops)<br>
4 Billion Belly Tribute (Item Sold in the Flower Capital Shops)<br>

4. If there isn't an existing Legacy Rank Holder for the title the player wants, then they get the rank automatically. If there is a player that holds the requested rank, then they must be challenged to a best 2 out of 3 match according to 1v1 Rules that are set up in the PvP plugin for the right to have the title. Whoever wins gets the kit associated with the rank.

5. Change the suffix of the player to match their legacy rank. If there is a rank challenge involved and the challenger wins, change their suffix and remove the suffix of the old legacy rank holder. If the challenger loses, the current legacy rank holder keeps their rank and no suffix changes are necessary. See the list of suffix commands for each legacy rank [here](https://haneki56.github.io/DawnPiece/#/Staff/Admin/LegacyRanks?id=suffix-commands). 

6. If the challenger wins, give them their kit and remove the kit of the old legacy rank holder. If the challenger loses, the current legacy rank holder keeps their rank and no kit changes are necessary. If there is no challenge, simply give the player their new kit.<br>

1 Billion Belly: /lp user (Username) permission set playerkits.kit.1Billion<br>
2 Billion Belly: /lp user (Username) permission set playerkits.kit.2Billion<br>
4 Billion Belly: /lp user (Username) permission set playerkits.kit.4Billion<br>
Remove Kit From Old Legacy Player: /lp user (Username) permission unset playerkits.kit.(1/2/4)Billion<br>

7. Give the new legacy rank holder their new damage value for their respective rank found [here](https://haneki56.github.io/DawnPiece/#/Ranks/Overview?id=legacy-ranks). If there is a rank challenge involved and the challenger wins, give them their new damage value and set the damage value of the old legacy rank holder to 1. If the challenger loses, the current legacy rank holder keeps their rank and no damage multiplier changes are necessary.<br>

Note: Before giving the damage, make sure the player types /dp rank clear. If they still have their old ranks then their damage will be set back to 1.3 the next time they relog.

1 Billion Belly: /mmnm damagem 1.50 (Username)<br>
2 Billion Belly: /mmnm damagem 1.75 (Username)<br>
4 Billion Belly: /mmnm damagem 2.0 (Username)<br>
Loser Reset: /mmnm damagem 1.0 (Username)

8. After all in game items are handled, make sure to update the [MEE6 Embed](https://mee6.xyz/en/dashboard/1385526041807949855/guild_embeds) found in the [Ranks Channel](https://discord.com/channels/1385526041807949855/1395615888585130144) with the new legacy rank holder.

9. Give them their respective discord role. Don't forget to remove the discord role for the old legacy rank owner if applicable. 

10. Once all of these items on the list have been verified, the ticket can then be closed.

## Suffix Commands

Please see the list below for all of the suffix commands applicable for all legacy ranks. Just be sure to replace where it says (name) with the player's Minecraft Username.

### Rank Removal

If a Legacy Rank Holder loses a challenge, please make sure to remove their suffix. You can then advise them to speak to the recruiter at spawn or type /dp ranks to choose a general rank afterwards.<br> 

Command: /lp user (name) meta setsuffix " "

### Pirate Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&c&lWarlord&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&c&lYonko&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&c&lPirate King&0]&f "

### Marine Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&9&lWarden&0]&f "<br>
1 Billion Belly: /lp user (name) meta setsuffix " &0[&9&lAdmiral&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&9&lFleet Admiral&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&9&lCommander in Chief&0]&f "

### Revolutionary Life Path 

1 Billion Belly: /lp user (name) meta setsuffix " &0[&4&lRev. Army Commander&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&4&lChief of Staff&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&4&lMost Wanted&0]&f "

### Samurai Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&b&lDaimyo&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&b&lShogun&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&b&lSword God&0]&f "

### World Government Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&f&lGod's Knight Commander&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&f&lGorosei&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&f&lKing of the World&0]&f "

### Shandian Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&e&lGod's Guard&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&e&lDivine Priest&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&e&lGod of Skypiea&0]&f "

### Baroque Works Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&5&lUnluckies&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&5&lOfficer Agent&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&5&lMr. 0&0]&f "

### Bounty Hunter Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&a&lWarlord Hunter&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&a&lYonko Hunter&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&a&lWorld Seeker&0]&f "

### Bandit Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&6&lCrime Boss&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&6&lTyrant&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&6&lUnderworld Emperor&0]&f "

### Scientist Life Path

1 Billion Belly: /lp user (name) meta setsuffix " &0[&7&lWeather Wizard&0]&f "<br>
2 Billion Belly: /lp user (name) meta setsuffix " &0[&7&lMADS&0]&f "<br>
4 Billion Belly: /lp user (name) meta setsuffix " &0[&7&lAbsolute Mind&0]&f "
