
# MariaDB MaxScale 1.4.3 Release Notes

Release 1.4.3 is a GA release.

This document describes the changes in release 1.4.3, when compared to
release 1.4.2.

For any problems you encounter, please consider submitting a bug
report at [Jira](https://jira.mariadb.org).

## Bug fixes

[Here is a list of bugs fixed since the release of MaxScale 1.4.2.](https://jira.mariadb.org/browse/MXS-700?jql=project%20%3D%20MXS%20AND%20issuetype%20%3D%20Bug%20AND%20resolution%20in%20(Fixed%2C%20Done)%20AND%20fixVersion%20%3D%201.4.3)

 * [MXS-700](https://jira.mariadb.org/browse/MXS-700): Segfault on startup
 * [MXS-699](https://jira.mariadb.org/browse/MXS-699): qc_mysqlembedded fails to return fields in comma expression

## Known Issues and Limitations

There are some limitations and known issues within this version of MaxScale.
For more information, please refer to the [Limitations](../About/Limitations.md) document.

## Packaging

RPM and Debian packages are provided for the Linux distributions supported
by MariaDB Enterprise.

Packages can be downloaded [here](https://mariadb.com/resources/downloads).

## Source Code

The source code of MaxScale is tagged at GitHub with a tag, which is identical
with the version of MaxScale. For instance, the tag of version X.Y.Z of MaxScale
is X.Y.Z. Further, *master* always refers to the latest released non-beta version.

The source code is available [here](https://github.com/mariadb-corporation/MaxScale).
