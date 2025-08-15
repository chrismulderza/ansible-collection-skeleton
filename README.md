# ansible-collection-skeleton

A skeleton repository used for creating Ansible collections.

## Usage

After checking out the repository, update the `skeleton_vars.json` file with
your details, and then initialise a new Ansibe collection with:

```bash
ansible-galaxy collection init --force --collection-skeleton "<path/to/ansible-collection-skeleton/skeleton>" --extra-vars "@<path/to/ansible-collection-skeleton/skeleton_vars.json>" namespace.collection_name
```
