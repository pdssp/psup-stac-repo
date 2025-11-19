# PSUP STAC Repo

Contains the generated results of [psup-stac-converter](https://github.com/pdssp/psup-stac-converter)'s default pipeline.

You can observe the rendering from [RadiantEarth's STAC browser](https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/pdssp/psup-stac-repo/refs/heads/main/catalog.json).

# Using Docker

You can serve the catalog on `localhost` using Docker. To serve it, simply spin a container with 

```console
docker compose up -d
```

And go to `http://localhost`to see the result.

# Using Radiant Earth's STAC Browser

You can implement directly the root catalog inside [STAC Browser](https://radiantearth.github.io/stac-browser/#/external/raw.githubusercontent.com/pdssp/psup-stac-repo/refs/heads/main/catalog/catalog.json). It gives a quicklook as well as a compliance with the schemas.