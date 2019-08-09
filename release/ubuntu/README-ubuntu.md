(ubuntu) What is Zing? ![Zulu Duke in a Box][1]
======================================

Azul Zing is a runtime platform that uses the Zing Virtual Machine to run Java™ technology-based applications for Linux operating systems. The Zing Virtual Machine (ZVM) allows existing Java applications to elastically scale to dozens of CPU cores and hundreds of gigabytes of memory, meaning resources can also scale up and down based on real-time demands, and without garbage collection pauses present in other Java runtimes.

Azul Zing is compliant with the Java SE standard. 

Zing is built, tested, supported, and delivered by [Azul Systems][2].

Check out [Zing Overview][3] for more information.

Centos, Debian, and Ubuntu Docker images of Zing are available in the following repositories:

  * [azul/zing-release-centos][5]
  * [azul/zing-release-debian][6]
  * [azul/zing-release-ubuntu][7]

Tags and `Dockerfile` links
===========================

Most Recent
-----------

The Zing azul/zing-release repository provides various Ubuntu Docker image tags. The most recent Zing versions of OpenJDK 11 and 8 are listed below:

 * [ `11` (*Dockerfile*)][84]

 * [ `8` (*Dockerfile*)][53]


Usage
=====

This Zing repository supports numerous versions of OpenJDK-based Java SE JDKs. Versions 11 and 8 of Zing are compliant with Java SE 11 and 8 respectively.

To run a container of your choice, use commands below as an example.

For a Zing 11 container, enter:

    docker run -it --rm azul/zing-ubuntu:11 java -version

For a Zing 8 container, enter:

    docker run -it --rm azul/zing-ubuntu:8 java -version


  [1]: https://www.azul.com/files/ZuluDocker60.gif
  [2]: http://www.azul.com/zulu
  [3]: https://www.azul.com/products/zing/
  [5]: https://hub.docker.com/r/azul/zing-release-centos
  [6]: https://hub.docker.com/r/azul/zing-release-debian
  [7]: https://hub.docker.com/r/azul/zing-release-ubuntu
  [53]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/8u222-8.40.0.25/Dockerfile
  [84]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/11.0.4-11.33/Dockerfile
  