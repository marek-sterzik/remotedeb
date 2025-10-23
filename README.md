# remotedeb

`remotedeb` is an easy-to-use script depending only on minimal requirements being able to remotely install debian packages via an ssh channel.

## requirements

Local site (commander):

* bash
* ssh
* sshpass

Remote site (slave):

* bash
* perl
* sudo

## installation

No installation needed. Just download the script [remotedeb](remotedeb), add executable rights and use.
You may also copy the script to some directory in PATH so that the command becomes a system-wide command.


## usage

Use `./remotedeb --help` for help and for the list of supported options.


## example

```sh
./remotedeb --ask-sudo-password --ask-ssh-password user@remote.example.com /local/path/to/deb/package_1.5.3_all.deb
```
