# Behind the scenes

This is just a simple chat, created following the #38 elixir casts tutorial, in order to learn more about channels and how useful they are for real time sending and receiving of messages.
All you have to do is create a channel, and whoever subscribes to that channel, will receive messages from the broadcasters. The fun part is that receivers and senders can swap their positions, and they can be anything. In this case it's a simple javascript client that's subscribing to the channel and waiting for messages.

# Chat

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `cd assets && npm install`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
