---
layout:   post
title:    (03) Which command line options are available?
category: pswgen
---

### User Language

PswGen starts in English or German depending on your system settings, unless overridden by this JVM option:

`-Duser.language={en|de}`

How to set a JVM option with Launch4j? Create a file named PswGen.l4j.ini in your PswGen installation directory containing for example:

`# Launch4j runtime config`
`-Duser.language=en`

### Disable splash screen

From PswGen 1.5.6 till 1.7.5 there was a splash screen shown on startup unless disabled by this command line option:

`--l4j-no-splash`

See [Launch4J runtime options](http://launch4j.sourceforge.net/docs.html#Runtime_options) for more information.

### Services file

PswGen stores you login information in a file called `services.xml` in the installation directory, unless overridden by this command line option:

`-services <filepath>`
