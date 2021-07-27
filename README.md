# exchange-orderbook

Project is just a basic order-matching engine (orderbook), created especially for learning Rust and internals of trading systems.

Each instance of orderbook is a single-threaded reactive module for the certain currency pair. It consumes orders and return vector of events, generated during processing.

Supported features:

* market orders
* limit orders
* amending limit order price/quantity
* cancelling limit order
* partial filling

