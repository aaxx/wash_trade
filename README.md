
|Exchange|Protocol|Type|Time Book|Time Trade|Used Time|
|---|---|---|---|---|---|
|Bitfinex|WS|-|1 ms|1 ms|Exchange|
|BitMart|WS|Updates|n/a|1 ms|Local|
|Bitstamp|WS|-|1 μs|1 μs|Exchange|
|Bittrex|WS|-|n/a|1 ms|Local|
|Binance|WS|Updates|~1 sec (1 ms)|1 ms|Exchange|
|Bit-Z|Unoffical WS|Updates|1 ms|1 sec (+)|Exchange|
|BW|Unoffical WS|Updates|n/a|1 sec|Local|
|Coinbase|WS|-|1 ms|1 ms|Exchange|
|Coinbene|Unoffical WS|Updates|1 ms|1 sec (+)|Exchange|
|Cointiger|Unoffical WS|Snapshots|1 ms|1 ms|Exchange|
|HitBTC|WS|Updates|~100 ms (1 ms)|1 ms|Exchange|
|HuobiGlobal|WS|Snapshots|1 ms|1 ms|Exchange|
|IDAX|Unoffical WS|Updates|1 ms|1 ms|Exchange|
|Kraken|WS|Updates|1 ms|1 ms|Exchange|
|LBank|WS|Snapshots|1 μs|1 μs|Exchange|
|Livecoin|WS|Updates|n/a|1 ms|Local|
|OKEx|WS|Updates|1 ms|1 sec|Exchange|
|ZB|WS|Snapshots|1 sec|1 sec|Exchange|

* (+) means that we have 1ms precision on trades *batch message*, but we have 1 sec precision on trade itself
* ~1 sec (1 ms) meants that we recieve data once per second, but it has timestamp with 1 ms preciesion

Please see individual readme files in the subfolders
