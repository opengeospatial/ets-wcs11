# Overview

This executable test suite is based on the following OGC specifications:

  * [OGC Web Coverage Service (WCS) Implementation Specification Corrigendum 1 (1.1.1 c1)](http://www.opengeospatial.org/standards/wcs) (OGC 07-067r2)
  * [OGC Web Service Common Implementation Specification](http://www.opengeospatial.org/standards/common) (OGC 06-121r3)
  * [GML 3.1.1 common CRSs profile ](http://www.opengeospatial.org/standards/requests/24)(05-095r1)
  * [GML 3.1.1 grid CRSs profile ](http://www.opengeospatial.org/standards/requests/25) (05-096r1)

This test suite is based on the following Abstract Test Suite (ATS): [ats.html](ats.html)


## What is tested

Only the protocol is tested.

  * GetCapabilities, GET KVP and POST XML encodings
  * DescribeCoverage, GET KVP and POST XML encodings
  * GetFeature, GET KVP and POST XML encodings

Each encoding is optional except for the GetCapabilities GET KVP encoding. The
optional encodings are only tested when the GetCapabilities response indicates
that the encoding is supported.

The user is prompted for the end point URL of the server. If there is no
server at that location, the testing stops. If the GetCapabilities response
indicates that the UpdateSequence attribute is supported, then the user is
prompted to enter extreme values for the UpdateSequence.

## What is not tested

  * The coverage returned by a GetCoverage request
  * The Output and GridCRS
  * POST SOAP encodings

## Test data

There is no test data for this implementation of the WCS 1.1.1 executable test
suite. The provision of test data awaits a WCS encoding profile to be adopted
by the OGC. At this time, there are no adopted encoding profiles. See OGC
07-067r2 subclause 9.3.2.2.

## Namespaces
There are two namespaces used by the WCS.
ows
http://www.opengis.net/ows/1.1
wcs
http://schemas.opengis.net/wcs/1.1.1

## Schemas
The schemas for ows can be found at <http://schemas.opengis.net/ows/1.1.0>.
Note that owsExceptionReport as published does not validate. For these tests,
the xml:lang attribute has been removed.
The schemas for wcs do not validate and are not published on
<http://schemas.opengis.net/wcs>. Instead they can be found here:
[wcs111.zip](wcs111.zip).

## Release Notes
Release notes are available from the [relnotes.html](relnotes.html).
