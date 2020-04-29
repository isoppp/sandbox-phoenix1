# MyApp

To start your Phoenix server:

  * Setup the project with `mix setup`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

## personal notes

following: https://lobotuerto.com/blog/building-a-json-api-in-elixir-with-phoenix/

- install hex and phoenix
  - `mix local.hex`
  - `mix archive.install hex phx_new 1.5.1`

- init command
  - mix phx.new . --app my_app --module MyApp --no-html --no-webpack --binary-id

- create/drop db
  - mix ecto.create
  - mix ecto.drop
  - MIX_ENV=test mix ecto.drop
  
- live dashboard
  - /dashboard
  

### User

- `mix phx.gen.context Auth User users email:string:unique is_active:boolean`
  - Auth is context's module name
  - User is schema's module name
  - users is the DB table's name
  
