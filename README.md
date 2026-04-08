uv init cbs
cd er naartoe
wijzig in pyproject.toml de python versie naar 3.12
uv python pin 3.12
uv add dbt-core dbt-snowflake
dbt init --> invullen