## [Donny Advanced]- Developed by [LlmDl](https://github.com/LlmDl)

___

<p><img align=right src="https://user-images.githubusercontent.com/879756/65964696-19d6b300-e423-11e9-9cb0-d193225ee40f.png">
I took over from ElgarL after MC 1.8 was released. Past developers have included: Shadeness, FuzzieWuzzie, ElgarL. 
With help coming from other developers from time to time including dumptruckman, ole8pie, SwearWord, gravypod, andrewyunt and more.

Towny is one of the oldest still-in-development plugins for Minecraft. It was created by Shadeness for the now-defunct server platform called hMod.

It is the second-oldest land protection plugin to become popular for Minecraft, having been beaten by WorldGuard by just a couple months, Towny is now over 10 years old! Go check out some of the [features](https://github.com/TownyAdvanced/Towny/wiki#features) Towny has and see why it's still popular for yourself.
</p>

___

### Licensing
Towny is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) License ](http://creativecommons.org/licenses/by-nc-nd/3.0/)

We don't object to you making your own forks and builds but we do object to people being selfish, which is why we specify No Derivative Works.
If you want to modify the code to add some nice feature the least you can do is ask and submit a pull request to allow everyone to benefit from it.

___

### Importing Towny for API use
[![](https://jitpack.io/v/TownyAdvanced/Towny.svg)](https://jitpack.io/#TownyAdvanced/Towny)

Developers who wish to use the Towny API in their plugins may read [the following instructions on adding Towny via a maven pom.xml.](https://github.com/TownyAdvanced/Towny/wiki/TownyAPI#getting-started-with-towny-and-your-ide)

___

### Building Towny
If you would like to build from a specific branch yourself, you can do so with either [Apache Ant](https://ant.apache.org/) or [Apache Maven](http://maven.apache.org/), depending on the age of the branch.

For building, open your terminal / command prompt and navigate to the Towny Directory (either extracted, or cloned).

- **Maven**

    - Run `mvn clean package` to generate the plugin in the `target` directory, within the Towny folder. 


- **Ant** (_Deprecated_)

    - For older branches using the Ant build system, the main command to use would be: `ant clean jar`. This command will _exit_ the Towny directory, creating a lib folder alongside it. A Towny.jar file will be generated and placed within there.
    - _Note: As Ant is being deprecated, older branches may eventually not be able to be built against without modification of the `build.xml` file. We leave no guarantee that the file repo providing the dependencies will stay up._
