# cintel-04-rolling-monitoring-custom

Author: James Webb (`jrwebb7`)

Updated: 2026-11

## Project Overview

I plan to use simulated fellowship onboarding data to track tasks due,
tasks completed on time, and tasks still open at the end of each workday.
I'll compare three- and five-workday rolling averages to see how quickly
each one picks up a growing backlog.

[Project documentation](https://jrwebb7.github.io/cintel-04-rolling-monitoring-custom/)

## Run the Starter Example

```bash
uv sync
uv run python -m cintel.rolling_monitor
uv run pytest
```

The starter pipeline writes its rolling averages to `artifacts/rolling_metrics.csv`.

## Developer Tools

The project uses Polars for data analysis, marimo for the interactive app,
uv for dependency management, prek for Git hooks, and pytest for tests.

## Template Credit

[Denise Case's rolling monitoring template](https://github.com/denisecase/cintel-04-rolling-monitoring)
