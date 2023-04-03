# compliance-pipeline-properties
Template Repository containing externalised pipeline properties required by compliance toolchain.

### Usage

Once this repo has been cloned, the user should:

- Update the contents of each `environment-properties.env` file to insert the values they require for their respective pipelines and triggers.
- Replace all instances of `[insert-vault-server-address]` in the `secret-store.yaml` files with the address for their vault.
- Replace all instances of `[insert-vault-role-id]` in the `secret-store.yaml` files with the roleId for their vault.
- Replace all instances of `[insert-secret-name-in-vault]` in the `external-secrets.yaml` files with the appropriate secret names from their vault.
