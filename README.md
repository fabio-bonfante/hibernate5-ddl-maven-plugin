hibernate5-ddl-maven-plugin
===========================

The hibernate5-ddl-maven-plugin is a simple Maven plugin for creating SQL DDL
files for JPA entities. The plugin uses Hibernates API for SchemaExport. The
plugin is available from Maven Central.

Please note that this plugin is *not* an official Hibernate tool. It was created
because I needed the functionality provided by this plugin for several projects.

## Compatibility with Java Versions

The different plugin variants embeded the latest version of the branch of 
Hibernate indicated by the artifact name of the plugin. For example the
hibernate52-ddl-maven-plugin uses the latest version of the 5.2 branch.

Only Hibernate 5.4 and later are compatible with Java 9 or newer. Therefore
the following plugin variants work only with Java 8:

* hibernate50-ddl-maven-plugin
* hibernate51-ddl-maven-plugin
* hibernate52-ddl-maven-plugin
* hibernate53-ddl-maven-plugin
* hibernate54-ddl-maven-plugin

## Reporting issues

If you have any issues please report them on Github: https://github.com/jpdigital/hibernate5-ddl-maven-plugin/issues 
In most cases it is really helpful if include an example demostrating the issue. Please note that issues
without an example may be closed *without* any comment.

## Supporting the project

If you find this project helpful please you can support the project using 
[Paypal](https://paypal.me/jenspelzetter).

## News

### 2018-05-16: Version 2.2.0

Starting with this version only specific properties from the persistence.xml 
file are passed to Hibernate for creating the database schema. The properties
can be customized. More details can be found in the documentation.

### 2017-12-22: Version 2.1.0

Only minor bugfixes and some code cleanup since version 2.1.0-beta.1.

### 2017-09-16: Version 2.1.0-beta.1

This release adds some features requested by users of the plugin. The first
new feature is the option to use custom dialects. Also it is now possible
to customise the name of the output files and the output path (Issue #11).

This release is a beta version which means that there might be some bugs. Also
there are things in the code which need to be addressed before the final release.

### 2017-06-10: Version 2.0.0

Starting with version 2.0.0 the plugin is provided in different variants build
against the most current Hibernate versions. For example, 2.0.0 is available
in three variants: One build against the latest version of Hibernate 5.0
(Hibernate 5.0 is used in Wildfly 10.1) one for the lastest version of the 5.1 branch
one for the lastest version of the 5.2 branch.

## Code Repository

The code is available at
[GitHub](http://github.com/jpdigital/hibernate5-ddl-maven-plugin) at
<http://github.com/jpdigital/hibernate5-ddl-maven-plugin>. The
[projects web site](http://jpdigital.github.com/hibernate5-maven-plugin) is also
available on GitHub at <http://jpdigital.github.io/hibernate5-ddl-maven-plugin>.
