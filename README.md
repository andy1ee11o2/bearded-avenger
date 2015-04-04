# Getting Started 
## Ubuntu
```
$ sudo apt-get install -y python-dev python-pip git
$ pip install pyzmq --install-option="--zmq=bundled"
$ pip install git+https://github.com/csirtgadgets/py-whiteface-sdk.git
$ pip install git+https://github.com/csirtgadgets/bearded-avenger.git
```

[![Build Status](https://travis-ci.org/csirtgadgets/bearded-avenger.png?branch=master)](https://travis-ci.org/csirtgadgets/bearded-avenger)

# Project Goals
* Pythonic re-write
* Break storage out from cif-router
* Enable various types of storage
* Less batch processing by cif-smrt, more streaming through HTTP and ZMQ

# Getting Involved
There are many ways to get involved with the project. If you have a new and exciting feature, or even a simple bugfix, simply [fork the repo](https://help.github.com/articles/fork-a-repo), create some simple test cases, [generate a pull-request](https://help.github.com/articles/using-pull-requests) and give yourself credit!

If you've never worked on a GitHub project, [this is a good piece](https://guides.github.com/activities/contributing-to-open-source) for getting started.

* [How To Contribute](contributing.md)  
* [Mailing List](https://groups.google.com/forum/#!forum/ci-framework)  
* [Project Page](http://csirtgadgets.org/collective-intelligence-framework/)

# COPYRIGHT AND LICENCE
Free use of this software is granted under the terms of the GNU Lesser General Public License (LGPLv3). For details see the files `COPYING` included with the distribution.
