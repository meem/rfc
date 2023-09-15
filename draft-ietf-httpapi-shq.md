---
###
# Internet-Draft Markdown Template
#
# Rename this file from draft-todo-yourname-protocol.md to get started.
# Draft name format is "draft-<yourname>-<workgroup>-<name>.md".
#
# For initial setup, you only need to edit the first block of fields.
# Only "title" needs to be changed; delete "abbrev" if your title is short.
# Any other content can be edited, but be careful not to introduce errors.
# Some fields will be set automatically during setup if they are unchanged.
#
# Don't include "-00" or "-latest" in the filename.
# Labels in the form draft-<yourname>-<workgroup>-<name>-latest are used by
# the tools to refer to the current version; see "docname" for example.
#
# This template uses kramdown-rfc: https://github.com/cabo/kramdown-rfc
# You can replace the entire file if you prefer a different format.
# Change the file extension to match the format (.xml for XML, etc...)
#
###
title: "Serialization for Hypertext Queries"
abbrev: "SHQ"
category: info # or standards-track?

docname: draft-ietf-httpapi-shq-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: AREA
workgroup: WG Working Group
keyword:
 - TODO
venue:
  group: HTTP-API WG
  type: Working Group
  mail: WG@example.com
  arch: https://example.com/WG
  github: USER/REPO
  latest: https://example.com/LATEST

author:
 -
    fullname: Peter Memishian (meem) and Dan Hudlow
    organization: IBM
    email: meem@ibm.com, dhudlow@us.ibm.com

normative:

informative:

https://hudlow.github.io/query-parse-suite/

--- abstract

  This document comprehensively specifies how to parse and interpret HTTP query
  strings to facilitate interoperability.
  
--- middle

# Introduction

  Despite being an essential aspect of modern HTTP APIs, the HTTP query string
  is woefully under-specified. As a result, web frameworks have made ad-hoc and
  often surprising choices for how to parse and interpret the contents of a query 
  string. This results in wide-ranging interopability problems which ultimately
  hinder the adoption, robustness, and evolution of HTTP-based APIs.

  This document describes how to parse and interpret HTTP query strings in a
  manner that is compatible with RFC3986 and is informed by experimentation with
  a wide variety of popular web frameworks. This document does not prescribe an
  implementation, but aims to be straightforward to implement and verify
  conformance.
 
# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
