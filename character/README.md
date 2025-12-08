# GraphQL Character Queries

This directory contains GraphQL queries to fetch character data from the Rick and Morty API.

## Individual Character Queries

Queries to fetch details for specific characters by their ID:

- `character-id-1.graphql`: Fetches details for character with ID 1.
- `character-id-2.graphql`: Fetches details for character with ID 2.
- `character-id-3.graphql`: Fetches details for character with ID 3.
- `character-id-4.graphql`: Fetches details for character with ID 4.

### Individual Character Outputs

The corresponding JSON output for each query:

- `character-id-1-output.json`
- `character-id-2-output.json`
- `character-id-3-output.json`
- `character-id-4-output.json`

## Paginated Character List Queries

Queries to fetch a paginated list of all characters:

- `characters-page-1.graphql`: Fetches characters from page 1.
- `characters-page-2.graphql`: Fetches characters from page 2.
- `characters-page-3.graphql`: Fetches characters from page 3.
- `characters-page-4.graphql`: Fetches characters from page 4.

Each query retrieves the following fields for each character:
- `id`: Character ID
- `name`: Character name
- `status`: Character status (Alive, Dead, unknown)
- `image`: URL to character image

### Paginated List Outputs

The corresponding JSON output for each paginated query:

- `characters-page-1-output.json`
- `characters-page-2-output.json`
- `characters-page-3-output.json`
- `characters-page-4-output.json`