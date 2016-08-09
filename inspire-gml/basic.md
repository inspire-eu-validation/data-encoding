# Basic test

**Version**: 1

**Purpose**: Verify that all documents are consistent with the standardization target of the conformance class.

**Prerequisites**

**Test method**

* Verify for each XML document that the root element is either a GML feature or a GML feature collection. For feature collections the following elements are recognised: wfs:FeatureCollection, gml:FeatureCollection, base:SpatialDataSet. Otherwise report [incorrectRoot](#incorrectRoot)

**Reference(s)**: 

* [D2.7](http://inspire.ec.europa.eu/id/ats/data-encoding/3.3/inspire-gml/README#ref_D2_7) recommendation 11

**Test type**: Automated

**Notes**

The use of the WFS 2.0 feature collection is recommended, but other feature collections (e.g. SpatialDataSet or gml:FeatureCollection) are currently allowed, too.

## Messages

Identifier  |  Message text (parameters start with '$')
---------------------------------------------------------- | -------------------------------------------------------------------------
incorrectRoot <a name="incorrectRoot"/>  |  XML document '$filename':  The root element is not a GML feature and not one of the recognised feature collections ({http://www.opengis.net/wfs/2.0}FeatureCollection, {http://www.opengis.net/gml/3.2}FeatureCollection or {http://inspire.ec.europa.eu/schemas/base/3.3}SpatialDataSet). The name of the root element is '$elementName' in namespace '$namespace'. It is recommended to use the WFS 2.0 feature collection element in INSPIRE.

## Contextual XPath references

The namespace prefixes used as described in [README.md](http://inspire.ec.europa.eu/id/ats/data-encoding/3.3/inspire-gml/README#namespaces).