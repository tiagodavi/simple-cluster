# SimpleCluster

This is a simple cluster example using libcluster.

## How to run and play with it?

First of all make sure you have elixir/erlang installed and running in your machine then install the dependencies with `mix deps.get` and simply run the command bellow in one terminal: `iex --name n1@127.0.0.1 -S mix`

This will try to automatically connect to another node running on: 

    n2@127.0.0.1

Then try to run the second node in another terminal to automatically connect both nodes: `iex --name n2@127.0.0.1 -S mix`

Try running: `SimpleCluster.Ping.ping()` from the iex terminal to send a message to the other node.

Pay attention to the terminal messages to see all communication happening between them.

Read the code and learn from it.

https://bigardone.medium.com/three-real-world-examples-of-distributed-elixir-pt-1-dac70420b1a8

https://github.com/bitwalker/libcluster