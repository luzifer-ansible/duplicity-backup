# luzifer-ansible / duplicity-backup

This role installs nginx and [duplicity-backup](https://github.com/Luzifer/duplicity-backup) on the host and writes the configuration to be used.

**Notice:** Currently the role only supports S3 and FTP backup without additional package installation. If you are using other methods ensure the required packages are installed.

## Requirements

- Debian >= 8 (jessie)
- Ubuntu >= 16.04 (xenial)

## Usage

See the [Ansible Galaxy Intro](https://galaxy.ansible.com/intro) for usage of roles within Ansible Galaxy.

For configuration variables and how to use them see [defaults/main.yml](defaults/main.yml).
