# GraphQL Episode Queries

This directory contains GraphQL queries to fetch episode data from the Rick and Morty API.

## Episode Queries by ID

Queries to fetch details for specific episodes by their ID:

- `episode-page-1.graphql`: Fetches details for episode with ID 1.
- `episode-page-2.graphql`: Fetches details for episode with ID 2.
- `episode-page-3.graphql`: Fetches details for episode with ID 3.
- `episode-page-4.graphql`: Fetches details for episode with ID 4.

Each query retrieves the following fields for each episode:
- `id`: Episode ID
- `name`: Episode name
- `air_date`: Episode air date
- `episode`: Episode code (e.g., S01E01)

## Episode Outputs

The corresponding JSON output for each query:

- `episode-page-1-output.json`
- `episode-page-2-output.json`
- `episode-page-3-output.json`
- `episode-page-4-output.json`

## API Reference

All queries are executed against the Rick and Morty GraphQL API:
- Endpoint: `https://rickandmortyapi.com/graphql`