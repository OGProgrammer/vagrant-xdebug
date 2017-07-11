# vagrant-xdebug
An Xdebug example using a PuPHPet generated Vagrant VM

This example currently only works with linux and mac. You can get this working with Windows if you change the puphpet/config.yaml to SMB mounting instead of NFS.

## Prerequisites

You must have [`vagrant`](https://vagrantup.com) installed. You'll also want to install the bindfs plugin for vagrant by running 

```
vagrant plugin install vagrant-bindfs
vagrant plugin install vagrant-hostsupdater
```

## Instructions

Run `vagrant up` then grab some ☕ 

You should see a bunch of ascii art at the end that says "read above", your VM should be running at this point. You can always double check by running `vagrant global-status`

Hosts Updater should have added the `example.ogp` host to your `/etc/hosts` file.

### Other vagrant commands

You can SSH into the VM with `vagrant ssh`

To shutdown the VM, run `vagrant halt`

To kill the VM, run `vagrant destroy`

## Xdebug Examples

Navigate to `example.ogp` in your browser to see examples.

Turn on the telephone icon in PHPStorm and setup path mappings on first run.

After that you're off to the races! Vroom vroom.

### Vagrant+Puppet Config Generation

This was generated from [`PuPHPet`](https://puphpet.com) which is pretty awesome tool for vagrantfile+puppet generation.


### About & other info

```
Built & Maintained by @OGProgrammer

Support Your Local User Groups
http://php.ug/

Check out our PHP UG in Las Vegas, NV
http://PHPVegas.com

Support your local tech scene!
#VegasTech

Share your knowledge!
Become a speaker, co-organizer, at your local user groups.
Contribute to your favorite open source packages (even if its a README ;)

If you enjoyed this code, please support me at one of the following:

Thank you! ☺

BTC Wallet
1HNHoUz8ruQGko8vh85Jf4nXx8tpEaxUxr

ETH Wallet
0xb561e6a160c86cd5831c323b0f9ce319b56c6421

Patreon
https://www.patreon.com/ogprogrammer
```
