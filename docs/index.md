## Welcome to CTKXbot's documentation

You can do lots of things with this bot, but it gets confusing to remember all the commands, right?

## Commands

[Stocks](/stocks/index.md)

### General

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .ping   |                      | Pong!  |
| .define | `word`                 | Looks up a word in the dictionary | 
| .rhyme | `word`                  | Finds rhyming words |

### Clocks

| Command  | Additional Input     | Output |
|----------|----------------------|--------|
| .clock   |                      | Shows a live clock that lasts for 1 minute. |

#### Stock Clocks:

Shows the lime left until market period starts or ends.

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .clock  | `pm`                   | premarket  |
| .clock  | `mkt`                  | market  |
| .clock  | `ph`                  | power hour (final hour of day)  |
| .clock  | `ah`/`am`                  | after hours/after market  |

The stock clocks default to NY Trading hours. You can also specify a country code, or market acronym:

| Command | Additional Input     | Output |
|---------|----------------------|--------| 
| .clock  | `<mkt_type>` `US` / `NYSE` / `NASDAQ` | New York |
| .clock  | `<mkt_type>` `CA` / `TSX`           | Toronto |
| .clock  | `<mkt_type>` `UK` / `LSE`           | London |
| .clock  | `<mkt_type>` `DE` / `FWB`           | Frankfurt |
| .clock  | `<mkt_type>` `CN` / `SSE`           | Shanghai |
| .clock  | `<mkt_type>` `JP` / `JPX`           | Tokyo |
| .clock  | `<mkt_type>` `HK` / `HKEX`          | Hong Kong |
| .clock  | `<mkt_type>` `FR` / `EURONEXT`      | Paris | 
| .clock  | `<mkt_type>` `CH` / `SIX`           | Zurich |

  
#### Fun

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .pronounce | `word`              | Attempts to pronounce a word |
| .advice | `@username` (optional) | Gives you advice, or the user you mention |
| .compliment | `@username` (optional) | Compliments you, or the user you mention |
| .shibe | `@username` (optional) | Sends you a shibe, or the user you mention |
