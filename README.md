# Event Store Go Client

A [Go](https://golang.org/) client for [Event Store](https://geteventstore.com/).

## Status

This project is considered at an alpha stage and shouldn't be used in production.

## Example

For an example, look into `example`. You will need an instance of event store to be running to try it.
I suggest using [Docker](https://docker.com/) with [Event Store Docker Container](https://hub.docker.com/r/eventstore/eventstore/).

## Implemented

* Writing to a stream
* Reading a stream forwards
* Volatile subscriptions
* Deleting stream

## TODO

* Complete unit and integration tests
* Transaction
* Reading a single event
* Reading a stream backwards
* Reading all events forwards
* Reading all events backwards
* Persistent subscription
* Scavenging database
* Global authentication