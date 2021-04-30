## Welcome to CTKXbot's documentation

You can do lots of things with this bot, but it gets confusing to remember all the commands, right?

## Commands

[Server/Guild Owner Setup](/guild_setup/index.md) 

### General

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .ping   |                      | Pong!  |
| [.mod](/mod/index.md) | [`required_args`](/mod/index.md) | [Moderator Functions](/mod/index.md) |
| [.stocks](/stocks/index.md) | [`required_args`](/stocks/index.md) | Stock market info |
| [.clock](/clock/index.md) | [`optional_args`](/clock/index.md) | International Clocks |
| .define | `word`                 | Looks up a word in the dictionary | 
| .rhyme | `word`                  | Finds rhyming words |
| .pronounce | `word`              | Attempts to pronounce a word |
| .advice | `@username` (optional) | Gives you advice, or the user you mention |
| .compliment | `@username` (optional) | Compliments you, or the user you mention |
| .shibe | `@username` (optional) | Sends you a shibe, or the user you mention |

### Games

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .dice | `x` `y` | Rolls `x`dice, with `y` sides |
| .mines  | `number` | Emoji Minesweeper. Defaults to 10 mines, you can specify between 10 and 30 mines<br> Numbers are optional. Defaults to 1x 6 Sided die|
| .flipcoin | | Flip a coin. Heads you win! |
| .hangman | `difficulty` `category` | Hangman (Interactive) <br> Difficulties: <br>`easy` <br>`medium` <br>`hard` <br><br>Categories: <br>`all` <br>`animals` |
| .hilo | `number` | Card Game (Interactive) <br>Draw a card and guess if the next card will be higher or lower. Keep going for double or nothing rewards. Order of Cards:<br>`ace (1)`<br>`2-10`<br>`Jack (11)`<br>`Queen (12)`<br>`King (13)`

### Tokens

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .wallet | 					 | Check how many tokens are in your wallet |
