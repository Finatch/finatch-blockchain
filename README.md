[Finatch Core](https://finatch.org)
===========================

[![Build Status](https://badge.buildkite.com/370fe5c79410f7d695e4e34c500b4e86e3ac021c6b1f739e20.svg?branch=master)](https://travis-ci.org/Finatch/finatch-blockchain/) [![Discord](https://img.shields.io/badge/discord-join%20chat-blue.svg)](https://discord.gg/yCggc7c)

The goal of Finatch is to create sound money that is usable by everyone in the world. We believe this is a civilization-changing technology which will dramatically increase human flourishing, freedom, and prosperity. The project aims to achieve this goal by implementing a series of optimizations and protocol upgrades that will enable peer-to-peer digital cash to scale many orders of magnitude beyond current limits.
Finatch development tree
https://finatch.com

What is Finatch?
----------------

Finatch is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Finatch uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Finatch Core is the name of open source
software which enables the use of this currency.Finatch is a PoS-based cryptocurrency.

For more information, as well as an immediately useable, binary version of
the Finatch Core software, see https://finatch.org, or read the
[original whitepaper](https://finatch.org/finatchcore.pdf).

License
-------

Finatch Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/Finatch/finatch-blockchain/tags) are created
regularly to indicate new official, stable release versions of Finatch Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Finatch.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

## Resources
1. [Website](https://finatch.org)
1. [Blog](https://blog.finatch.org)
1. [Developer Portal](https://developers.finatch.org)
1. [Discord for Q&A](https://discord.gg/yCggc7c)
1. [Community Telegram Group](https://t.me/finatch)
1. [Developer Telegram Group](https://t.me/finatch_core_developers)
1. [White Paper](https://finatch.org/finatchcore.pdf)
1. [Roadmap](https://finatch.org)

<a name="gettingstarted"></a>
## Getting Started
Instructions detailing the process of getting the software, building it, running a simple test network that produces blocks, account creation and uploading a sample contract to the blockchain can be found in [Getting Started](https://developers.finatch.org) on the [Finatch Core Developer Portal](https://developers.finatch.org).
