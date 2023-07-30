# Awesome Schematron [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Schematron tools and applications.

*Please read the [contribution guidelines](contributing.md) before contributing.*

Inspired by the sheer number of other 'awesome' lists out there.

## Table of Contents

- [Specifications](#specifications)
- [Reference material](#reference-material)
- [Software](#software)
- [Applications](#applications)

## Specifications

 - [ISO Schematron 3rd Edition](https://www.iso.org/standard/74515.html) - ISO/IEC 19757-3:2020 - Information technology - Document Schema Definition Languages (DSDL) - Part 3: Rule-based validation using Schematron. For sale from ISO or a standards reseller near you.
 - [ISO Schematron 2nd Edition](http://standards.iso.org/ittf/PubliclyAvailableStandards/c055982_ISO_IEC_19757-3_2016.zip) - ISO/IEC 19757-3:2016 - Information technology - Document Schema Definition Languages (DSDL) - Part 3: Rule-based validation - Schematron. No longer available.
 - [ISO Schematron 1st Edition](http://standards.iso.org/ittf/PubliclyAvailableStandards/index.html) - ISO/IEC 19757-3:2006 - Information technology -- Document Schema Definition Language (DSDL) -- Part 3: Rule-based validation -- Schematron. No longer available.
 - [Schematron Quick Fixes](http://schematron-quickfix.github.io/sqf) -- Schematron Quick Fixes Specification

## Reference material

### Books

 - Siegel, Erik. “[Schematron: A language for validating XML](https://xmlpress.net/publications/schematron/)” Denver, CO, USA: XML Press, 2022.
 - Hedler, Marko, Manuel Montero Pineda, and Nico Kutscherauer. “[Schematron: Effiziente Business Rules für
   XML-Dokumente.](https://schematron.info)” Heidelberg: dpunkt, 2011.
 - Jelliffe, Rick. “[The Schematron Assertion Language
   1.6](https://web.archive.org/web/20061230150144/http://xml.ascc.net:80/resource/schematron/Schematron2000.html)”
   Online, October 1, 2002.
   
 ### Presentations
 
 - Bormans, Geert. “[Customisation of Akoma Ntoso using Schematron.](https://www.balisage.net/Proceedings/vol27/html/Bormans01/BalisageVol27-Bormans01.html)” Presented at Balisage: The Markup Conference 2022, Washington, DC, August 1 - 5, 2022. In Proceedings of Balisage: The Markup Conference 2022. Balisage Series on Markup Technologies, vol. 27 (2022). https://doi.org/10.4242/BalisageVol27.Bormans01.
 - Maus, David. “[Overview of Implementations](https://archive.xmlprague.cz/2022/files/presentations/Schematron.pdf)” In “[Schematron Users Meetup](https://www.xmlprague.cz/day3-2022/#sch)” at XML Prague 2022, Prague, Czech Republic, 2022.
  - Sigel, Erik. “[Schematron Query Language Binding](https://archive.xmlprague.cz/2022/files/presentations/schematron-qlb.pdf)” In “[Schematron Users Meetup](https://www.xmlprague.cz/day3-2022/#sch)” at XML Prague 2022, Prague, Czech Republic, 2022.
  - Holman, G. Ken. “[Non-programmers’ support for Schematron assertions](https://archive.xmlprague.cz/2022/files/presentations/Schematron%20Users%20Meetup%202022-06-11%2020220521-1310z.pdf)” In “[Schematron Users Meetup](https://www.xmlprague.cz/day3-2022/#sch)” at XML Prague 2022, Prague, Czech Republic, 2022.
 - Graham Tony, David Maus, Andrew Sales and Erik Siegel. “[Schematron State of the Union](https://www.xmlprague.cz/day2-2022/#sch)”  XML Prague 2022, Prague, Czech Republic, 2022.
 - Maus, David. “[Ex-Post Rule Match Selection: A Novel Approach to XSLT-Based Schematron
   Validation.](https://archive.xmlprague.cz/2019/files/xmlprague-2019-proceedings.pdf#page=79)” In XML Prague 2019
   Conference Proceedings, 57–65. Prague, Czech Republic, 2019.
 - Maus, David. “[An Introduction to Schematron and Schematron QuickFix.](https://doi.org/10.5281/zenodo.3429706)”
   Presented at the TEI Conference and Member’s Meeting 2019 (TEI 2019), Graz, Austria, 16–22 September 2019, Graz,
   September 16, 2019.
 - Maus, David. “[Schematron Report Customization.](https://www.youtube.com/watch?v=V5M_mRLoy8s)” Webinar presented at
   the Markup UK Solidarity Edition, June 10, 2020.
 - Maus, David. “[What’s in a Schematron?](https://markupuk.org/webhelp/index.html#ar02.html)” In Markup UK 2021
   Proceedings. Online, 2021.
 - Nadolu, Octavian, and Nico Kutscherauer. “[Schematron
   QuickFix](https://archive.xmlprague.cz/2016/files/xmlprague-2016-proceedings.pdf#page=93)” In XML Prague 2016
   Conference Proceedings, 81–98. Prague, Czech Republic, 2016.
 - Nadolu, Octavian. “[Taking Schematron QuickFix To The Next
   Level.](https://markupuk.org/2019/webhelp/index.html#ar09.html)” In Markup UK 2019 Proceedings, 125–34. London, UK,
   2019.
 - Sales, Andrew. "[XQS: A Native XQuery Schematron Implementation
](https://markupuk.org/2023/webhelp/index.html#ar11.html)" In Markup UK 2023 Proceedings, 146-56. London, UK, 2023.

 - *Add your Schematron book, paper, or presentation here*

## Software

Implementations of Schematron:

 - [SchXslt](https://github.com/schxslt/schxslt) - An XSLT-based Schematron processor.
 - [ml-schematron](https://github.com/ndw/ML-Schematron) - A `schematron.xqy` module that will allow you to perform Schematron validation with MarkLogic Server 
 - [ph-schematron](https://github.com/phax/ph-schematron) - Java library to validate XML documents according to Schematron rules, using 2 different engines - additionally you can validate Schematron itself. Ships with Maven plugins and an Ant task (since 4.3.0).
 - [schematron-basex](https://github.com/Schematron/schematron-basex) - XQuery module to use ISO Schematron in BaseX.
 - [schematron-exist](https://github.com/Schematron/schematron-exist) - XQuery module to use ISO Schematron in eXist.
 - [schematron](https://github.com/Schematron/schematron) - "skeleton" XSLT implementation of ISO Schematron. No longer maintained.
 - [XQS](https://github.com/AndrewSales/XQS) - native XQuery implementation of ISO Schematron. _Pre-release._
 - *Add your Schematron software here*

## Applications

 - [focheck](https://github.com/AntennaHouse/focheck) - Validates XSL-FO property value expressions in attributes by parsing expressions using parser written in XSLT 2.0 then running `assert` and `report` on results.
 - [org.doctales.terminology](https://github.com/doctales/org.doctales.terminology) - DITA-OT plugin and authoring framework for terminology management, that generates Schematron termchecker rule sets for DITA ([Demo](https://doctales.github.io/samples/termchecker-dita/terminology-DITA-en-GB.sch)) and XLIFF ([Demo](https://doctales.github.io/samples/termchecker-xliff/terminology-XLIFF-en-GB.sch)) files from DITA `<termentry>` topics.
 - *Add your Schematron application here*
