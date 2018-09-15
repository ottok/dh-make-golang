% DH-MAKE-GOLANG(1) 2015-07-26

# NAME

dh-make-golang - automatically creates Debian packaging for Go packages

# SYNOPSIS

**dh-make-golang** [ *flags* ] *package*

**dh-make-golang** search *pattern*

# DESCRIPTION

dh-make-golang is a tool to automatically create Debian packaging for Go
packages. Its goal is to automate away as much of the work as possible when
creating a Debian package for a Go library package.

# EXTRA COMMANDS

**search**

Searches the Debian archive for binary packages of Go libraries with import
paths matching the given pattern. Uses Go's default regexp syntax
(https://golang.org/pkg/regexp/syntax).

# OPTIONS

Run dh-make-golang -help for more details.

# AUTHOR

This manual page was written by Michael Stapelberg <stapelberg@debian.org>,
for the Debian project (and may be used by others).
