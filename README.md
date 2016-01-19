# Croquet Australia

This repository, [croquet-australia](https://github.com/croquet-australia/croquet-australia), contains an overview of all Croquet Australia repositories & services. This branch,  `phase2/master` is the current development branch.

## Repositories

The current list of repositories only includes those required by `phase2`. todo: Add all Croquet Australia repositories.

### auth.croquet-australia.com.au

Handles authorisation and authentication for all Croquet Australia resources.

### croquet-australia-domain

- This is the Domain/Model layer.
- It depends on no other Croquet Australia repository.

### croquet-australia-domain-implementation

- Implements interfaces in `croquet-australia-domain` repository.
- It depends on `croquet-australia-domain` repository.
- Microsoft Azure Table Storage is the primary persistence technology.