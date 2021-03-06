Release Notes for TYPO3 CMS 6.1.11
==================================

This document contains information about TYPO3 CMS 6.1.11 which was
released on September 23rd, 2014.

News
----

This release is a bug fix release.

Notes
-----

This is part of a combined release of TYPO3 CMS 4.5.36, 6.1.11 and
6.2.5.

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    4e321d16c78983457423210ac90331ac  blankpackage-6.1.11.tar.gz
    23eff6578586911ec9736979dc97b38c  blankpackage-6.1.11.zip
    ee3f89e2385f4c22ba85c0940d6ec51a  dummy-6.1.11.tar.gz
    55b3269f8d6607a80676920935e15051  dummy-6.1.11.zip
    7546c27ddb67d87a29b18f1e6ba81253  typo3_src+dummy-6.1.11.zip
    151111201b3c0c7afb687a21c2651b06  typo3_src-6.1.11.tar.gz
    62ca1d147337da3c2eb4ed894720c5dd  typo3_src-6.1.11.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changes
-------

Here is a list of what was fixed since
[6.1.10](TYPO3_CMS_6.1.10 "wikilink"):

    2014-09-23  63ef9fc                  [RELEASE] Release of TYPO3 6.1.11 (TYPO3 Release Team)
    2014-09-20  c72e901  #36822          [BUGFIX] Invalid shortcut target on translated pages (Oliver Hader)
    2014-09-18  ca5de2e  #45834          [BUGFIX] Transfer curlProxyServer to new HTTP settings (Ernesto Baschny)
    2014-09-11  65b0018  #50396          [BUGFIX] RootlineUtility wrongly handles group-type fields (Francois Suter)
    2014-09-05  4bd9c6d  #61135          [BUGFIX] indexed_search: in some cases indexing does not work (Samir Rachidi)
    2014-08-25  571b782  #55707          [TASK] Missing stdWrap for select.recursive TypoScript property (Matthias Kappenberg)
    2014-08-23  30630b1  #60199          [BUGFIX] Collect correct information on elements in page (Jigal van Hemert)
    2014-08-13  6234622  #51572          [BUGFIX] Prevent uninstall of an extension during update (Nicole Cordes)
    2014-08-06  acb06c1  #60613          [BUGFIX] Fix Extbase language fallback in query parser (Helmut Hummel)
    2014-07-29  c517f74  #44795          [BUGFIX] Avoid superfluous IRRE child record duplication (Alexander Stehlik)
    2014-07-26  4f7a0f3  #60595          [BUGFIX] Add use-statement for GeneralUtility (Stefan Neufeind)
    2014-07-25  250b03b  #50566          [BUGFIX] Menu-links generate two empty spaces at closing anchor (Stefan Neufeind)
    2014-07-08  66d2354  #59587          [BUGFIX] Followup to CacheBackend patch (Markus Klein)
    2014-07-08  072f355  #59587          [BUGFIX] Too many tags by identifier in CacheBackends (Alexander Opitz)
    2014-07-08  36debe4                  [TASK] Set TYPO3 version to 6.1.11-dev (TYPO3 Release Team)


