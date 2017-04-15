# epgsql_poolboy

This is erlang pgsql app which uses poolboy APIs to create connections pool to perform pgsql operations.

## Configuration

Open **src/epgsql_poolboy.app.src** and change the pgsql parameters there.

## Usage

```
epgsql_poolboy:equery(Poolname, Query, Params);
```
