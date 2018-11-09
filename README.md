# Portable JAR simulation loader tool

JSLT is a tool for loading a large number of java simulations using JavaPortable.
It was developed because

- the school I work at does not install JVM on its computers
- the casual user and students do not know how to use JavaPortable.

## Instructions
Open the file called "application". use the buttons to choose a category, or click "All categories" to get a list of all available simulations. Use the search feature to further refine the search.

To add new java simulations to the collection, 

1. download the java simulation from phet.colorado.edu
2. copy the downloaded file to the "assets/simulation_files" folder, choosing an appropriate category
3. restart the application.

If you have any suggestion, or require the addition/amendment of a category, please contact me at the project's [Github page](https://github.com/iwalpola/phet-java-simulations-launcher/)

## New Features!

  - Category Classification
  - Search Feature


### Tech

JSLT uses a number of open source projects to work properly:

* [JavaPortable64](https://portableapps.com/apps/utilities/java_portable) - Portable Java Virtual Machine!
* [HTA](https://technet.microsoft.com/en-ca/scriptcenter/dd742317.aspx) - HTML Application
* [Javascript](https://www.javascript.com/) - for serch, sorting and populating tables
* [VBScript](https://en.wikipedia.org/wiki/VBScript) - great UI boilerplate for modern web apps
* [FileSystemObject](http://www.java2s.com/Tutorial/JavaScript/0600__MS-JScript/FileSystemObject.htm) - windows filesystem utility
* [WScript.Shell](https://stackoverflow.com/questions/15351508/using-a-wscript-shell-activex-to-execute-a-command-line) - Windows command prompt utility


### Installation

JSLT requires [JavaPortable](https://portableapps.com/apps/utilities/java_portable) to run.

The program is packaged with JavaPortable64. Please file an issue if you run linux or Windows 32 bit.

### Development

Want to contribute? Great!

File a pull request!

### Todos

 - Write an installer script that automticlly installs the correct version of JavaPortable.

License
----

MIT
