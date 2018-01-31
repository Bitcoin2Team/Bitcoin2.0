Bit integration/staging tree
=====================================


What is Bit?
----------------

Bit is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Bit uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Bit Core is the name of open source
software which enables the use of this currency. Bit is based on the infrastructure of bitcoin, with parameters optimized for a modern deployment.


License
-------

Bit is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Installation Process
-------------------

Installation of Bit requires following the corresponding "build" text at
https://github.com/litecoin-project/litecoin/tree/master/doc

After the build is done compiling, go into -datadir (./Bit) and create a text file bitcoin2.conf containing the line:

addnode=24.90.16.52:30333


Then run src/qt/bit-qt, hide synchronization window, click Help > Debug window > Console and begin mining :)

Same commands as Litecoin 0.14 , i.e. generate 10 mines 10 blocks, getmininginfo shows current block info, etc.

Click receive and send to see addresses for receiving and sending, same as Litecoin UI.
