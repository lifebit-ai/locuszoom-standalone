# LocusZoom Standalone

This repository is for the command line (standalone) version of LocusZoom, an application for creating regional plots from genome-wide association studies built in Python and R.

Documentation for this program is available on our wiki: http://genome.sph.umich.edu/wiki/LocusZoom_Standalone

# Status

This version of LocusZoom is no longer under active development. Bug fixes and small updates may be made, though it is unlikely.

A new web-based interactive version of LocusZoom is now available on [my.locuszoom.org](https://my.locuszoom.org/). Find information on how to use it on your own sites at the [locuszoom.js github site](https://github.com/statgen/locuszoom/).

# Releases

| Build                                                                                               | Version | Date       | Size |
|-----------------------------------------------------------------------------------------------------|---------|------------|------|
| [Program + database + LD files](https://statgen.sph.umich.edu/locuszoom/download/locuszoom_1.4.tgz) | 1.4     | 2017-05-01 | 23G  |
| [Program + database](https://statgen.sph.umich.edu/locuszoom/download/locuszoom_1.4_nold.tgz)       | 1.4     | 2017-05-01 | 16G  |
| [Program only](https://statgen.sph.umich.edu/locuszoom/download/locuszoom_1.4_srconly.tgz)          | 1.4     | 2017-05-01 | 86K  |
|                                                                                                     |         |            |      |
| [Program + database + LD files](https://statgen.sph.umich.edu/locuszoom/download/locuszoom_1.3.tgz) | 1.3     | 2014-06-20 | 10G  |
| [Program + database](https://statgen.sph.umich.edu/locuszoom/download/locuszoom_1.3_nold.tgz)       | 1.3     | 2014-06-20 | 4.3G |
| [Program only](https://statgen.sph.umich.edu/locuszoom/download/locuszoom_1.3_srconly.tgz)          | 1.3     | 2014-06-20 | 79K  |

Database contains required data for LocusZoom to function, though you can skip it if you are already creating your own.

LD files are entirely optional - you can calculate LD instead from your own genotype files (`--ld-vcf`), or not at all (`--no-ld`).

A full list of changes for each version can be found in the [changelog](docs/CHANGELOG.md).

# Contact

Contact/support options:
 * Submit an issue to the repository: https://github.com/statgen/locuszoom-standalone/issues
 * Post a message to the Google Group: https://groups.google.com/forum/#!forum/locuszoom
