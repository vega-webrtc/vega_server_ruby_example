# Vega Server Ruby Example

This is an example for running a vega server in Ruby.

## Usage

### First time setup

```sh
$ git clone git@github.com:vega-webrtc/vega_server_ruby_example.git
$ cd vega_server_ruby_example
$ bundle install
```

### Running the server locally

```sh
$ bundle exec puma example.ru -p 9292
```

That should start running the server on port 9292. You would reach the server
by passing `ws://localhost:9292` as the url for in the Vega client libraries.
