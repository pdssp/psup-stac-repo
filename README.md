# PSUP STAC Repo

Contains the generated results of [psup-stac-converter](https://github.com/pdssp/psup-stac-converter)'s default pipeline.

You can observe the rendering from [RadiantEarth's STAC browser](https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/pdssp/psup-stac-repo/refs/heads/main/catalog.json), or use a local STAC browser directly. You will need to import it directly as a submodule with

```console
$ git submodule update --init --recursive
``` 

# Using Docker

You can serve the catalog on `localhost` using Docker. To serve it, simply spin a container with 

```console
docker compose up -d
```

And go to `http://localhost` to see the result.

# Using Radiant Earth's STAC Browser

You can either implement directly the root catalog inside [STAC Browser](https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/pdssp/psup-stac-repo/refs/heads/main/catalog/catalog.json), or use the local version build with Docker compose at `http://localhost:8091/`.


It gives a quicklook as well as a compliance with the schemas.