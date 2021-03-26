# Security Policy

## Supported Versions

All of our software projects use [Semantic Versioning](https://semver.org/) with 
version numbers of the form: MAJOR.MINOR.PATCH, where differences 
in MAJOR correspond to incompatible changes, differences in MINOR 
correspond to introduction of backwards compatible new functionality, 
and PATCH corresponds to backwards compatible bug fixes.

We release patches for security vulnerabilities.  Specifically, we patch security
vulnerabilities in the most recent release, regardless of when it was released,
as well as all MINOR releases of the current MAJOR version that were released in
the past 3 months. In the following table, let A be the current major version
number, and B is the current minor version number.

| Version | When Released | Supported |
| ------- | ------------ | ------------------ |
| A.B.x   | any time | :white_check_mark: |
| A.x.y   | past 3 months | :white_check_mark: |
| < A.x.y | | :x: |

## Reporting a Vulnerability

Please report suspected security vulnerabilities 
to: development @ cicirello org.  If the issue is confirmed, we 
will release a patch as soon as possible depending on complexity
of the issue.
