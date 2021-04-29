# Stocks

[Back home](../index.md)

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .stocks | `<symbol>` `1ytarget` 	| 1Y Target (est) |
| .stocks | `<symbol>` `52wrange`		| 52 Week Range<br>( lowest and highest price at which a stock has traded during the previous 52 weeks. ) |
| .stocks | `<symbol>` `ask`			| The ask is the lowest price someone is willing to sell a share.  |
| .stocks | `<symbol>` `avol`			| Average Volume (3 Months) |
| .stocks | `<symbol>` `beta`			| Beta compares a stock's volatility to the rest of the market. <br>A beta greater than 1 means the stock is more volatile than the average <br>A beta less than 1 has less volatility than the average. |
| .stocks | `<symbol>` `bid`			| The bid is the highest price someone is willing to pay for a share. |
| .stocks | `<symbol>` `borrowed`		| Shows borrow availability, with ETFs |
| .stocks | `<symbol>` `dayrange`		| The highest and lowest price the stock has traded for today |
| .stocks | `<symbol>` `earnings`		| Last 5 years Revenue & Earnings |
| .stocks | `<symbol>` `edate`		| Next Earnings Date |
| .stocks | `<symbol>` `eps`			| Earnins per Share |
| .stocks | `<symbol>` `exdd`			| Ex-Dividend Date |
| .stocks | `<symbol>` `fdy`			| Forward Dividend & Yield |
| .stocks | `<symbol>` `ftd`			| Failure to Deliver |
| .stocks | `<symbol>` `holders`		| Institutional Holders Info |
| .stocks | `<symbol>` `iborrowed`	| Shows borrow availablility. |
| .stocks | `<symbol>` `mcap`			| Market Cap |
| .stocks | `<symbol>` `open`			| Today's Open Price |
| .stocks | `<symbol>` `optiondates`	| Shows Options Dates |
| .stocks | `<symbol>` `options`		| Shows options data |
| .stocks | `<symbol>` `options`	<`puts`/`calls`> `yyyy-mm-dd` `<filter>`	| Shows detailed options data for puts / calls that expire on week ending `yyyy-mm-dd`<br>Filters:<br>`strikeabove X`<br>`strikebelow X`<br>`strikebetween X`|
| .stocks | `<symbol>` `pclose`		| Previous Close Price |
| .stocks | `<symbol>` `per`			| Price/Earnings Ratio |
| .stocks | `<symbol>` `qearnings`	| Last 4 Quarters Revenue & Earnings |
| .stocks | `<symbol>` `shortvol`		| Short Volume |
| .stocks | `<symbol>` `ssr`			| Short Sale Restriction |
| .stocks | `<symbol>` `stats`		| Stats (Most of the other options) |
| .stocks | `<symbol>` `vol`			| Volume |

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
