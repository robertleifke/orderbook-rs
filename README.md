# Order matching engine (orderbook)

A basic matching engine, "orderbook." 

Each instance of orderbook is a single-threaded reactive module for the certain cryptocurrency pair. It consumes orders and return vector of events, generated during processing.

Supported features:

* market orders
* limit orders
* amending limit order price/quantity
* cancelling limit order
* partial filling


## Usage
Full example code could be found in `bin/example.rs`.

## Run 

`cargo run` 