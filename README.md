# ProBuilders Relay

> backend for Stormworks servers running CCV2 for integration into the PB Dashboard

On first run it will generate a `config.json`, fill it out with your credidentals from https://swprobuilders.com/.  
Then restart it, it should be working, check the Dashboard to see if nothing is blocked.

For help, open a Issue here or contact us on Discord: https://swprobuilders.com/discord

## Extensibility through Add-Ons

This application can easily be extended through add-ons by creating a folder "modules" next to the executable.

These modules must have a ExpressJS Router as default export. Other type of add-ons can be loaded through a loader module.

## Documentation for the Api

The Documentation will be hosted at https://swprobuilders.com/apidoc.

## Will this be open sourced?

Yes! I plan on open-sourcing the relay module so people can check the code for trust or if someone wants to contribute.

So you might ask, where is the source? It will remain closed-source until the endpoints are made public and the v2 api is sufficiently implemented.

Currently only the v1 api is accessible for our older scripts, but new software and scripts should use the new v2 api.
