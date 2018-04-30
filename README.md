# rdocker

The R docker that I use. The plan is to have three different images:

- rdocker4ci: for continous integration, containing the core packages
- rdocker4working: for working and with some additional packages like ROracle, RSQLServer, etc.
- rdocker4server: for shiny server deploying with shiny-server built-in.

## TODO

- [ ] Build the image from rocker/I don't think I need the Rstudio bundle in the docker image.


## STATUS

image | size | metrics
----------|----------------|--------------
rdocker4ci | [![](https://images.microbadger.com/badges/image/shrektan/rdocker4ci.svg)](https://microbadger.com/images/shrektan/rdocker4ci "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/version/shrektan/rdocker4ci.svg)](https://microbadger.com/images/shrektan/rdocker4ci "Get your own version badge on microbadger.com")
rdocker4working | [![](https://images.microbadger.com/badges/image/shrektan/rdocker4working.svg)](https://microbadger.com/images/shrektan/rdocker4working "Get your own image badge on microbadger.com") | [![](https://images.microbadger.com/badges/version/shrektan/rdocker4working.svg)](https://microbadger.com/images/shrektan/rdocker4working "Get your own version badge on microbadger.com")
rdocker4server | | 
