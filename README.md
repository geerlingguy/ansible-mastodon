# Ansible Mastodon Playbook

Well, I'm not sure how Twitter's going to go, so I thought I'd mess around with the Federated tootiverse.

So here's an Ansible playbook to set up a single server Mastodon instance, following (roughly, but much more automated-ly) the [official Mastodon source install guide](https://docs.joinmastodon.org/admin/install/).

## Usage

  1. Create a VPS somewhere. Choose Ubuntu 20.04 or Debian 11.
  2. Install Ansible locally, make sure you can SSH into your server.
  3. Create a `hosts.ini` file and `config.yml` file from the provided example files.
  4. Run this playbook: `ansible-playbook main.yml`

## License

MIT.

## Author

[Jeff Geerling](https://www.jeffgeerling.com).
