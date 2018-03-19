# drupal-template

Composer based Drupal 8 template with Drupal VM.


## Requirements

You will need to have available on your system:
- PHP 7.2
  - on macOS, use Homebrew: `brew install php72`
- [Composer](https://getcomposer.org)
  - minimum version 1.6.3
  - On macOS, use Homebrew: `brew install composer`.
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  - version 5.x
- [Vagrant](https://www.vagrantup.com/)
  - minimum version 1.8.6
- [Ansible](https://docs.ansible.com/ansible/latest/intro_installation.html)
  - minimum version 2.4
  - On macOS, use Homebrew: `brew install ansible`


## Setup

- Clone the repo.
- Run `composer install`.
- In `vmconfig/config.yml` change `project_ip` to a free local network IP of your choice instead of default `192.168.88.88` (Optional).
- Run `vagrant up`.
- Drupal site will be created at (http://drupaltemplate.local).
  - Default admin credentials are `admin:admin`.
  - If you have [Drush launcher](https://github.com/drush-ops/drush-launcher) installed on your host system, you can use the alias `@drupaltemplate.local` to access the site from your host command line.
