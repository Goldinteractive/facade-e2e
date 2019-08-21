# Facade E2E

Cypress based E2E Testing facade which can be used for any Sackmesser based project.

## Setup

`npx gold-cli setup e2e-cypress`

Update your **root** Makefile to include at the end:

`include e2e/Makefile`

Start writing your specs in `e2e/cypress/integration`.

## Run Cypress

`make test-e2e`

## Maintain the Facade

Push your changes and don't forget to update the package.json version in `e2e/package.json`.

Create a new Tag (Release) for the given version.
