Maven POM parent for [Indago related projects](https://github.com/fjug/Indago),
and for projects wishing to inherit the Indago environment.
[Bill of Materials](http://imagej.net/BOM).

The Indago parent POM is designed to be compatible with artefact versions used in Fiji, allowing you to directly deploy Indago projects to Fiji.

Projects that use `pom-indago` as a parent project need to
override the following configuration sections:
* `<name>`
* `<description>`
* `<url>`
* `<inceptionYear>`
* `<organization>`
* `<licenses>`
* `<developers>`
* `<scm>`
* `<issueManagement>`
* `<ciManagement>`
