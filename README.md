# Dive+ Queries
#RDF queries for DIVE+

This repo contains RDF queries used in [divedashboard](https://github.com/beeldengeluid/divedashboard-ui) and DIVE+ user interface. Queries are [grlc](https://github.com/CLARIAH/grlc) compatible.

If you have a grlc server running, you can see you queries for this repo in this URL:

```
http://localhost:8088/api/DivePlus/queries/
```

If have a [search-api](https://github.com/beeldengeluid/labs-search-api) server running, and want to register these queries on your API, call this:

```
http://localhost:5320/api/v1/plugin/dive-sparql/user/DIVE/grlc/DivePlus/queries
```