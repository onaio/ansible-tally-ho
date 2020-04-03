# ansible-tally-ho

Install and configure tally-ho.

## How it works

This role depends on the [ansible-django](https://github.com/onaio/ansible-django).

Basically, this is what it does:

1. Installs Redis
2. Installs the tally-ho web server, which is a Django application
3. Finishes setting up Django
4. Installs SSL certificates if necessary

## Role variables

You can see all variables by looking at the `defaults/main.yml` file.

You can look at `tests/test.yml` for examples of how to use these variables.

## Testing

This project comes with a Vagrantfile, this is a fast and easy way to test changes to the role, fire it up with `vagrant up`.

See [vagrant docs](https://docs.vagrantup.com/v2/) for getting setup with vagrant

## License

Apache 2

## Authors

[Ona Engineering](https://ona.io)
