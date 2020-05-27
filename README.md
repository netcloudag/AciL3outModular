# ACI Modular L3Out

Python Module for configuring ACI L3Outs on a Modular bases.
Currently Supported is Static- and BGP-Routing (inclusive Multicast). 
The Module Provide an abstraction Layer in Form of Python Objects and gives back 
the JSON which could be posted to the APIC.

## Getting Started

Install Module via pip install and check examples folder.

pip install --upgrade git+https://github.com/netcloudag/AciL3outModular.git

```
from L3Out import ModularL3Out
L3Out2Post = ModularL3Out.L3Out("L3Out-Name-xyz", "Tenant-Name-xyz")
etc...
print L3Out2Post.tostring()
```

### Prerequisites

What things you need to install the software and how to install them

```
Python 3.7.X
```

### Installing

```
pip install --upgrade git+https://github.com/netcloudag/AciL3outModular.git
```

## Running the tests

Simple UnitTest is under test Folder

## Contributing

Please read [CONTRIBUTING.md](https://github.com/netcloudag/AciL3outModular/blob/master/CONTRIBUTING.md) for details on our code 
of conduct, and the process for submitting pull requests to this project.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/netcloudag/AciL3outModular/tags). 

## Authors

* ** Andreas Graber ** - *Initial work*

## License

Please - see the [LICENSE.md](https://github.com/netcloudag/AciL3outModular/blob/master/LICENSE.md) file for details. 

[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/netcloudag/AciL3outModular)