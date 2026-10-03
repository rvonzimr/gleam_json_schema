# gleam.toml schema

Unofficial JSON schema for Gleam (as of gleam 1.18.0)!

## Checks

Tasks are defined via [mise](https://mise.jdx.dev)

```sh
mise run lint      # every schema check (metaschema, idioms, formatting)
mise run test      # the unit tests in tests/
mise run validate  # check TOML files against the schema (default: examples/)
mise run format    # format the schema and the examples in place
mise run convert   # print one TOML file as JSON
```