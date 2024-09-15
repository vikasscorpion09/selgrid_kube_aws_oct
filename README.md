## Introduction
This project is used for Test Infrastructure Workshop 

## New to Git ?

Install Git : https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

```sh
git clone https://github.com/Raneesh02/selgrid_kube_aws_oct.git
```

## Java Installation

```
https://www.oracle.com/in/java/technologies/downloads/#jdk22-windows
```


## Use Intellij or Eclipse ?

Directly import the project as a maven project

## Setup Project SDK
Intellij requires you to set/ choose project SDK , follow this link for the same

https://intellij-support.jetbrains.com/hc/en-us/community/posts/360010215699-Set-up-a-project-SDK

## Download Maven

Download Maven https://maven.apache.org/download.cgi

Open a command line/ Terminal in project folder
```sh
mvn compile
```

If above command is successful then we are good to go

## Execution

```sh
mvn clean test
```

all the tests of mentioned suite in pom.xml will run

