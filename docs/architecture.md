# Architecture

How the main parts connect. Read this before adding a module or changing how
parts talk to each other. Describe the shape, not every file.

## Parts

- Front end: Vue + Vite + Tailwind, in src/. The only part.
- No API and no database. Accounts, tasks and administration are planned.

## How they connect

Everything runs in the browser. Login is simulated in the front end, with
no HTTP calls.

## Data

No persistent data yet. How simulated users are stored is decided by the human.

## What does not belong here

How to start the project (docs/dev-environment.md) and why a choice was made
(docs/decisions.md).
