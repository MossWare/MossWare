<img width="120" height="120" align="left" style="float: left; margin: 0 10px 0 0;" alt="lantern client image" src="src/main/resources/assets/minecraft/liquidbounce%2B/big.png">

# Lantern Client
A random client lol

## Credits
LiquidBounce+ - Base \
[ViaForge](https://github.com/ViaVersion/ViaForge) - Version switcher

### Download
Right now you can't actually download Lantern without a github account, please create one and download it from the [Action](https://github.com/MokkowDev/Lantern/actions) tab.

### LiquidBounce's contact info
Website: https://liquidbounce.net \
Forum: https://forums.ccbluex.net \
Guilded: https://www.guilded.gg/CCBlueX \
YouTube: https://youtube.com/CCBlueX \
Twitter: https://twitter.com/CCBlueX 

## License
This project is subject to the [GNU General Public License v3.0](LICENSE). This does only apply for source code located directly in this clean repository. During the development and compilation process, additional source code may be used to which we have obtained no rights. Such code is not covered by the GPL license.

For those who are unfamiliar with the license, here is a summary of its main points. This is by no means legal advice nor legally binding.

You are allowed to
- use
- share
- modify

this project entirely or partially for free and even commercially. However, please consider the following:

- **You must disclose the source code of your modified work and the source code you took from this project. This means you are not allowed to use code from this project (even partially) in a closed-source (or even obfuscated) application.**
- **Your modified application must also be licensed under the GPL.** 

Do the above and share your source code with everyone; just like we do.

## Setting up a Workspace
Lantern is using Gradle, so make sure that it is installed properly. Instructions can be found on [Gradle's website](https://gradle.org/install/).
1. Clone the repository using `git clone https://github.com/MokkowDev/Lantern`. 
2. CD into the local repository folder.
4. Depending on which IDE you are using execute either of the following commands:
   ***Recommended: IntelliJ***
    - For IntelliJ: `gradlew setupDevWorkspace idea genIntellijRuns build`
    - For Eclipse: `gradlew setupDevWorkspace eclipse build`

    (you can add `-debug` right after `gradlew` if you want to enable debug logging.)
6. Open the folder as a Gradle project in your IDE.
7. Select the default run configuration.

## Additional libraries
### Mixins
Mixins can be used to modify classes at runtime before they are loaded. Lantern is using it to inject its code into the Minecraft client. This way, we do not have to ship Mojang's copyrighted code. If you want to learn more about it, check out its [Documentation](https://docs.spongepowered.org/5.1.0/en/plugin/internals/mixins.html).
