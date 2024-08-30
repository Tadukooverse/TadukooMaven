# TadukooMaven
Maven poms and archetypes for Tadukooverse projects.

#### Table of Contents
* [Modules](#modules)
    * [Tadukoo Base POM](#tadukoo-base-pom)
      * [Tadukoo Base Archetype](#tadukoo-base-archetype) 
      * [Tadukoo JUnit POM](#tadukoo-junit-pom)
        * [Tadukoo Library POM](#tadukoo-library-pom)
          * [Tadukoo Maven Plugin POM](#tadukoo-maven-plugin-pom)
        * [Tadukoo Parsing POM](#tadukoo-parsing-pom)
        * [Tadukoo Web Service POM](#tadukoo-web-service-pom)
        * [Tadukoo View POM](#tadukoo-view-pom)
        * [Tadukoo Form POM](#tadukoo-form-pom)
          * [Tadukoo Engine Base POM](#tadukoo-engine-base-pom)
        * [Tadukoo Program POM](#tadukoo-program-pom)
* [Current Plans](#current-plans)

## Modules
### Tadukoo Base POM
Tadukoo Base POM is the base POM.xml for all Tadukooverse Maven projects.

#### Tadukoo Base Archetype
Tadukoo Base Archetype is an archetype for Tadukooverse projects made off the 
Tadukoo Base POM.

#### Tadukoo JUnit POM
Tadukoo JUnit POM is the base POM to be used by libraries that rely on 
Tadukoo JUnit. Usually you want to rely on a POM below it that's more specific 
to your needs.

##### Tadukoo Library POM
Tadukoo Library POM is the base POM to be used by libraries in Tadukooverse.
It extends Tadukoo Maven JUnit POM, providing the dependencies for 
[Tadukoo Util](https://tadukooverse.github.io/projects/TadukooUtil.html).

###### Tadukoo Maven Plugin POM
Tadukoo Maven Plugin POM is the base POM to be used by libraries that are creating 
Maven plugins. It extends Tadukoo Maven Library POM, and provides the dependencies 
used for making Maven plugins.

##### Tadukoo Parsing POM
Tadukoo Parsing POM is the base POM to be used by parsing libraries in 
Tadukooverse. It extends Tadukoo Maven JUnit POM, providing the dependencies 
for 
[Tadukoo Parsing](https://tadukooverse.github.io/projects/TadukooParsing.html).

##### Tadukoo Web Service POM
Tadukoo Web Service POM is the base POM to be used by web services 
libraries in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing the 
dependencies for 
[Tadukoo Web Services](https://tadukooverse.github.io/projects/TadukooWebServices.html)

##### Tadukoo View POM
Tadukoo View POM is the base POM to be used by libraries or programs using 
view components in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing 
the dependencies for 
[Tadukoo View](https://tadukooverse.github.io/projects/TadukooView.html)

##### Tadukoo Form POM
Tadukoo Form POM is the base POM to be used by libraries or programs using 
form components in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing 
the dependencies for 
[Tadukoo Form](https://tadukooverse.github.io/projects/TadukooForm.html)

###### Tadukoo Engine Base POM
Tadukoo Engine Base POM is the base POM to be used by Tadukoo Engine 
within Tadukooverse. It extends Tadukoo Maven Form POM, providing the dependencies for 
[Tadukoo Look & Feel](https://tadukooverse.github.io/projects/TadukooLookAndFeel.html) 
and 
[Tadukoo GitHub](https://tadukooverse.github.io/projects/TadukooGitHub.html)

##### Tadukoo Program POM
Tadukoo Program POM is the base POM to be used by all programs run on 
the engine in Tadukooverse. It extends Tadukoo Maven JUnit POM, providing 
the dependencies for 
[Tadukoo Engine](https://tadukooverse.github.io/projects/TadukooEngine.html)

## Current Plans
Check out the [project page](https://tadukooverse.github.io/projects/TadukooMaven.html) 
for information about current plans for Tadukoo Maven.
