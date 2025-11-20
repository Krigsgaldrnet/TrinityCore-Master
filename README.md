# ![logo](https://community.trinitycore.org/public/style_images/1_trinitycore.png) TrinityCore (master)

------

[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/TrinityCore/TrinityCore.svg)](https://isitmaintained.com/project/TrinityCore/TrinityCore "Average time to resolve an issue") [![Percentage of issues still open](https://isitmaintained.com/badge/open/TrinityCore/TrinityCore.svg)](https://isitmaintained.com/project/TrinityCore/TrinityCore "Percentage of issues still open")

------

**IMPORTANT NOTES: This is not a fork of TrinityCore 11.1.0, but a <u>replication</u> of the original trinity master tree. Some files had to be fixed/rewritten because of some [malformed Author and Committer emails from 15 years! back](https://github.com/TrinityCore/TrinityCore/issues/30820).** Because Github does not allow the complete tree of a cloned repository with malformed files to be pushed to a new repository and you can not just fix the malformed files, history HAD to be rewritten.

For example commit [0d4bbd96410dfa6d9d9bf761f26ba7651da38a96](https://github.com/TrinityCore/TrinityCore/commit/0d4bbd96410dfa6d9d9bf761f26ba7651da38a96), which has been addressed here https://github.com/TrinityCore/TrinityCore/issues/30820 🫣

We could have made a fork where Github just copies the files over to a new repository but there are dozens of them and that was not in our interest for various reasons.

To make a long story short. For the above reason, for example:
Commit https://github.com/Krigsgaldrnet/TrinityCore-Master/commit/2beb472ae1bfa3a6fce0d2f1b04274deb6370fd6
in our repository now, corresponds to https://github.com/TrinityCore/TrinityCore/commit/fa75f635669df6f0aab4abef074f9e8da4b5bf06 on the original tree, and so on.

Thanks to Klaus from the [electrobutterfly](https://github.com/electrobutterfly) [repository](https://github.com/electrobutterfly/Code-Snippets-and-Scripts) to make this possible with his [repo sync script](https://github.com/electrobutterfly/Code-Snippets-and-Scripts/blob/main/repo-sync).

So, enough said, back to the original content of TrinityCore. Features below which work only in the original github repository or are for other branches have been removed.

--------------




* [Build Status](#build-status)
* [Introduction](#introduction)
* [Requirements](#requirements)
* [Install](#install)
* [Reporting issues](#reporting-issues)
* [Submitting fixes](#submitting-fixes)
* [Copyright](#copyright)
* [Authors &amp; Contributors](#authors--contributors)
* [Links](#links)



## Build Status

| master tree | [![master Build Status](https://circleci.com/gh/TrinityCore/TrinityCore/tree/master.svg?style=shield)](https://circleci.com/gh/TrinityCore/TrinityCore/tree/master) | [![master Build status](https://ci.appveyor.com/api/projects/status/54d0u1fxe50ad80o/branch/master?svg=true)](https://ci.appveyor.com/project/DDuarte/trinitycore/branch/master) | ![master GCC Build status](https://github.com/TrinityCore/TrinityCore/actions/workflows/gcc-build.yml/badge.svg?branch=master&event=push) | [![master macOS arm64 Build status](https://github.com/TrinityCore/TrinityCore/actions/workflows/macos-arm-build.yml/badge.svg?branch=master&event=push)](https://github.com/TrinityCore/TrinityCore/actions?query=workflow%3AGCC+branch%3Amaster+event%3Apush) | [![Coverity Scan Build Status](https://scan.coverity.com/projects/435/badge.svg)](https://scan.coverity.com/projects/435) |
| ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |

------



## Introduction

------

TrinityCore is a *MMORPG* Framework based mostly in C++.

It is derived from *MaNGOS*, the *Massive Network Game Object Server*, and is
based on the code of that project with extensive changes over time to optimize,
improve and cleanup the codebase at the same time as improving the in-game
mechanics and functionality.

It is completely open source; community involvement is highly encouraged.

If you wish to contribute ideas or code, please visit our site linked below or
make pull requests to our [Github repository](https://github.com/TrinityCore/TrinityCore/pulls).

For further information on the TrinityCore project, please visit our project
website at [TrinityCore.org](https://www.trinitycore.org).

## Requirements


Software requirements are available in the [wiki](https://trinitycore.info/en/install/requirements) for
Windows, Linux and macOS.


## Install

Detailed installation guides are available in the [wiki](https://trinitycore.info/en/home) for
Windows, Linux and macOS.


## Reporting issues

Issues can be reported via the [Github issue tracker](https://github.com/TrinityCore/TrinityCore/labels/Branch-master).

Please take the time to review existing issues at [Github issue tracker](https://github.com/TrinityCore/TrinityCore/labels/Branch-master)  before submitting your own to prevent duplicates.

Please take the time to review existing issues before submitting your own to
prevent duplicates.

In addition, thoroughly read through the [issue tracker guide](https://community.trinitycore.org/topic/37-the-trinitycore-issuetracker-and-you/) to ensure
your report contains the required information. Incorrect or poorly formed
reports are wasteful and are subject to deletion.



## Submitting fixes

C++ fixes are submitted as pull requests via Github. For more information on how to
properly submit a pull request, read the [how-to: maintain a remote fork](https://community.trinitycore.org/topic/9002-howto-maintain-a-remote-fork-for-pull-requests-tortoisegit/).
For SQL only fixes, open a ticket; if a bug report exists for the bug, post on an existing ticket.


## Copyright

License: GPL 2.0

Read file [COPYING](COPYING).


## Authors &amp; Contributors

Read file [AUTHORS](AUTHORS).


## Links

* [Website](https://www.trinitycore.org)
* [Wiki](https://www.trinitycore.info)
* [Forums](https://talk.trinitycore.org/)
* [Discord](https://discord.trinitycore.org/)
