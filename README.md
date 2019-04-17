# OGC Web Coverage Service 1.1.1 Test-Suite

The OGC Web Coverage Service 1.1.1 Test-Suite provides the Executable Test Script (ETS) to test implementations against the following specification(s):

  * OGC Web Coverage Service (WCS) Implementation Specification Corrigendum 1 (1.1.1 c1) - [OGC 07-067r2](http://www.opengeospatial.org/standards/wcs) 
  * OGC Web Service Common Implementation Specification - [OGC 06-121r3](http://www.opengeospatial.org/standards/common)
  * GML 3.1.1 common CRSs profile [05-095r1](http://www.opengeospatial.org/standards/requests/24)
  * GML 3.1.1 grid CRSs profile [05-096r1](http://www.opengeospatial.org/standards/requests/25) 

Detailed information about this test suite is available [here](http://opengeospatial.github.io/ets-wcs11).

## License

[Apache 2.0 License](LICENSE.md)

## How to build

This test is build using [Apache Maven](http://maven.apache.org/) To 
build the test suite run maven from the root directory.
   % mvn install

Follow the [TEAM ENGINE instructions](http://opengeospatial.github.io/teamengine/installation.html) to install and run the tests in TEAM ENGINE.  

## How to run the tests

#### Docker

This test suite comes with a Dockerfile which can be used to easily setup the OGC test harness with
the test suite. Details can be found on [Create Docker Image and create and start Docker Container](https://github.com/opengeospatial/cite/wiki/How-to-create-Docker-Images-of-test-suites#create-docker-image-and-create-and-start-docker-container).

#### OGC test harness

Use [TEAM Engine](https://github.com/opengeospatial/teamengine), the official
OGC test harness. The latest test suite release should be available at the
[beta testing facility](http://cite.opengeospatial.org/te2/). You can also
[build and deploy](https://github.com/opengeospatial/teamengine) the test
harness yourself and use a local installation.

## How to contribute

If you would like to get involved, you can:

* [Report an issue](https://github.com/opengeospatial/ets-wcs11/issues) such as a defect or an
enhancement request
* Help to resolve an [open issue](https://github.com/opengeospatial/ets-wcs11/issues?q=is%3Aopen)
* Fix a bug: Fork the repository, apply the fix, and create a pull request
* Add new tests: Fork the repository, implement (and verify) the tests on a new topic branch,
and create a pull request

## Mailing Lists

The [cite-forum](http://cite.opengeospatial.org/forum) is where software developers discuss issues and solutions related to OGC tests. 

## More Information

Visit the [CITE website](http://cite.opengeospatial.org/) to get more information about the CITE program and tools.

