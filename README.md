Mizuno AI Commands
===============

`/help` Basic commands!
----------

| Command | Description | Usage |
| ------ | ----------- | -----------|
| `/help`  | Sends help message | `/help` |
| `/delete` | Delete a particular message Mizuno sent | reply `/delete` to any Mizuno's message | 
| `/kick <reason (optional)>` | Kicks a user | reply `/kick <reason (optional)>` to a user's message |

---

`/help` More commands!
----------

| Command  | Description | Usage      |
| ------   | ----------- | -----------|
| `/fun`     | Sends available random miscellaneous commands | `/fun` |  
| `/slot`     | `CURRENTLY DISABLED`<br>Sends commands for the slot machine game | `/slot help` for more info |  
| `/axiehelp`     | Sends available Axie Infinity / crypto related commands | `/axiehelp` |  
| `/note`     | a handy way of saving "notes"! | `/note help` for more info |  


---


`/fun` Random and miscellaneous commands!
----------

| Command  | Description | Usage      |
| ------   | ----------- | -----------|
| `/reddit` |  Returns a random Reddit post from a subreddit | `/reddit <subreddit>` |
| `/pokemon` | Returns the base stats of a Pokémon | `/pokemon <pokemon name>`|


--- 


`/slot` `CURRENTLY DISABLED` Slot machine game!
----------

| Command | Description | Usage |
| ------   | ----------- | -----------|
| `/slot spin` | Spins the slot machine. Default bet amount is 10.00 HaraCoins. | `/slot spin <bet amount>` |
| `/slot balance` | Shows your current balance. | `/slot balance` |
| `/slot help` | Shows help message for `/slot`. | `/slot help` |
| `/slot give` | Gives `<amount>` to `@mentioned` player | `/slot give <amount> <@receiver>`| 

| Symbol | Multiplier | More info |
|--------|------------|-----------|
🍄 | x 0.2
🍒 | x 0.5 
🍌 | x 0.5 
🍎 | x 2 
🍊 | x 2 
🍇 | x 2 
🌟 | x 4 
❓ | x 4  |(wildcard)


---


`/axiehelp` Axie Infinity/crypto related commands:
----------

| Command | Description | Usage |
| ------   | ----------- | -----------|
| `/slp` | Command to check SLP balance | check `/slp help` for more info |
| `/price` | Shows the current price (with price graph in the last 6 hours) of requested crypto/coin.<br>`<coin>` = can be the ID (slp) or name (smooth love potion). <br>`<currency>` = can only be the abbreviation (php) of your requested currency| `/price <coin> <currency>` |
| `/stat` | Shows your current stats in Axie Infinity. <br> `<address>` = could be your Ronin or ETH address. | `/stat <address>` | 
| `/axieinfo` | `CURRENTLY DISABLED`<br>Shows information about `<axie id>`. <br> `<axie id>` = Axie ID. <br> `<type>` (optional) = stats, cards; defaults to both | `/axieinfo <axie id> <type (optional)>`|


---


`/slp` commands!
----------

| Command | Description | Usage |
| ------   | ----------- | -----------|
| `/slp` | Shows current SLP balance of `<address>` | `/slp <address>`|
| `/slp daily` | `CURRENTLY BUGGY`<br>Shows your daily SLP earnings.<br>**IMPORTANT!** Use `/slp addtracker` before using `/slp daily` | `/slp daily`|
| `/slp addtracker` | Adds your address to the SLP tracker | `/slp addtracker <address>` |
| `/slp edittracker` | Edits your address to the SLP tracker | `/slp edittracker <address>` |


---


`/note` - a handy way of saving "notes"!
----------

| Command        | Description | Usage |
| ---------------| ----------- | -----------|
| `/note help`   | Shows help message for `/note` | `/note help` |
| `/note add`    | Adds note<br>**IMPORTANT!** Use an underscore _ instead of a white space!| Reply `/note add <note_name>` to a message|
| `/note get`    | Gets note | `/note get <note_name>` |
| `#`            | Shorthand for `/note get`, same functionality as `/note get` | `#<note name>`|
| `/note list`   | Lists notes on a particular thread | `/note list` |
| `/note delete` | Deletes requested note | `/note delete <note_name>` |


---


`/ar` `/autorespond` - autoresponder!
----------

| Command        | Description | Usage |
| ---------------| ----------- | -----------|
| `/ar help`   | Shows help message for `/ar` | `/ar help` |
| `/ar add`    | Adds autoresponse | Reply `/ar add <autoresponse name>` to a message|
| `/ar list`   | Lists autoresponse on a particular thread | `/note list` |
| `/ar delete` | Deletes requested autoresponse | `/note delete <autoresponse name>` |
