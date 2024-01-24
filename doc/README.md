SmartLoopAI Core
==========

This is the official reference wallet for SmartLoopAI digital currency and comprises the backbone of the SmartLoopAI peer-to-peer network. You can [download SmartLoopAI Core](https://www.smartloopai.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run SmartLoopAI Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/smartloopai-qt` (GUI) or
- `bin/smartloopaid` (headless)

### Windows

Unpack the files into a directory, and then run smartloopai-qt.exe.

### macOS

Drag SmartLoopAI Core to your applications folder, and then run SmartLoopAI Core.

### Need Help?

* See the [SmartLoopAI documentation](https://docs.smartloopai.org)
for help and more information.
* Ask for help on [SmartLoopAI Discord](http://staysmartloopaiy.com)
* Ask for help on the [SmartLoopAI Forum](http://smartloopai.space//forum)

Building
---------------------
The following are developer notes on how to build SmartLoopAI Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The SmartLoopAI Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* See the [SmartLoopAI Developer Documentation](https://smartloopai.readme.io/)
  for technical specifications and implementation details.
* Discuss on the [SmartLoopAI Forum](http://smartloopai.space//forum), in the Development & Technical Discussion board.
* Discuss on [SmartLoopAI Discord](http://staysmartloopaiy.com)
* Discuss on [SmartLoopAI Developers Discord](http://chat.smartloopaidevs.org/)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [smartloopai.conf Configuration File](smartloopai-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
