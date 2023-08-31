# TadukooMaven
Maven poms and archetypes for Tadukooverse projects.

#### Table of Contents
* [Modules](#modules)
    * [Tadukoo Maven Base POM](#tadukoo-maven-base-pom)
      * [Tadukoo Maven JUnit POM](#tadukoo-maven-junit-pom)
        * [Tadukoo Maven Library POM](#tadukoo-maven-library-pom)
          * [Tadukoo Maven Plugin POM](#tadukoo-maven-plugin-pom)
        * [Tadukoo Maven Parsing POM](#tadukoo-maven-parsing-pom)
        * [Tadukoo Maven Web Service POM](#tadukoo-maven-web-service-pom)
        * [Tadukoo Maven View POM](#tadukoo-maven-view-pom)
        * [Tadukoo Maven Form POM](#tadukoo-maven-form-pom)
          * [Tadukoo Maven Engine Base POM](#tadukoo-maven-engine-base-pom)
        * [Tadukoo Maven Program POM](#tadukoo-maven-program-pom)
* [Current Plans](#current-plans)

## Modules
### Tadukoo Maven Base POM
Tadukoo Maven Base POM is the base POM.xml for all Tadukooverse Maven projects.

#### Tadukoo Maven JUnit POM
Tadukoo Maven JUnit POM is the base POM to be used by libraries that rely on 
Tadukoo JUnit. Usually you want to rely on a POM below it that's more specific 
to your needs.

##### Tadukoo Maven Library POM
Tadukoo Maven Library POM is the base POM to be used by libraries in Tadukooverse.
It extends Tadukoo Maven JUnit POM, providing the dependencies for 
[Tadukoo Util](https://tadukooverse.github.io/projects/TadukooUtil.html).

###### Tadukoo Maven Plugin POM
Tadukoo Maven Plugin POM is the base POM to be used by libraries that are creating 
Maven plugins. It extends Tadukoo Maven Library POM, and provides the dependencies 
used for making Maven plugins.

##### Tadukoo Maven Parsing POM
Tadukoo Maven Parsing POM is the base POM to be used by parsing libraries in 
Tadukooverse. It extends Tadukoo Maven JUnit POM, providing the dependencies 
for 
[Tadukoo Parsing](https://tadukooverse.github.io/projects/TadukooParsing.html).

##### Tadukoo Maven Web Service POM
Tadukoo Maven Web Service POM is the base POM to be used by web services 
libraries in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing the 
dependencies for 
[Tadukoo Web Services](https://tadukooverse.github.io/projects/TadukooWebServices.html)

##### Tadukoo Maven View POM
Tadukoo Maven View POM is the base POM to be used by libraries or programs using 
view components in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing 
the dependencies for 
[Tadukoo View](https://tadukooverse.github.io/projects/TadukooView.html)

##### Tadukoo Maven Form POM
Tadukoo Maven Form POM is the base POM to be used by libraries or programs using 
form components in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing 
the dependencies for 
[Tadukoo Form](https://tadukooverse.github.io/projects/TadukooForm.html)

###### Tadukoo Maven Engine Base POM
Tadukoo Maven Engine Base POM is the base POM to be used by Tadukoo Engine 
within Tadukooverse. It extends Tadukoo Maven Form POM, providing the dependencies for 
[Tadukoo Look & Feel](https://tadukooverse.github.io/projects/TadukooLookAndFeel.html) 
and 
[Tadukoo GitHub](https://tadukooverse.github.io/projects/TadukooGitHub.html)

##### Tadukoo Maven Program POM
Tadukoo Maven Program POM is the base POM to be used by all programs run on 
the engine in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing 
the dependencies for 
[Tadukoo Engine](https://tadukooverse.github.io/projects/TadukooEngine.html)

## Current Plans
Check out the [project page](https://tadukooverse.github.io/projects/TadukooMaven.html) 
for information about current plans for Tadukoo Maven.
