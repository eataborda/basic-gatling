[![gatling-test-run](https://github.com/eataborda/basic-gatling/actions/workflows/github-actions.yml/badge.svg)](https://github.com/eataborda/basic-gatling-gradle-scala/actions/workflows/github-actions.yml)
![Gradle](https://img.shields.io/badge/Gradle-7.3.3-blue)
[![Gradle Plugin Portal](https://img.shields.io/badge/io.gatling.gradle-3.7.3-blue)](https://plugins.gradle.org/plugin/io.gatling.gradle)

# Basic Gatling simulation
A basic gatling test with gradle and scala, based on the [gatling-gradle-plugin-demo-scala](https://github.com/gatling/gatling-gradle-plugin-demo-scala) repository

Contains:
- Basic build.gradle config
- Basic sample of a simulation with a friendly structure

## Use sample project
- Verify that you have `Git` installed
- Clone the repository and move inside that path:
```shellscript
$ git clone https://github.com/eataborda/basic-gatling.git
$ cd ./basic-gatling-gradle-scala
```

## Run simulations
There are two ways to run the simulations depending on the number you want to run, please go to the root of the repository and execute the following command:
- Run all simulations:
```
$ ./gradlew gatlingRun
```
- Run a specific simulation:
```
$ ./gradlew gatlingRun-com.github.eataborda.gatling.BasicSimulation
```
To run a simulation class it is necessary go to the path `src/gatling/scala` and identify:

- The package that contains the simulation class: `com.github.eataborda.gatling`

- The name of the simulation class: `BasicSimulation`