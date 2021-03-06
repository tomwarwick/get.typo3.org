Release Notes for TYPO3 CMS 4.5.40
==================================

This document contains information about TYPO3 CMS 4.5.40 which was
released on February 19th, 2015.

News
----

This release is a combined bug fix and security release.

Notes
-----

Due to a critical security issue found in the TYPO3 CMS Core, there was
a release of TYPO3 CMS 4.5.40.\
Find more details in the security bulletin:
<https://typo3.org/teams/security/security-bulletins/typo3-core/typo3-core-sa-2015-001/>

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    3a0b4be40e8ae7ab5df3c61cb046f5fa  blankpackage-4.5.40.tar.gz
    7f49f571dbf5b9ce252ae146945bdd01  blankpackage-4.5.40.zip
    a2ac752f2d944486b9d7404c91c3d86e  dummy-4.5.40.tar.gz
    7d329f02639eba9418a4caa6c12adc76  dummy-4.5.40.zip
    810390766259e8580d8b421a7eb71065  introductionpackage-4.5.40.tar.gz
    708cb851ea08b682280be8143f6d4531  introductionpackage-4.5.40.zip
    71dcee3c9171fa7fcb21718ff869636d  typo3_src+dummy-4.5.40.zip
    75dc19184abfec84c384f31a7b353b6a  typo3_src-4.5.40.tar.gz
    03bf82bfe10f13022af80f038d75fe4e  typo3_src-4.5.40.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changes
-------

Here is a list of what was fixed since
[4.5.39](TYPO3_CMS_4.5.39 "wikilink"):

    2015-02-19  1b8a673                  [RELEASE] Release of TYPO3 4.5.40 (TYPO3 Release Team)
    2015-02-19  3fbd91c  #65113          [SECURITY] Prevent login with semi-empty values (Nicole Cordes)
    2015-01-29  6cf78f6  #64597          [TASK] Update TYPO3 copyright in all branches (Benjamin Mack)
    2015-01-29  38e1cb1  #64573          [BUGFIX] Travis tests for PHP 5.5 (Stephan Großberndt)
    2015-01-19  fc33980                  [TASK] Post travis notification to #typo3-cms-coredev channel (Helmut Hummel)
    2015-01-15  c7615b6  #63896          [BUGFIX] Fix regression in prefixLocalAchors feature (Helmut Hummel)
    2014-12-17  583d1bf  #59186          [BUGFIX] Add case insensitive flag to trustedHostsPattern (Dietrich Heise)
    2014-12-10  b2c673b                  [TASK] Set TYPO3 version to 4.5.40-dev (TYPO3 Release Team)


