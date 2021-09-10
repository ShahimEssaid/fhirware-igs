## Introduction

This repository simply holds copies of IG outputs to simplify local access and sharing between team members. The "IG outputs" are the files available on a download page from an IG site. Only official and versioned releases are included. Also, this content should not be considered authoritative in any way. Authoritative content should be obtained from the official IG sites.

In general, content is organized under a self-descriptive directory name to indicate the location from which it was copied. Each IG directory will also have a README file that has additional notes if needed. I'm starting with organizing the content with a hierarchy of location-folder/IG-name-folder/version-folder/content-folders but a different structure might be adopted later if this initial layout is not that helpful.

## Sources of IG content

The IGs included here are based on my needs in various projects. Feel free to fork this repo to add additional IGs, and submit a PR if you think others might find them useful.

When I find an IG of interest, I try to see if the published site lists official releases. These are usually listed on a "Publication History" page. If an IG has this page, I follow the version links to the official/permanent publication site and copy the content from that site.  The location folder will try to be self-descriptive to indicate where the IG's content was found, and the README file might have additional information.

### Starting places

The following are starting sites for finding FHIR IGs

* The FHIR build index page found here: http://build.fhir.org/ig/HL7
* The FHIR registry http://www.fhir.org/guides/registry
* The FHIR wiki page https://confluence.hl7.org/display/FHIR/IGs+from+other+Organizations
* US IGs https://www.hl7.org/fhir/us/
* International IGs http://hl7.org/fhir/uv/

## IG directories

The following directories might be found under each IG version directory

* `npm-package` for the NPM package content of an IG, if available.
* `conformance-json` for JSON based definitions. These are the conformance resources for an IG from a download link from the IG site.
* `conformance-xml` as above but XML
* `examples-json` for files provided with the examples download link.
  * However, these downloads also contain an additional copy of conformance resources with a slightly different formatting. Whenever I notice this, I try to make an effort to find these and move them to the `examples-json-conformance` but consider this effort as a WIP and you might need to look in both folders if the file you're looking for is missing in one of them.
* `examples-xml` as above but for XML
* 
