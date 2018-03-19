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
- Run `vagrant up`.
- Drupal site will be created at (http://drupal-template.local).
  - Default admin credentials are `admin:admin`.
