# MyApp

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Using Docker

Build the image
```
sudo docker build -t my-app-elixir .
```
Run the container
```
sudo docker run --publish 4000:4000 --env COOL_TEXT='ELIXIR ROCKS!!!!' --env SECRET_KEY_BASE=$(mix phx.gen.secret) --env APP_PORT=4000 my-app-elixir:latest

```

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
