# `m-onz`

## screenshot

An early algorithmic experiment...

<img src="3.png" />

## todo list. ideas...

## virtual orchestra

create a virtual orchestra... each virtual performer is modelled using node.js or erlang as concurrent actors that can communicate via message passing. Each virtual performer can have some algorithmic process or ruleset that it follows. Each virtual performer can listen to the other performers using machine listening or cheating by getting note values or metadata directly.

Each virtual performer sends OSC messages that can be interpreted as sound by Pd or SuperCollider. High level parameter changes should produce interesting and varied results. It should be possible to experiment with the number of performers used and by limiting or enhancing the performers cabalities. The performers could evolving internally using genetic algorithms. Performers of different types could be introduced into the same virtual orchestra creating interesting results. Performers could have a lifespan and randomly spawn a performer of a random type: this would create unpredictable changes as performers drop in and out.
