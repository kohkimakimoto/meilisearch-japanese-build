# Meilisearch Japanese Build

This repository contains Github Actions workflows to build the Meilisearch for Japanese.

## How to build

1. Create a new tag in the repository. The tag name must be the same version of Meilisearch you want to build. For example, if you want to build Meilisearch v1.14.0, create a tag named `v1.14.0`.
2. Push the tag to the repository. 
3. Create a new release from the tag. 
4. The Github Actions workflow will automatically be triggered and start building the Meilisearch.

## See also

* https://github.com/orgs/meilisearch/discussions/532
* https://github.com/meilisearch/meilisearch/pull/3882
