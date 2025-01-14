---

layout: col-sidebar
title: PHP File Inclusion
author: 
contributors: Fletcher Nichols
permalink: /vulnerabilities/PHP_File_Inclusion
tags: ["vulnerability", "PHP", "File Inclusion", "PHP File Inclusion"]
auto-migrated: 1

---

{% include writers.html %}

## Description

PHP, as many other languages, allows the inclusion of files in order to
provide or extend the functionality of the current file.

## Risk Factors

TBD

## Examples

<?PHP
 include '/path/filename.php';
 include_once 'path/filename.class.php';
 require '../path/filename.inc';
 require_once 'filename.inc.php';
 ?>

## Related [Attacks](https://owasp.org/www-community/attacks/)

  - Remote file inclusion using variables from the request POST or GET

## Related [Vulnerabilities](https://owasp.org/www-community/vulnerabilities/)

  - [Vulnerability 1](Vulnerability_1 "wikilink")
  - [Vulnerabiltiy 2](Vulnerabiltiy_2 "wikilink")

## Related [Controls](https://owasp.org/www-community/controls/)

  - [Control 1](Control_1 "wikilink")
  - [Control 2](Control_2 "wikilink")

## Related [Technical Impacts](Technical_Impacts "wikilink")

  - [Technical Impact 1](Technical_Impact_1 "wikilink")
  - [Technical Impact 2](Technical_Impact_2 "wikilink")

## References

  - [CWE 98: PHP Remote File Inclusion](http://cwe.mitre.org/data/definitions/98.html).
  - [CWE 434: Unrestricted Upload of File with Dangerous Type](https://cwe.mitre.org/data/definitions/434.html)
  - [CAPEC 193: PHP Remote File Inclusion](https://capec.mitre.org/data/definitions/193.html)
  - [CAPEC 252: PHP Local File Inclusion](https://capec.mitre.org/data/definitions/252.html)

\[\[Category:FIXME|add links

In addition, one should classify vulnerability based on the following
subcategories:
Ex:\[\[Category:Error_Handling_Vulnerability|Category:Error Handling
Vulnerability\]\]

Availability Vulnerability

Authorization Vulnerability

Authentication Vulnerability

Concurrency Vulnerability

Configuration Vulnerability

Cryptographic Vulnerability

Encoding Vulnerability

Error Handling Vulnerability

Input Validation Vulnerability

Logging and Auditing Vulnerability

Session Management Vulnerability\]\]

__NOTOC__

[Category:OWASP ASDR Project](Category:OWASP_ASDR_Project "wikilink")
[Category:PHP](Category:PHP "wikilink")
[Category:Vulnerability](Category:Vulnerability "wikilink")
