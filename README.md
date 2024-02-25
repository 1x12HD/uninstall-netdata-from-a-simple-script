# Uninstall Netdata from a simple script



## Getting started

Netdata doesn't provide an easy way to uninstall their software. They do have "netdata-uninstaller.sh," but the issue is that people want easy ways to do things. This is why I am making a guide on how to uninstall netdata from your system using only two steps!

## How To

First, insert this command:

```python
wget -O /tmp/netdata-uninstaller.sh https://raw.githubusercontent.com/netdata/netdata/master/packaging/installer/netdata-uninstaller.sh
```
When it has finished downloading the "netdata-uninstaller.sh" file, you will insert the final command:
```python
sudo bash /tmp/netdata-uninstaller.sh --yes
```

After that, there will be questions, and if you want to permanently uninstall the whole software, then proceed to type "Y" on the following question the uninstaller will give you.
