Vagrant Ansible examples with VyOS
==================================

Requirements
------------

* vagrant-vyos

```
vagrant plugin install vagrant-vyos
```

* Python and poetry

```
sudo apt install python3 python3-pip
pip3 install poetry
```

* Ansible

```
poetry install
```

* Ansible vyos.vyos module

```
poetry run ansible-galaxy collection install -r requirements.yml
```

Usage
-----

* `mv` into example dir and run `vagrant up`
