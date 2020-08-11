Tnmcoin integration/Project
===========================
Tnmcoin is an new digital currency that enables instant payments to anyone, anywhere in the world. Tnmcoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Tnmcoin is also the name of the open source software which enables the use of this currency.It Is Mined Using High-End Computers And Software By Solving Complex Algorithms.
This Is One Of The Most Recommended Cryptocurrencies Which Is Basically Advisable For Value Miners. It Is A Peer-To-Peer Transactional Digital Currency

For more information, as well as an immediately useable, binary version of the Tnmcoin client software, see
https://www.tnm-project.com




What is Tnmcoin?
----------------

Tnmcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2 minute block targets
 - ~100 million total coins
 -Subsidy is cut in half every 840000 blocks, which will occur approximately every 4 years
 - 60 coins per block
 - 2016 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Tnmcoin client sofware, see :
https://www.tnm-project.com.



Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Tnmcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/tnmcoin-project/tnmcoin/tags) are created
regularly to indicate new official, stable release versions of Tnmcoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./tnmcoin-qt_test

License
-------

Tnmcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.


Copyright (c) 2019-2020 tnm-project Developers

