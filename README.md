# Devfile Templates

A set of personal [devfile](devfile.io) templates I use with [Eclispe Che](https://github.com/eclipse/che) (i.e. [OpenShift Dev Spaces](https://developers.redhat.com/products/openshift-dev-spaces/overview)).

## Usage

You can do any of the following:

- Copy the contents to your projects and open in Eclipse Che
- Source the raw file as a parent in your own devfile
```
schemaVersion: 2.2.0
metadata:
  name: ansible example
parent:
  uri: https://raw.githubusercontent.com/dataNdeadlifts/devfile-templates/feature/initial-ansible-devfile/ansible-playbook-development.yaml

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)