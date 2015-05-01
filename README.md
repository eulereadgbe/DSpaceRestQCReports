# Proposed REST API based reporting tool for DSpace

A proposed reporting tool for DSpace based on the DSpace 4.x REST api.

## Collections Filter Report

This code illustrates a mechanism to filter DSpace items by use case and item properties.

The code allows a set of use case filters to be defined.
* [Enum defining available filters to be applied to a collection of items](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/blob/master/dspace/modules/rest/src/main/java/org/dspace/rest/filter/ItemFilterDefs.java)

### Collections Filter Client

_The purpose of this client code is to illustrate how quickly a useful client application could be built by extending the REST API to support the ability to filter collections._

* [Sample Filter Client Page](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/sampleClient/index.html)
* [Sample Filter Client JS](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/sampleClient/restCommon.js)
* [Sample Client Screen Shots](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/releases/tag/v0.1)

## Metadata Query Tool

This tool allows a user to query for items based on the presence of one or more metadata fields within an item.  The tool supports 8 operators: exists, doesn't exist, equals, not equals, like, not like, matches, doesn't match.  More than one operation can be provided.

### Metadata Query Tool Client

_The purpose of this client code is to illustrate how quickly a useful client application could be built by extending the REST API to support the ability to query item metadata._


* [Sample Query Tool Client Page](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/sampleClient/query.html)
* [Sample Query Tool Client JS](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/sampleClient/restQuery.js)
* [Sample Query Tool Client Screen Shots](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/releases/tag/v0.2)


## REST API Enhancements Needed For These Reports (based on DSpace 4.3 REST API)

* [Additional code needed in the DSpace REST API to support these capabilities](https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/dspace/modules/rest/src/main/java/org/dspace/rest)

### New API Calls Needed to Support These Tools

* __/metadataregistry__ - Return the Metadata Registry
* __/filters__ - Return a set of pre-defined filters for items of interest
* __/filtered-collections__ - Return items / item counts within a collection that satisfy a filter
* __/filtered-items__ - Return items that match a metadata query

# License 
License information is contained below.

Copyright (c) 2015, Georgetown University Libraries All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. 
in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials 
provided with the distribution. THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, 
BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. 
IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) 
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
