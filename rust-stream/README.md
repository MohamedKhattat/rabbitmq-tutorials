# Rust code for RabbitMQ tutorials (using rabbitmq-stream-client)

Here you can find the Rust code examples for [RabbitMQ
tutorials](https://www.rabbitmq.com/getstarted.html).

The examples use [rabbitmq-stream-client](https://github.com/rabbitmq/rabbitmq-stream-rust-client) client library.

These tutorials assume a RabbitMQ server node running locally using default ports and the [stream plugin enabled](https://www.rabbitmq.com/docs/stream#enabling-plugin).

## Requirements

* [Rust and Cargo](https://www.rust-lang.org/tools/install)

## Code
Each cargo command should be launched in a separate shell.

#### [Tutorial one: "Hello World!"](https://www.rabbitmq.com/tutorials/tutorial-one-rust-stream.html)

    cargo run --bin receive
    cargo run --bin send