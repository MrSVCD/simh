# Open SIMH for Alpine Linux

This is a modification of Open SIMH to get it to work at Alpine Linux/with musl libc.

I have built this version on:

* Ubuntu 24.04 x86_64
* Alpine 3.23.3 x86
* Alpine 3.23.3 x86_64 where PDP10-ka,-ki,-kl and -ks fails for some reason that I don't understand. PDP10 builds. (Help please)

Because of the above mentioned build failures the PDP10 variants they have been removed from the `all` part of the makefile, aka just typing `make`

ToDo: 

* Convert all the text to unix line endings
* Remove or fix Cmake since it doesn't work on Alpine Linux

# Orignial Readme.md:

# Open SIMH machine simulator

This is the codebase of SIMH, a framework and collection of computer system simulators.

SIMH was created by Bob Supnik, originally at Digital Equipment Corporation, and extended by contributions of many other people.  It is now an open source project, licensed under an MIT open source license (see [LICENSE.txt](LICENSE.txt) for the specific wording).  The project gatekeepers are the members of the [SIMH Steering Group](SIMH-SG.md).  We welcome and encourage contributions from all.  Contributions will be covered by the project license.

The Open SIMH code base was taken from a code base maintained by Mark Pizzolato as of 12 May 2022.  From that point onward there is no connection between that source and the Open SIMH code base.  A detailed listing of features as of that point may be found in [SIMH-V4-status](SIMH-V4-status.md).

## PLEASE NOTE

**Do not** contribute material taken from `github.com/simh/simh` unless you are the author of the material in question.

<a href="https://scan.coverity.com/projects/open-simh-simh">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/29458/badge.svg"/>
</a>
