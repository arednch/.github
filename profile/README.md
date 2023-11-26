# AREDN Switzerland

TL;DR: This is a collection of repositories used and provided as part of AREDN Switzerland.

[AREDN (Amateur Radio Emergency Data Network)](https://www.arednmesh.org/aredn-advantage) is a wireless mesh network based on 802.11 (WiFi) and uses a [customized OpenWRT firmware](https://github.com/aredn/aredn). For more details on AREDN, see https://www.arednmesh.org.

This GitHub organization contains packages developed to run on AREDN Nodes in order to support their use.

Notable are in particular the following repositories:

- [`packages`](https://github.com/arednch/packages): This is the primary repository which contains the build definitions for AREDN packages to run on the Node as well as the automated [releases](https://github.com/arednch/packages/releases).

- [`phonebook`](https://github.com/arednch/phonebook): This is the source code for the phonebook application specifically developed to act as a distributed phone directory to run on Nodes in Switzerland (it is easily adapted to run elsewhere too but will require forking/diffs).