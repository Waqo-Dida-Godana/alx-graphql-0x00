# alx-graphql-0x00

This repository contains GraphQL learning exercises focused on querying the Rick and Morty API.

## Project Structure

### character/
Contains GraphQL queries and their outputs for fetching character data:

#### Individual Character Queries
- Query files: `character-id-1.graphql` through `character-id-4.graphql`
- Output files: `character-id-1-output.json` through `character-id-4-output.json`

#### Paginated Character List Queries
- Query files: `characters-page-1.graphql` through `characters-page-4.graphql`
- Output files: `characters-page-1-output.json` through `characters-page-4-output.json`

Each paginated query retrieves a list of 20 characters with the following fields:
- `id`: Character ID
- `name`: Character name
- `status`: Character status (Alive, Dead, unknown)
- `image`: URL to character image

## API Reference

All queries are executed against the Rick and Morty GraphQL API:
- Endpoint: `https://rickandmortyapi.com/graphql`

## Repository Information

- **Repository**: alx-graphql-0x00
- **Directory**: character/