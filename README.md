# Ansible Mastodon Playbook

[![CI](https://github.com/geerlingguy/ansible-mastodon/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/geerlingguy/ansible-mastodon/actions?query=workflow%3ACI)

Welcome to the tootiverse.

This Ansible playbook sets up a single server Mastodon instance, following (roughly, but much more automated-ly) the [official Mastodon source install guide](https://docs.joinmastodon.org/admin/install/).

> Note: The playbook is a work in progress. See this issue for details: [Make it like... work and stuff](https://github.com/geerlingguy/ansible-mastodon/issues/1).

## Usage

  1. Create a VPS somewhere. Choose Ubuntu 20.04 or Debian 11.
  2. Install Ansible locally, make sure you can SSH into your server.
  3. Install requirements: `ansible-galaxy install -r requirements.yml --force`
  4. Create a `hosts.ini` file and `config.yml` file from the provided example files.
  5. Run this playbook: `ansible-playbook main.yml`

## License

MIT.

## Author

[Jeff Geerling](https://www.jeffgeerling.com).
