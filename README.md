# DITAStyleSheets
## Introduction
This repository and project are for the development of a consistent WCAG 2.1 AA publication template for OxygenXML WebResponsive output.
## Core technologies
* CSS
* LESS
* HTML5
* DITA
## Approach
1. Where possible, use CSS (authored in LESS) to achieve accessible pages
1. If necessary, amend the core templates in line with Oxygen guidelines, avoiding dependence on a specific version of OxygenXML
1. As a last resort, post process with XSLT or JavaScript
## Target releases

|Release|Features|Status|
|:------|:-------|:-----|
|Alpha|Basic branding|Complete|
|Private Beta - Early February|Web Accessible to WCAG 2.1 AA|Completed|
||Hosted on Beta Data Dictionary domain|Blocking|
|Public Beta - Early March|Web Accessible to WCAG 2.1 AA and Schema.org|Blocked|
|                         |Refactored navigation||
|Live|In line with user feedback||
## Background information
### File types
|Extension|Name|Use|
|:------|:-------|:-----|
|.scenarios|Transformation or Validation Scenarios|An XML file describing the transformation scenario
|.opt|[Template Descriptor File](https://www.oxygenxml.com/doc/versions/22.1/ug-webhelp-responsive/topics/whr_publishing_template_contents.html)|Each publishing template includes a descriptor file that defines the meta-data associated with template. It is an XML file with certain elements that defines all the resources included in a template (such as CSS files, images, JS files, and transformation parameters)|
|.less|[Leaner Style Sheets](http://lesscss.org/)|Less is a backwards-compatible language extension for CSS.  It defines the look and feel of the template but not the structure|
