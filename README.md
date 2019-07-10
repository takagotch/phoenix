### phoenix
---
http://phoenixframework.org/

https://github.com/phoenixframework/phoenix

```exs
defp deps do 
  [{:phoenix, path: "../..", override: true},]
  
config :phoenix, :json_library, Jason

```

```sh
mix phx.digest.clean
mix phx.digest.clean -o /www/public
mix phx.digest.clean --age 600 --keep 3

cd installer
mix phx.new dev_app --dev

cd assets
npm install
cd ..
MIX_ENV=docs mix docs
mix deps.get
mix compile
mix deps.get
mix compile
mix deps.get
mix compile
mix archive.build
cd assets
npm install
npm run watch
```

```
```



