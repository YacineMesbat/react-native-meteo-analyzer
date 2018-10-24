# Meteo Analyzer

Educational project, which takes weather informations as input and output stats using charts and tables.

## Table Of Contents

- [Meteo Analyzer](#meteo-analyzer)
    - [Table Of Contents](#table-of-contents)
    - [Tasks](#tasks)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Start](#start)
- [Built with](#built-with)
- [Author](#author)
- [License](#license)

## Tasks

- [x] Init the project
- [x] Initial Commit
- [ ] Add dependencies to the project
- [ ] Handle files from the Download Folder
- [ ] Parse files to get weather informations
- [ ] Output stats from the files content
- [ ] Coolify the UI :bowtie:

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

Install Java

```bash
apt install openjdk-8-jre openjdk-8-jdk
```

Install node

```bash
apt install nodejs
```

Install React-native

```bash
npm install -g react-native-cli
```

## Start

Run your emulator, should be located in your **$HOME/Android/Sdk/emulator** folder:

```bash
> emu -avd Nexus_5X_API_28_x86

...
emulator: INFO: boot completed
```

Then, run the development server:

```bash
> react-native start

...
Looking for JS files in
   /Path/To/The/Project 

Loading dependency graph, done.
```

Link assets:

```bash
> react-native link

rnpm-install info Linking assets to ios project 
rnpm-install WARN ERRGROUP Group 'Resources' does not exist in your Xcode project. We have created it automatically for you.
rnpm-install info Linking assets to android project 
rnpm-install info Assets have been successfully linked to your project 
```

Finally, build and install the app:
```bash
> react-native run-android

...
BUILD SUCCESSFUL in 2s
```

# Built with 

* [React Native](https://github.com/facebook/react-native) - Build mobile apps with React

```bash
├── android
├── App.js
├── app.json
├── index.js
├── ios
├── LICENSE
├── node_modules
├── package.json
└── README.md
```

# Author

**Yacine Mesbat** - *Fullstack Work* - [GITHUB](https://github.com/YacineMesbat)
 
# License 

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details