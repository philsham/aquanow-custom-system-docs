# aquanow-custom-system-docs
## Aquanow Customized System Documentation
Aquanow provides best-in-class execution platform and institutional-quality trading solutions via a single point of access to aggregate liquidity across cryptocurrency marketplaces and exchanges. Aquanow consistes of the following core components:

* **Market Data Service**
* **Pre-Trade Service**
* **Execution Service**
* **Algo Engine**
* **Post Trade Service**
* **Web Applications**

# Market Data Services
Market Data Service provides real-time & historical data feed for users across various cryptocurrecy symbols. Aquanow processes data feed from cryptocurrency exchanges and generate aggregated data & statistics. 

## Functions
* RESTFul APIs for aggregated best bid & offer snapshot
* RESTFul APIs for aggregated orderbook snapshot
* RESTFul APIs for historical best bid & offer 
* Websocket APIs for streaming aggregated best bid & offer
* Websocket APIs for streaming aggregated orderbook

# Pre-Trade Service
Pre-Trade Service generates pre-trade analytics with real-time data and helps user to analyze the performance of execution strategies in the current market condition.

## Functions
* RESTFul APIs for generating pre-trade analytics 

# Execution Service
Execution Service contains the order routing logic which efficiently send orders to different exchanges 

## Functions
* RESTFul APIs for user to place orders

# Algo Engine
Algo Engine contains the logic to maintain the state of the active strategies, control order placements and manage risk.  

## Functions
* A component in the system that consumes 

# Post Trade Service
Post Trade Service provides users the details of the execution information of each order (e.g. executed price, exchange that the order was executed)

## Functions
* RESTFul APIs for users to retrieve their own orders with execution details for each child order. 

# Web Applications
Two main web applications are provided. 
 
* Client Web Portal for client to place order and retrieve their account information
* Trader Web Portal for trader to see in coming orders from clietns, monitor the market with our real-time aggregated market data feed and execute orders using algo
