What is Zing? ![Java Duke in a Box][1]
======================================

Azul Zing is a runtime platform that uses the Zing Virtual Machine to run Java™ technology-based applications for Linux operating systems. The Zing Virtual Machine (ZVM) allows existing Java applications to elastically scale to dozens of CPU cores and hundreds of gigabytes of memory, meaning resources can also scale up and down based on real-time demands, and without garbage collection pauses present in other Java runtimes.

Azul Zing is compliant with the Java SE standard. 

Zing is built, tested, supported, and delivered by [Azul Systems][2].

Check out [Zing Overview][3] for more information.

Centos and Debian Docker images of Zing are available in the following repositories:

  * [smetsys1uza/zing-centos][5]
  * [smetsys1uza/zing-debian][6]

Tags and `Dockerfile` links
===========================

Most Recent
-----------

The Zing smetsys1uza/zing repository provides various Ubuntu Docker image tags. The most recent Zing versions of OpenJDK 11 and 8 are listed below:

 * [`11.0.3-19.07.0.0`, `11`][52]

 * [`8u222-19.07.0.0`, `8`, `latest`][53]

 * [`7u232-19.07.0.0`, `7`, `latest`][54]


Usage
=====

This Zing repository supports numerous versions of OpenJDK-based Java SE JDKs. Versions 11 and 8 of Zing are compliant with Java SE 11 and 8 respectively.

To run a container of your choice, use commands below as an example.

For a Zing 11 container, enter:

    docker run -it --rm smetsys1uza/zing:11 java -version

For a Zing 8 container, enter:

    docker run -it --rm smetsys1uza/zing:8 java -version


  [1]: https://www.azul.com/files/ZuluDocker60.gif
  [2]: http://www.azul.com/zing
  [3]: https://www.azul.com/products/zing/
  [5]: https://hub.docker.com/r/smetsys1uza/zing-centos
  [6]: https://hub.docker.com/r/smetsys1uza/zing-debian
  [52]: https://github.com/alex01t/zing/blob/master/ubuntu/11.0.3-19.07.0.0/Dockerfile
  [53]: https://github.com/alex01t/zing/blob/master/ubuntu/8u222-19.07.0.0/Dockerfile
  [54]: https://github.com/alex01t/zing/blob/master/ubuntu/7u232-19.07.0.0/Dockerfile
  
