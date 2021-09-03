# Builds

This repository holds a list of builds between all repository projects as of January 1st, 2021. Licensing for each build stored here adheres to the specific license put on the associated source. There is no warranty or liability for anything that occurs within the distributions on this site. Please see the wiki for accessing the repository.

# Versioning Schema

These projects use [Semantic Versioning][semver] as their version number. The following will document pre-release and build metadata identifiers and how they are used in the projects.

| Identifier | Description |
| :---: | :---: |
| -a | An alpha build of the project. All projects start off in the alpha stage. |
| -b | A beta build of the project. Once projects move out of alpha, they become part of the beta stage. At this point, most of the class names are stable. |
| -rc | A release candidate build of the project. Once projects move out of beta, they become part of the release candidate stage. At this point, all class and most method signatures are stable with mainly testing and verification of quality left to be done. |
| -final | A final build of the project. That project will never again be worked on. |
| -u | A project whose artifact id will be reused. This artifact id can and will be used in another project which may or may not have any relation to the original. Note that all projects with this tag are most likely final as well. | 

# Project Versions

| Name | Artifact Id | Version | Maven Central |
| :--- | :---: | :---: | :---: |
| [Codecable][codecable] | codecable | 1.1.0 | ✔️ |
| [Codecable - Minecraft][codecable] | codecable-minecraft | 1.1.0 | ✔️ |
| [Consumability][functionality] | consumability | 1.0.0 | ✔️ |
| [Functionality][functionality] | functionality | 3.0.0 | ✔️ |
| [Functionality - All][functionality] | functionality-all | 1.0.0 | ✔️ |
| [Operating][functionality] | operating | 1.0.0 | ✔️ |
| [Predicating][functionality] | predicating | 1.0.0 | ✔️ |
| [Throwability][functionality] | throwability | 1.0.0 | ✔️ |

# End of Life Projects

| Name | Artifact Id | Version | Maven Central |
| :--- | :---: | :---: | :---: |
| [Aritiality][functionality-old]* | aritiality | 2.0.0-final | ✔️ |
| [Callability][functionality-old]** | callability | 2.2.0-final | ✔️ |
| [Functionality][functionality-old]*** | functionality | 2.2.0-ufinal | ✔️ |
| [Functionality - Core][functionality-old]* | functionality-core | 1.0.0 | ❌ |

\* [Aritiality][functionality-old] and [Functionality - Core][functionality-old] are deprecated and final. Project is separated into [Functionality][functionality], [Consumability][functionality], and [Operating][functionality].  
\*\* [Callability][functionality-old] is deprecated and final. Project has been moved to [Throwability][functionality].  
\*\*\* The original [Functionality][functionality-old] project is deprecated and final. From version 3.0.0 onwards, the artifact id will be repurposed.

[semver]: https://semver.org/
[functionality-old]: https://github.com/ChampionAsh5357/Functionality/tree/1/2.x
[functionality]: https://github.com/ChampionAsh5357/Functionality
[codecable]: https://github.com/ChampionAsh5357/Codecable
