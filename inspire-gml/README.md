# Conformance class: INSPIRE GML encoding (DRAFT)

This conformance class is part of the [Abstract Test Suite for the Guidelines for the encoding of spatial data (D2.7)](http://inspire.ec.europa.eu/id/ats/data-encoding/3.3).

This conformance class examines GML documents against basic requirements for the GML encoding for spatial data sets in INSPIRE. This only covers application-schema-independent, generic requirements. Requirements related to specific application schemas are part of conformance classes with a dependency on this conformance class. 

## Standardization target type

INSPIRE spatial data set encoded in GML

## Dependencies

### Direct dependencies

A direct dependency is another conformance class whose requirements must be met by the metadata record, too.

| Specification | Conformance class | Parameters | 
| ------------- | ----------------- | ---------- |
| [Geography Markup Language version 3.2.1, OGC document 07-036, same as ISO 19136:2007](#ref_GML) | [GML 3.2 documents](http://www.opengis.net/doc/IS/GML/3.2/clause/2.4) | n/a |

*Note*: An executable Test Suite for this external conformance class is available at http://cite.opengeospatial.org/teamengine/about/gml32/3.2.1/site/.

### Indirect dependencies

none

## External document references

The following abbreviations are used in the test text for referring to external documents:

Abbreviation                     | Document name
-------------------------------- | --------------------------------------------------
D2.7 <a name="ref_D2_7"></a>   | [INSPIRE Guidelines for the encoding of spatial data version 3.3](http://inspire.jrc.ec.europa.eu/documents/Data_Specifications/D2.7_v3.3.pdf)
TG DS Template <a name="ref_TG_DS_tmpl"></a>   | [INSPIRE Data Specification Template version 3.0rc3](http://inspire.jrc.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_Template_v3.0rc3.pdf)
GML 3.2 <a name="ref_GML32"/>  | [Geography Markup Language version 3.2.1, OGC document 07-036, same as ISO 19136:2007](http://portal.opengeospatial.org/files/?artifact_id=20509) 

## Test Cases

| Identifier                                                        | Status   | Test case in [TG DS Template](#ref_TG-DS_tmpl)  |
| ----------------------------------------------------------------- | -------- | ------------ |
| [Basic test](http://inspire.ec.europa.eu/id/ats/data-encoding/3.3/inspire-gml/basic)  | ready for review  | (A.6.1), A.9.5  |
| [Character encoding](http://inspire.ec.europa.eu/id/ats/data-encoding/3.3/inspire-gml/char-encoding)  | ready for review  | (A.6.1), A.9.5  |

## XML namespace prefixes <a name="namespaces"></a>

The following prefixes are used to refer to the corresponding XML namespaces in all test descriptions:

Prefix         | Namespace
-------------- | -------------------------------------------------
base           | http://inspire.ec.europa.eu/schemas/base/3.3
gml            | http://www.opengis.net/gml/3.2
wfs            | http://www.opengis.net/wfs/2.0
xsi            | http://www.w3.org/2001/XMLSchema-instance
xlink          | http://www.w3.org/1999/xlink
xml            | http://www.w3.org/XML/1998/namespace