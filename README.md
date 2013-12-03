TYPO3 Neos Demo Site
====================

Martin Helmich (m.helmich@mittwald.de)
Mittwald CM Service GmbH & Co. KG

Synopsis
--------

This package contains a simple TYPO3 Neos demo site that I used in a [blog article](https://blog.mittwald.de/?p=34543).

Installation
------------

Clone this repository into the directory `Packages/Sites/MH.DemoSite` (the package key should be easily changeable, you
just need to adjust the TypoScript template):

    git clone github.com:martin-helmich/neos-demosite.git Packages/Sites/MH.DemoSite
    ./flow site:import --package-key MH.DemoSite