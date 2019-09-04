# Bitwig Studio on Fedora

A script that installs Bitwig Studio on Fedora.
I forked this from digiberk who forked it from the original creator because it hadn't been updated for the latest release of Fedora.

It is now for version 3.0.2 under Fedora 30

## Installation

```bash
$ git clone https://github.com/nunodio/bitwig-fedora.git

$ cd bitwig-fedora

$ chmod +x bitwig-fedora.sh

$ sudo ./bitwig-fedora.sh -i
```

## Uninstallation

This procedure is only available if you installed Bitwig Studio with this script.

To uninstall Bitwig Studio run the **same script version/tag** used in the installation.
Example: if you installed Bitwig Studio with the script version/tag 2.2.2, use the same script version to uninstall it.

```bash
sudo ./bitwig-fedora.sh -u
```
