.. _hicFindRestSite:

hicFindRestSites
================

.. argparse::
   :ref: hicexplorer.hicFindRestSite.parse_arguments
   :prog: hicFindRestSite

Further usage
^^^^^^^^^^^^^

In case multiple restriction enzymes are used in one experiment, ``hicFindRestSite`` can be used to find restriction sites individually per enzyme. Afterwards, all output bed files should be combined. However, it should be noted that the QC report will not be correct for this specific usage.
