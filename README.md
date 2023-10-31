# Lina's Linux keyboard remap for Macs

This is an Ansible role planned to be a part of my personal GNOME customisation set.

To use this in a playbook, you'll need to pass the `-K` option to `ansible-playbook` for the BECOME root password.

## Manual actions

* xremap needs to be installed. The role assumes that xremap is installed at user's Rust (install it at [rustup.rs]()) cargo binary directory.

`cargo install xremap --features gnome`

* Role dependencies need to be installed.

`ansible-galaxy install petermosmans.customize-gnome`
