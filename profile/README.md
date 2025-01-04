Welcome to the TerrainSympa orga !

TerrainSympa is a free and open-source French cadastral parcel web search engine.

The website is here: https://terrainsympa.fr (not up yet).

This orga got 3 distincts repos to make TerrainSympa up and running:
- `db-elt` to extractm transform and load all datas needed 
- `back-gql` a graphql backend that use the database created by the `db-elt`
- `front-vvvue` a frontend for the end user that use `back-gql`
