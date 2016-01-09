# g8-java8-template

    A giter8 template for Java projects

# Requirements

    Install giter8 using instructions [here](https://github.com/n8han/giter8#installation).

# Use

    Generate your project:

> g8 git://github.com/timjstewart/g8-java8-template

# Maven Targets

    * exec:java - runs application in the same JVM as Maven
    * exec:exec - runs application in a new process

> Run with arguments with: mvn exec:java -Dexec.args="foo bar baz"

    * mvn javadoc:javadoc - creates target/site/apidocs/index.html
    * mvn javadoc:fix - adds javadoc comments to source files in place
    * findbugs:check
    * findbugs:findbugs - generates a findbugs report
    * findbugs:gui - displays the findbugs GUI.
  
>  Note: Java source code must be compiled.  This implies it does
>      byte-code analysis as opposed to source code analysis.

    * cobertura:cobertura - generates report at target/site/cobertura/index.html
    * mvn jdepend:generate - creates target/jdepend-report.xml
    * mvn site:site - creates target/site/jdepend-report.html
    * mvn checkstyle:checkstyle
    * taglist:taglist
    * mvn eclipse:eclipse
    * mvn source:jar

