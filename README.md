# rocket-workspace

## Overview

This project agglutinates all Stratio Rocket projects for a easier usage when you are developing (you don't need to have
open several projects with the following complexity when you have to change from one to another).

It uses [git submodules](https://git-scm.com/docs/git-submodule) to make it.

These modules refer to the following Git projects:

* [rocket-core](https://github.com/stratio/rocket-core)
* [rocket-api](https://github.com/stratio/rocket-api)
* [rocket-driver](https://github.com/stratio/rocket-driver)
* [rocket-plugins](https://github.com/stratio/rocket-plugins)
* [rocket-ui](https://github.com/stratio/rocket-ui)

## Usage

* Clone this repository:

  ```bash
  $ git clone https://github.com/stratio/rocket-workspace
  ```
  
* The first time you need to update every submodule of the project:

  ```bash
  $ git submodule update --recursive --remote
  ```
  
* Finally you can open your ide pointing to rocket-workspace

**Note:** Take into account that every module has a different remote that is pointing to a real repository.