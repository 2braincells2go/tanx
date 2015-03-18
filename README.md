# tanx

Multiplayer WebGL Game

[__online demo__](http://playcanv.as/p/aP0oxhUr "tanx game")  
[![tanx game](http://files.moka.co/screens/tanx_04.jpg)](http://playcanv.as/p/aP0oxhUr)

## installation & running

1. Install the Node dependencies:

        npm install

2. Run the server:

        npm start

    Or:

        node app.js

    WebSocket and HTTP servers will be started on port `30043` by default. You can change the port or host via environment variables:

    * `TANX_PORT=30043`
    * `TANX_HOST='0.0.0.0'`

## usage

1. Fork the [tanx client](https://playcanvas.com/project/45093/overview/tanx) project.
2. Run the game from designer with `?server=local` argument so it connects to `http://localhost:30043/socet`.
3. Play your fork!

## changelog

##### v1.4.2 (05.03.15)
* added usernames - let others know you
* added us server - if you are from US, it will connect to dedicated server on west-coast for better network experience
* changes ui, designs by @roonio
* changes room capacity - 12 players

##### v1.3.0 (16.02.15)
* added teams - 4 of [blue, red, green yellow] colours
* added scores - teams and players have score
* added end game scenario - first team to reach 32 kills
* added lobby and rooms - each room can handle up to 16 players, then new room will be created

##### v1.2.1 (10.02.15)
* added pickables: repair, bullets, shield

##### v1.1.0 (09.02.15)
* added Block object
* added tank-level collision
* added bullet-level collision
* merged [@cvan](https://github.com/cvan) pull request: [allow host/port to be changed via environment variables; update README with verbose instructions](https://github.com/Maksims/tanx/commit/837c2f34588b4060d8112afe3002dc1d7fabc77e)
* merged [@cvan](https://github.com/cvan) pull request: [code linting](https://github.com/Maksims/tanx/commit/f28b6c3259ed82f962957fd2f531cf916bbc6638)
