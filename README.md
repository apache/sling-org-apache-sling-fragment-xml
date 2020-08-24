[![Apache Sling](https://sling.apache.org/res/logos/sling.png)](https://sling.apache.org)

&#32;[![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-fragment-xml/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-fragment-xml/job/master/)&#32;[![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-fragment-xml&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-fragment-xml)&#32;[![JavaDoc](https://www.javadoc.io/badge/org.apache.sling/org.apache.sling.fragment.xml.svg)](https://www.javadoc.io/doc/org.apache.sling/org-apache-sling-fragment-xml)&#32;[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.sling/org.apache.sling.fragment.xml/badge.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.apache.sling%22%20a%3A%22org.apache.sling.fragment.xml%22)&#32;[![fragment](https://sling.apache.org/badges/group-fragment.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/group/fragment.md) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

# Apache Sling System Bundle Extension: XML APIs

This module is part of the [Apache Sling](https://sling.apache.org) project.

Adds the XML API packages to the system bundle exports.
The list of packages is derived from the packages available
in the Java 7 platform. The system bundle exporting these
packages gives no guarantee the platform provides them.
For proper setup it is suggested to either install an
extension fragment adapted to the platform or to install
regular API packages as bundles.
