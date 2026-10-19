# MDS Data Product Factory: Interactive Prototype

Clickable concept prototype of an MDS Data Product Factory for SME fleet managers. It shows how a fleet could turn its telematics data into a governed, privacy-reviewed data product for the Mobility Data Space (MDS).

## Run it

Open `index.html` in any modern browser. It is a single self-contained file with no dependencies, build step or network calls.

## What the demo covers

**Data to Product** (six steps):

1. Data source: a synthetic fleet telematics dataset
2. Data check: field classification and quality signals
3. Product idea: three candidate data products from the same dataset
4. Privacy recipe: transformations such as drop, bucket, aggregate, suppress and mask
5. Approvals: fleet manager, data protection and works council gates
6. MDS preview: the resulting data offering with usage policies

**Product idea to Data** (reverse mode): describe an idea, derive the data signals it needs, match simulated MDS catalog offerings, assess feasibility and get a sourcing blueprint.

The page also registers a small set of WebMCP tools (`document.modelContext`) when the browser supports them, so an AI agent can drive the demo.

## Disclaimer

All data, providers and catalog matches are synthetic. Nothing is sent or published. Not legal advice and no live MDS connection.
