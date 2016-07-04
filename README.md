# jaks-post-config
[Anaconda](https://rhinstaller.github.io/anaconda/intro.html) installer `%post`
configuration toolkit for [jaks (Just Another KickstartScript)](https://github.com/jas-/jaks)

## Description ##
`jaks-post-config` is a collection of shell scripts that implement a framework
for dealing with automated system configuration of any RHEL RPM based Linux
distribtion.

The project is modular; the `jaks-post-config` shell script at the root of this
repository calls any configured module to configure a host.

While the collection of tools is meant to assist the
[JAKS](https://github.com/jas-/jaks) automated installation tool, it was also
designed to facilitate system audits and en masse configuration changes.

## Features ##
The following features are implemented with each module:

*   Verbose mode
*   Test mode
*   Validation only mode
*   Restoration mode
*   Interactive restoration mode

## Contributing ##
Contributions are welcome & appreciated. Refer to the
[contributing document](https://github.com/jas-/jaks-post-config/blob/master/CONTRIBUTING.md)
to help facilitate pull requests.

## License ##
This software is licensed under the
[MIT License](https://github.com/jas-/jaks-post-config/blob/master/LICENSE).

Copyright Jason Gerfen, 2015-2016.
