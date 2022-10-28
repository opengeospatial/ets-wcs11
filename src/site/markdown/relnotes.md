# WCS 1.1.1 Test Suite Release Notes

## 1.16 (2022-10-28)

* [#74](https://github.com/opengeospatial/ets-wcs11/pull/74) - Set TEAM Engine version to 5.5.2
* [#72](https://github.com/opengeospatial/ets-wcs11/issues/72) - GetCoverage_TemporalSubset_TimePeriod_With_Resolution has problem
* [#68](https://github.com/opengeospatial/ets-wcs11/issues/68) - Add template to get an XML/JSON response via rest endpoint
* [#71](https://github.com/opengeospatial/ets-wcs11/pull/71) - Set Docker TEAM Engine version to 5.4.1

## 1.15 (2020-11-24)

* [#64](https://github.com/opengeospatial/ets-wcs11/issues/64) - wcs 111 compliance test cannot correctly parse the time from a describecoverage call
* [#65](https://github.com/opengeospatial/ets-wcs11/issues/65) - Regression: Several tests fail as syntax for RangeSubset is erroneous

## 1.14 (2020-07-01)

* [#50](https://github.com/opengeospatial/ets-wcs11/issues/50) - Enable REST API
* [#55](https://github.com/opengeospatial/ets-wcs11/issues/55) - illegal DescribeCoverage requests sent
* [#56](https://github.com/opengeospatial/ets-wcs11/issues/56) - erroneous requirement that each CoverageSummary has an abstract
* [#57](https://github.com/opengeospatial/ets-wcs11/issues/57) - wcs 1.1.1 compliance test getcapabilities issue

## 1.13 (2019-05-29)

* [#47](https://github.com/opengeospatial/ets-wcs11/issues/47) - Enable Docker support
* [#45](https://github.com/opengeospatial/ets-wcs11/issues/45) - Test wcs:GetCoverage_BoundingBox_OutOfRangeCoordinates is not covered by specification
* [#43](https://github.com/opengeospatial/ets-wcs11/issues/43) - Invalid KVP encoding of "rangesubset" parameter
* [#39](https://github.com/opengeospatial/ets-wcs11/issues/39) - Improve tests with multiple identifiers
* [#35](https://github.com/opengeospatial/ets-wcs11/issues/35) - Invalid KVP parameter "Identifier" in wcs:DescribeCoverage_Response_InterpolationMethods test
* [#34](https://github.com/opengeospatial/ets-wcs11/issues/34) - Update CTL with better information about conformance classes

## 1.12 (2017-05-10)
* [#29](https://github.com/opengeospatial/ets-wcs11/issues/29) - wcs:DescribeCoverage_Response_InterpolationMethods test is faulty
* [#31](https://github.com/opengeospatial/ets-wcs11/issues/31) - wcs:DescribeCoverage_MissingVersion test is faulty

## 1.11 (2017-02-01)
* [#26](https://github.com/opengeospatial/ets-wcs11/issues/26) - Several tests fail as syntax for RangeSubset is erroneous
* [#27](https://github.com/opengeospatial/ets-wcs11/issues/27) - Several tests fail due to a InvocationTargetException

## 1.10 (2016-11-04)
* [#20](https://github.com/opengeospatial/ets-wcs11/issues/20) - wcs:GetCapabilities_AcceptVersions_0.0.0 test is faulty

## 1.9 (2016-09-01)
* [#19](https://github.com/opengeospatial/ets-wcs11/issues/19) - xml:lang attribute not accepted in ExceptionReport element
* [#21](https://github.com/opengeospatial/ets-wcs11/issues/21) - fails if first coverage has no Identifier

## 1.8 (2016-06-02)
* [#15](https://github.com/opengeospatial/ets-wcs11/issues/15) - mistaken assumption that HTTP POST endpoints are required
* [#16](https://github.com/opengeospatial/ets-wcs11/issues/16) - The wcs:DescribeCoverage_MissingVersion test have a version parameter

## 1.7 (2016-02-23)
* [#4](https://github.com/opengeospatial/ets-wcs11/issues/4) - Using more than one ows:BoundingBox in coverage description breaks GetCoverage tests
* [#2](https://github.com/opengeospatial/ets-wcs11/issues/2) - Arithmetic operator is not defined for arguments of types (xs:string, xs:string)
* [#13](https://github.com/opengeospatial/ets-wcs11/issues/13) - Master is not building due to wrong version of dependency

## 1.6 (2016-01-29)
* [#7](https://github.com/opengeospatial/ets-wcs11/issues/7) - Error - cannot find declaration of element Capabilities

## 1.5 (2015-07-30)
- Update pom.xml to build with Maven 2 

## 1.4 (2015-03-04)

* [11](https://github.com/opengeospatial/ets-wcs11/issues/11) - Change versioning scheme 

## r3 (2015-02)

* [9](https://github.com/opengeospatial/ets-wcs11/issues/9) - Fix link to GitHub page
* [10] (https://github.com/opengeospatial/ets-wcs11/issues/10) - Remove default URL

## r2 (2015-02)

* [#3](https://github.com/opengeospatial/ets-wcs11/issues/3) - Invalid parameter value for Format
* [#1](https://github.com/opengeospatial/ets-wcs11/issues/1) - Cannot convert string to xs:decimal
* [#7](https://github.com/opengeospatial/ets-wcs11/issues/7) - Cannot find declaration of element Capabilities 

## r1 (2013-02-08)

- [config.xml]: Updated for TEAM-Engine v4
- [GetCoverage_MinimalRequest,GetCoverage_MissingIdentifier]: Fixed xpath errors 
  "Arithmetic operator is not defined for arguments of types (xs:string, xs:string)"


## r0 (2010-11-15)

- added accept_versions to getcapabilities-main (issue #339)

