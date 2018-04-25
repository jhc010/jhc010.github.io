---
layout: post
title:  "WS Simulator"
date:   2018-04-19
categories: C# Games
---
This was my first C# project and I was aiming to make a simulator for a card game to allow me and friends to play
against each other online more easily than playing through Skype or a similar video chat service. Since the app uses
host-client connection, ideally hamachi is used to create a local network or both players are already connected on LAN.

To start a game, one person needs to be the host by clicking Start Host, while the other person enters the ip of the
host and selects Start Client. Then, you can acquire a decklist from wsdecks.com using their "copy decklist by text"
button.

Once both players are connected, pasting the decklist into the box and clicking start game will start a game.
As a side note, the card database isn't 100% complete as it caters to a group of friends so invalid cards will
cause errors.

[WS-Simulator][WS-Sim]

[WS-Sim]: https://github.com/jhc010/WS-Simulator

Next post: Z80 Spectrum Game for CSE190
