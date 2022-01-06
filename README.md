<a href="https://offen.dev/">
    <img src="https://offen.github.io/press-kit/offen-material/gfx-GitHub-Offen-logo.svg" alt="Offen logo" title="Offen" width="150px"/>
</a>

# protocol
A specification for the discoverable exchange of data over a single HTTP endpoint

This repository provides the home for the __Offen protocol__ specification, as well as a server and client reference implementation.

## The specification

The [__Offen protocol__][draft] provides vocabulary and a set of building blocks that can be used to transparently collect and share arbitrary data with your users.
It is derived from our learnings when building [Offen][Offen].

[Offen]: https://www.offen.dev
[draft]: https://offen.github.io/protocol/

## The client

`client` contains a reference implementation of a client class that implements the Offen protocol.
It is written in JavaScript and requires to run in a browser.

## The server

`server` contains a reference implementation of a server that implements the Offen protocol.
It is written in Golang and is designed in a framework agnostic way so that you can use it in basically any application.
