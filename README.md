# cedar-parent

[![Build Status](https://travis-ci.com/metadatacenter/cedar-parent.svg?branch=master)](https://travis-ci.com/metadatacenter/cedar-parent)

Parent project for all CEDAR Java-based components

This repository contains a POM that specifies configuration and dependency version information for all Java-based CEDAR components.
The [CEDAR project repository](https://github.com/metadatacenter/cedar-project) contains a POM that can be used to build these components.

#### Building and Installing

To build you must have the following items installed:

+ [Java 17](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
+ A tool for checking out a [Git](http://git-scm.com/) repository.
+ Apache's [Maven](http://maven.apache.org/index.html).

Get a copy of the latest code:

    git clone https://github.com/metadatacenter/cedar-parent.git

Change into the cedar-parent directory:

    cd cedar-parent 

Then build it with Maven:

    mvn clean install

#### Questions

If you have questions about this repository, please subscribe to the [CEDAR Developer Support
mailing list](https://mailman.stanford.edu/mailman/listinfo/cedar-developers).
After subscribing, send messages to cedar-developers at lists.stanford.edu.


