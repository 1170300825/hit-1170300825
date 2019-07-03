# Contributing to hit-1170300825
hit-1170300825 is released under the Apache 2.0 license. If you would like to contribute something, or simply want to hack on the code this document should help you get started.

## Code of Conduct 
This project adheres to the Contributor Covenant [code of conduct]().By participating, you are expected to uphold this code. 

## Using GitHub Issues
We use GitHub issues to track bugs and enhancements.<br>
If you are reporting a bug, please help to speed up problem diagnosis by providing as much information as possible. 

## Reporting Security Vulnerabilities
If you think you have found a security vulnerability in Spring Boot please DO NOT disclose it publicly until we’ve had a chance to fix it. Please don’t report security vulnerabilities using GitHub issues, instead head over to our official email 1170300825@stu.hit.edu.cn.

## Sign the Contributor License Agreement
Before we accept a non-trivial patch or pull request we will need you to [sign the Contributor License Agreement](). Signing the contributor’s agreement does not grant anyone commit rights to the main repository, but it does mean that we can accept your contributions, and you will get an author credit if we do. Active contributors might be asked to join the core team, and given the ability to merge pull requests.

## Code Conventions and Housekeeping
None of these is essential for a pull request, but they will all help.  They can also be
added after the original pull request but before a merge.

* We use the https://github.com/spring-io/spring-javaformat/[Spring JavaFormat] project
  to apply code formatting conventions. If you use Eclipse and you follow the '`Importing
  into eclipse`' instructions below you should get project specific formatting
  automatically. You can also install the https://github.com/spring-io/spring-javaformat/#intellij-idea[Spring JavaFormat IntelliJ Plugin]
  or format the code from the Maven build by running
  `./mvnw io.spring.javaformat:spring-javaformat-maven-plugin:apply`.
* The build includes checkstyle rules for many of our code conventions. Run
  `./mvnw validate` if you want to check you changes are compliant.
* Make sure all new `.java` files to have a simple Javadoc class comment with at least an
  `@author` tag identifying you, and preferably at least a paragraph on what the class is
  for.
* Add the ASF license header comment to all new `.java` files (copy from existing files
  in the project)
* Add yourself as an `@author` to the `.java` files that you modify substantially (more
  than cosmetic changes).
* Add some Javadocs.
* A few unit tests would help a lot as well -- someone has to do it.
* If no-one else is using your branch, please rebase it against the current master (or
  other target branch in the main project).
* When writing a commit message please follow [these conventions](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html),
  if you are fixing an existing issue please add `Fixes gh-XXXX` at the end of the commit
  message (where `XXXX` is the issue number).
