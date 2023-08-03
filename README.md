# version-compare

## Prerequisites

- meld

You can install meld by [macPorts](https://www.macports.org/install.php) or [dmg file](http://meldmerge.org/)
And then add the path of meld to your PATH environment variable.

```bash
export PATH=$PATH:/Applications/Meld.app/Contents/MacOS
```

## Usage

```bash
./version-compare
```

It will instruct you to input what you want to compare. like this example:

```bash
➜  version-compare git:(master) ✗ ./version-compare

Please enter the harvester repo directory:
~/workspace/harvester/dashboard

Please enter the target branch:
upstream/master

Please enter the head branch:
master
```

Or you can also save the input to a file (/config) and use it as input.

```bash
repo_dir=~/workspace/harvester/dashboard
target=upstream/master
head=master
```
