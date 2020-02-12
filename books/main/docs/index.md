# *openLilyLib* Contributor's Guide

This is the Contributor's Guide for [openLilyLib](https://openlilylib.org), an
extension framework for the [GNU LilyPond](http://lilypond.org) notation
software. Work on this CG has begun in February 2020, and it is considered work
in progress until further notice.

## Outline

Working on *openLilyLib* (a.k.a. *OLL*) can be grouped into three different
areas, which are covered in corresponding “sections” in this CG. Direct links to
the various sections are provided at the bottom of the left-hand navigation
column on each page.

### Writing / Working on Packages

Goto section: [Writing Packages](packages/index.html) |

*openLilylib* packages are essentially collections of LilyPond functionality
which are wrapped in a rather thin layer of package interface code. Creating new
packages is pretty straightforward, and working on an existing package is just
as difficult as the actual code is.

However, usually packages make use of
[oll-core](https://openlilylib.org/oll-core)'s functionality, so this is
something to be studied, as well as the mechanisms of publishing packages.

### Writing / Working on Package Documentation

Goto section: [Documentation](documentation/index.html) |

Working on the documentation has three flavours:

* Authoring documentation for a package
* Fixing/editing existing documentation
* Working on the documentation infrastructure itself

### Working on the Core Functionality

Goto section: [Working on the core](core/index.html) |

Working on *openLilyLib's* core is a particularly important issue, which
requires a deep understanding of [oll-core](https://openlilylib.org/oll-core)'s
code base and its integration in LilyPond itself.
