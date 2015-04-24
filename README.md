# Proposed REST API based reporting tool for DSpace

A proposed reporting tool for DSpace based on the DSpace 4.x REST api.

This code illustrates a mechanism to filter DSpace items by use case and item properties.

The code allows a set of use case filters to be defined.
https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/blob/master/dspace/modules/rest/src/main/java/org/dspace/rest/filter/ItemFilterDefs.java

These filters are accessible by a new REST API verb **filters**.

Each DSpace collection can be queried by supplying one or more filters using the REST API verb **filtered-collections** with a parameter of **filters**.

### Sample Client

Code: https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/sampleClient

Screen Shots: https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/releases/tag/v0.1

### REST API Enhancements (based on DSpace 4.3 REST API)

https://github.com/Georgetown-University-Libraries/DSpaceRestQCReports/tree/master/dspace/modules/rest/src/main/java/org/dspace/rest


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
