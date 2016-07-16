![Image](extras/logo.png)


### Specs
[![Build Status](https://travis-ci.org/cesarferreira/dryrun.svg?branch=master)](https://travis-ci.org/cesarferreira/dryrun) [![Gem Version](https://badge.fury.io/rb/dryrun.svg)](http://badge.fury.io/rb/dryrun)

### Featured in
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-dryrun-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/2361)
 [![Android Weekly](https://img.shields.io/badge/Android%20Weekly-%23200-blue.svg)](http://androidweekly.net/issues/issue-200)

### Show some :heart:
[![GitHub stars](https://img.shields.io/github/stars/cesarferreira/dryrun.svg?style=social&label=Star)](https://github.com/cesarferreira/dryrun) [![GitHub forks](https://img.shields.io/github/forks/cesarferreira/dryrun.svg?style=social&label=Fork)](https://github.com/cesarferreira/dryrun/fork) [![GitHub watchers](https://img.shields.io/github/watchers/cesarferreira/dryrun.svg?style=social&label=Watch)](https://github.com/cesarferreira/dryrun) [![GitHub followers](https://img.shields.io/github/followers/cesarferreira.svg?style=social&label=Follow)](https://github.com/cesarferreira/dryrun)  
[![Twitter Follow](https://img.shields.io/twitter/follow/cesarmcferreira.svg?style=social)](https://twitter.com/cesarmcferreira)



**Try** any **android library** hosted online **directly** from the **command line**

<p align="center">
<img src="extras/usage_v4.gif" width="100%" />
</p>

## Usage
```bash
dryrun https://github.com/cesarferreira/android-helloworld
```

Wait a few seconds and the app is now opened on your phone :smiley:

### Advanced usage
```bash
$ dryrun -h                                                                                       
Usage: dryrun GIT_URL [OPTIONS]

Options
    -m, --module MODULE_NAME         Custom module to run
    -b, --branch BRANCH_NAME         Checkout custom branch to run
    -f, --flavour FLAVOUR            Custom flavour (e.g. dev, qa, prod)
    -p, --path PATH                  Custom path to android project
    -t, --tag TAG                    Checkout tag/commit hash to clone (e.g. "v0.4.5", "6f7dd4b")
    -h, --help                       Displays help
    -v, --version                    Displays the version
```

## Installation

    $ gem install dryrun

## Goodies

- Private repos can be tested too :smiley:
```
  $ dryrun git@github.com:cesarferreira/android-helloworld.git
```

- No need to cleanup after you test the library.

- No need to wait for **Android Studio** to load.

## Alternative scenario (if you don't use `dryrun`)

1. Find the github's repository url
2. Click the `download zip`
3. Extract the `zip file`
4. Open Android Studio
5. Import the project you just downloaded
6. Sync gradle
7. Run the project
8. Choose the device you want to run
9. Test all you want
10. Delete the `project folder` and the `zip file` when you don't want it anymore

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cesarferreira/dryrun.
