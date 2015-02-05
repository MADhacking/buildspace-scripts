buildspace-scripts
==================

Whilst maintaining a Gentoo Linux "build server" requires considerable discipline to ensure that all the relevant files remain in sync those procedures are fairly easily automated. What is not so easily automated is the process of updating the set of binary packages produced by a "build space" ensuring that all administrative tasks are performed as if an actual user had performed the update manually.

The utilities provided in this package aim to fully automate the process of building updated binary packages in a build-space including all of the administrative tasks which would usually be performed manually by the system administrator such as removing orphaned dependencies, rebuilding broken binaries, rebuilding perl and python packages as required and ensuring that only those binary packages which are actually in use on the system are available in the package repository.

The utilities in this package are designed to work in concert with those provided in the buildserver-scripts package although they could also easily be used as stand-alone tools or incorporated into another build system. 

More information may be found at

	http://www.mad-hacking.net/software/linux/gentoo/buildspace-scripts/index.xml
	http://www.mad-hacking.net/documentation/linux/deployment/buildserver/index.xml