# Mono.Options.Sources.nupkg

Source only package.

Prepare
-------

* mono: install `libxslt`
* `git checkout https://github.com/gcsa22/remotes.git`
* `git checkout https://github.com/gcsa22/Mono.Options.Sources.git`

Build
-----

* msbuild Mono.Options.targets
or
* XSLTPROC=xsltproc xbuild Mono.Options.targets

