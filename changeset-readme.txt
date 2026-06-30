// Changeset CLI Commands 
// (https://github.com/jakoblorz/go-changesets/blob/main/docs/07_cli-reference.mdx)

changeset add

changeset tree
changeset tree --format json

changeset changelog --project backend-service2
changeset changelog --project frontend-service2

changeset version --project backend-service2
changeset version --project frontned-service1

changeset each --filter open-changesets -- changeset version
changeset each --filter unchanged -- changeset version



