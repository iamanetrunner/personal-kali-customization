# Personal Kali Customization

These are my customization scripts for every time I have to perform a Kali clean install.

## Steps to install

- From a freshly installed Kali machine, update all packages by running:

```
sudo apt update
sudo apt full-upgrade -y
```

- Install Ansible:

```
sudo apt install ansible-core
```

- From the root directory of the repository run:

```
ansible-playbook main.yml
```

- When it finishes, restart the virtual machine, and before loggin in, check on the menu in the right-top corner and select bspwm.

- Login and enjoy!

**Disclaimer**: These Ansible scripts might work on other linux operative systems like Parrot, Debian or even Ubuntu, but these scripts haven't been tried on those distros.