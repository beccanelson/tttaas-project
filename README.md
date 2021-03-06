# Becca and Tom's Tic Tac Toe Server [![Build Status](https://travis-ci.org/beccanelson/tttaas-project.svg?branch=master)](https://travis-ci.org/beccanelson/tttaas-project)

This is the server that works with our [iOS application](https://github.com/beccanelson/tttaas-iOS).

## Dependencies:
+ [Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
+ [Maven](https://maven.apache.org/)
+ [Leiningen](http://leiningen.org/)
+ [Clojure tic tac toe](https://github.com/beccanelson/tttaas-clojure) (Included in setup script)
+ [Java server](https://github.com/beccanelson/tttaas-server) (Included in setup script)

## To setup this project:
Clone the repository

Inside the root folder:

`./setup`

\* This is a bash script that installs dependencies and sets up the Maven project.

## To run tests:
`mvn test`

## To start server:
`./server`

**Note:** `./setup` must have been run
