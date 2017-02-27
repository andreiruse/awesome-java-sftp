# Awesome Java SFTP libraries [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

_Inspired by [Awesome Java](https://github.com/akullpp/awesome-java)_

A more-or-less curated list of Java SFTP libraries:

# SFTP Servers

## Apache
* [Apache Mina SSHD](https://github.com/apache/mina-sshd) - Java library to support SSH servers and clients.

# SFTP Clients
## JSch based
* [Original JSch](http://www.jcraft.com/jsch/) - Original website. Library is outdated (using Java Vectors, etc). No clear way to contribute changes back to it. Also, lacking good documentation.
* [Original JSch - GitHub mirror](https://github.com/shubhamrajvanshi/JSch)
* [JSch with native Win32 Kerberos support](https://github.com/joekhoobyar/jsch-sspi) - Last updated 5 years ago.
* [Original JSch with example usages](https://github.com/frankhanner/jsch-SSH-example) - This is really useful since the original JSch library lacks proper JavaDocs.
* [Original JSch with JavaDocs](https://github.com/ePaul/jsch-documentation). 
* [JSch-extension](https://github.com/lucastheisen/jsch-extension) - Extension of the original JSch library, providing multiple session management, and simplified interfaces for sftp/scp, tunneling via SSH, and general command execution.
* [JSch-NIO](https://github.com/lucastheisen/jsch-nio) - A nice port of the JSch library based on the Java NIO classes. This exposes the SFTP file system as a Java NIO `FileSystem` object, providing an useful way of interacting with the server, especially when handling connections to multiple types of remote servers.
* [SSHWrap](https://github.com/jdcasey/sshwrap) - A wrap around JSch allowing easier execution of commands via SFTP/SFTP. Last updated 5 years ago.
* [vngx-JSch](https://github.com/vngx/vngx-jsch) - An update to the original JSch library, to use Java 6 features.  Includes JavaDocs, Maven build support, and many functional improvements

## Others
* [sshj](https://github.com/hierynomus/sshj) - An up-to-date library including SSH, SCP and SFTP support, with decent set of examples.

# Contributing

Contributions are very welcome. To propose a change, please fork the repository, then create a Pull Request to merge your change back into this repo.
