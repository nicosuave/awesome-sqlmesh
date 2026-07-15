# Awesome SQLMesh [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="https://sqlmesh.readthedocs.io/">
    <img src="https://raw.githubusercontent.com/TobikoData/sqlmesh/main/docs/readme/sqlmesh.png" alt="SQLMesh logo" width="200">
  </a>
</p>

> A curated list of awesome SQLMesh libraries, tools, and resources.

[SQLMesh](https://sqlmesh.readthedocs.io/) is a next-generation data transformation framework for shipping data quickly, efficiently, and without error.

All contributions related to SQLMesh are welcome! Please check the [contribution guidelines](CONTRIBUTING.md) first. Add new entries at the bottom of each category.

## Contents

- [Awesome SQLMesh ](#awesome-sqlmesh-)
  - [Contents](#contents)
  - [Official Resources](#official-resources)
  - [Sample Projects](#sample-projects)
  - [Community Projects](#community-projects)
  - [Tools](#tools)
  - [Media](#media)
    - [Blog Posts](#blog-posts)
    - [Videos](#videos)
  - [Contribute](#contribute)

## Official Resources

Docs, Slack, and core repositories.

- [Official Documentation](https://sqlmesh.readthedocs.io/en/stable/) - Official SQLMesh documentation.
- [Slack](https://tobikodata.com/slack) - Tobiko Slack community; the team is highly responsive.
- [SQLMesh Repository](https://github.com/TobikoData/sqlmesh) - Core SQLMesh source code.
- [SQLGlot Repository](https://github.com/tobymao/sqlglot) - Python SQL parser and transpiler used by SQLMesh.

## Sample Projects

Official examples and community demos to learn from.

- [Examples from the main repo](https://github.com/TobikoData/sqlmesh/tree/main/examples) - Built-in example projects in the SQLMesh repository.
  - [Custom Materializations](https://github.com/TobikoData/sqlmesh/tree/main/examples/custom_materializations) - Example of defining custom materializations.
  - [Ibis](https://github.com/TobikoData/sqlmesh/tree/main/examples/ibis) - A Python SQLMesh model with Ibis.
  - [Multi Repo](https://github.com/TobikoData/sqlmesh/tree/main/examples/multi) - Multiple SQLMesh projects.
  - [Multi dbt](https://github.com/TobikoData/sqlmesh/tree/main/examples/multi_dbt) - Multiple dbt projects in a single project.
  - [Multi Hybrid](https://github.com/TobikoData/sqlmesh/tree/main/examples/multi_hybrid) - dbt project alongside SQLMesh in a single project.
  - [Sushi](https://github.com/TobikoData/sqlmesh/tree/main/examples/sushi) - Canonical SQLMesh demo project.
  - [Sushi dbt](https://github.com/TobikoData/sqlmesh/tree/main/examples/sushi_dbt) - Sushi demo implemented with dbt.
  - [Sushi dlt](https://github.com/TobikoData/sqlmesh/tree/main/examples/sushi_dlt) - Sushi demo with dlt integration.
  - [Wursthall](https://github.com/TobikoData/sqlmesh/tree/main/examples/wursthall) - Restaurant analytics example project.
- [Official Example projects](https://github.com/TobikoData/sqlmesh-examples) - Additional official SQLMesh example projects.
- [sqlmesh-demos](https://github.com/sungchun12/sqlmesh-demos) - Community demos and walkthroughs for SQLMesh.

## Community Projects

End-to-end projects built with SQLMesh.

- [arcane-insight](https://github.com/mattiasthalen/arcane-insight) - An analytics, ingestion, and transformation project built with SQLMesh and DuckDB on Blizzard's Hearthstone API.

## Tools

Editors, proxies, and utilities around SQLMesh.

- [vscode-sqlmeshui](https://github.com/WesleyBatista/vscode-sqlmeshui) - Embedded SQLMesh UI in VS Code.
- [buenavista](https://github.com/nicosuave/buenavista/tree/add_sqlmesh_semantic_rewriting) - A fork of a Postgres/DuckDB proxy exposing both the PG and Trino protocols with a SQLMesh metric rewriter.
- [tff](https://github.com/tjirab/tff) - Fitness functions engine and linter for transformation projects, with a dedicated SQLMesh plugin.
- [sqlmesh-openlineage](https://github.com/sidequery/sqlmesh-openlineage) - OpenLineage integration for SQLMesh that emits table and column lineage events.

## Media

Blog posts, talks, and videos.

### Blog Posts

- [Unlocking Data Insights with Ibis and SQLMesh](https://tobikodata.com/ibis-sqlmesh-unlocking-data-insights.html) - Using Ibis with SQLMesh for analytical workflows.
- [SQLMesh for DBT Users 1](https://tobikodata.com/sqlmesh_for_dbt_1.html) - Introduction to SQLMesh for dbt users.
- [SQLMesh for DBT Users 2](https://tobikodata.com/sqlmesh_for_dbt_2.html) - Continued guide to SQLMesh for dbt users.
- [Efficient Development with the SQLMesh Browser UI](https://tobikodata.com/sqlmesh-ui.html) - Developing with the SQLMesh browser UI.

### Videos

- [Tobiko Data Youtube](https://www.youtube.com/@TobikoData/) - Official Tobiko Data YouTube channel.
- [Evolving Data Pipelines at Scale](https://www.youtube.com/watch?v=8XP25nQ2rPY) - Talk on evolving data pipelines at scale with SQLMesh.
- [Building SQLMesh Macros like dbt macros](https://www.youtube.com/watch?v=Qqbn1vUbLCU) - How to build SQLMesh macros similar to dbt macros.
- [SQLMesh Quickstart Guide](https://www.youtube.com/watch?v=weJH3eM0rzc) - Quickstart walkthrough for SQLMesh.
- [Running dbt Jaffle shop in SQLMesh](https://www.youtube.com/watch?v=weZxrJ2GHco) - Running the dbt Jaffle Shop example in SQLMesh.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
