## Run Locally

(First [install Elm](http://elm-lang.org/install))

If you do not have this repo on your computer yet, run these commands.

```bash
git clone https://github.com/LapshinIV/AvaElm.git
cd AvaElm
```
You have to install json-server

```bash
npm install -g json-server
```
Go to `AvaElm/server` and run the command

```bash
json-server --watch db.json --port 8001
```

Once you are in the `AvaElm/` directory, run these commands:

```bash
elm-reactor
```

And then open [http://localhost:8000/Main.elm](http://localhost:8000/Main.elm) to see it in action!
