This directory contains the following project and transcription artifacts

- 1 TPEN3 Project
- 1 Group of Users
- 3 Distinct Users with different roles
- 1 IIIF Manifest that is a good use case for Transcription (inbound).
- 2 IIIF Canvases each using 1 public IIIF Fixture Image.  The Canvases are included for resolvability.  
- 4 W3C Annotation Pages (TPEN3 Pages).  2 pages of transcribed text, 2 pages of translated text. (inbound)
- 8 W3C Annotations (TPEN3 Lines).  Two lines per page. (inbound)

This project is an example of an inbound IIIF Presentation API 3 Manifest that needs to be turned into a TPEN3 Project. It has multiple Canvas pages each with multiple 'layers' of Annotation. You can load the [manifest.json](https://tpen-project-examples.habesoftware.app/transcription-project/manifest.json) link in your preferred IIIF viewer.

The Manifest, Canvases, Annotation Pages, and Annotations are included as discrete objects and are individually resolvable.  In some cases objects are referenced as opposed to embedded.  It is assumed that the Annotations sent in are processed and preserved so they can be presented on the way out.
  