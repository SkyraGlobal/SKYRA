SKYRA Core
=============

Setup
---------------------
[SKYRA Core](http://skyra.org/wallet) is the original SKYRA client and it builds the backbone of the network. However, it downloads and stores the entire history of SKYRA transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run SKYRA Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/skyra-qt` (GUI) or
- `bin/skyrad` (headless)

If this is the first time running SKYRA Core (since v5.0.0), you'll need to install the sapling params by running the included `install-params.sh` script, which copies the two params files to `$HOME/.skyra-params`

### Windows

Unpack the files into a directory, and then run skyra-qt.exe.

### macOS

Drag SKYRA-Qt to your applications folder, and then run SKYRA-Qt.

### Need Help?

* See the documentation at the [SKYRA Wiki](https://github.com/SKYRA-Project/SKYRA/wiki)
for help and more information.
* Ask for help on the [SKYRA Forum](http://forum.skyra.org/).
* Join our Discord server [Discord Server](https://discord.skyra.org)

Building
---------------------
The following are developer notes on how to build SKYRA Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The SKYRA repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://www.fuzzbawls.pw/skyra/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [SKYRA](http://forum.skyra.org/) forum.
* Join the [SKYRA Discord](https://discord.skyra.org).

### Miscellaneous
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
