##Paper
===========

The paper core is taken as a basis, as well as patches from the playday team

##How To (Plugin Developers)
------
* See our API patches [here](patches/api)
* See upcoming, pending, and recently added API [here](https://github.com/orgs/PaperMC/projects/2/views/4)
* Paper API javadocs here: [papermc.io/javadocs](https://papermc.io/javadocs/)

##How To (Compiling Jar From Source)
------
To compile Paper, you need JDK 21 and an internet connection.

Clone this repo, run `./gradlew applyPatches`, then `./gradlew createMojmapBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.

To get a full list of tasks, run `./gradlew tasks`.

##How To (Pull Request)
------
See [Contributing](CONTRIBUTING.md)
