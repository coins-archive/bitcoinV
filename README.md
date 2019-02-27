
http://www.bitcoinV.org

What is BitcoinV?
----------------

The original Bitcoin (BTCV) is no longer decentralized. BitcoinV (Variable Block Rewards) solves this problem by providing incentive to the original CPU and GPU miners. Miners that secure the blockchain beyond the current difficulty level are rewarded more block rewards. Block rewards can vary from the standard block reward up to 1 MILLION times the standard block reward! Mining now becomes very interesting for an individual miner, the JACKPOT is waiting to be mined! These JACKPOT block rewards keep the blockchain decentralized and more secure.

License
-------

BitcoinV Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoinVBR/bitcoinV/tags) are created
regularly to indicate new official, stable release versions of BitcoinV Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

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