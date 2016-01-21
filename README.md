# NOTICE

This is an _unofficial_ repository for release 2.10.2 of the GENIE Neutrino 
Event MC generator. Please see the [official webpage](http://genie.hepforge.org)
for code that is appropriate for publications-level physics analysis. 

## Versioning and Releases

The complete list of available versions of GENIE can be seen on the official
repository using the Subversion command:

    svn list http://genie.hepforge.org/svn/generator/branches

_This_ repository contains different versions of GENIE stored as tags (on the
`master` branch) and as development branches. To see the full list, use

    git ls-remote --tags

You can get a specific release with, for example

    git checkout -b R-2_10_2-br R-2_10_2

where `R-2_10_2-br` is the name of the branch you are checking the tag out
into, and `R-2_10_2` is the name of the tag you would like to get. (It is a
good idea to check out into a branch to avoid ending up in a "detached HEAD"
state.) This is the recommended way to get a specific version of GENIE.

If you would like to see the branches used to develop the tagged versions
or the development branches stored here, use

    git remote show origin

You can check out a branch directly with, for example, 

    git checkout R-2_10_2

to get the `R-2_10_2` branch.

## About GENIE

GENIE (Generates Events for Neutrino Interaction Experiments) is a universal 
object-oriented neutrino MC generator supported and developed by an [international 
collaboration](http://genie.hepforge.org/collaboration.html) of scientists whose 
expertise covers a very broad range of neutrino  physics aspects, both 
phenomenological and experimental. GENIE is currently being 
used by T2K, NOvA, MINERvA, MicroBooNE, ArgoNEUT, LAGUNA-LBNO, DUNE, INO, IceCUBE, 
NESSiE and others. 

GENIE uses several third-party HEP codes:

* [ROOT](http://root.cern.ch)
* [LHAPDF](https://lhapdf.hepforge.org)
* [Pythia](http://home.thep.lu.se/~torbjorn/Pythia.html)

GENIE also uses [log4pp](http://log4cpp.sourceforge.net) and the [Gnu 
Scientific Library](http://www.gnu.org/software/gsl/)
