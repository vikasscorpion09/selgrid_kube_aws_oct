## Introduction
This project is used for QA Infrastructure Workshop : https://www.thetesttribe.com/live-trainings/qa-infra/

## New to Git ?

Install Git : https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

```sh
git clone <your_repo_url>
```

You can clone using two ways : 

1. **HTTPS Setup:**
     - When cloning a repository via HTTPS, you'll need to provide your GitHub username and personal access token (PAT) instead of your password.
     - Create a [personal access token](https://github.com/settings/tokens) from your GitHub account and use it for HTTPS authentication.

2. **SSH Setup:**
     - Open Git Bash and generate an SSH key:
       ```bash
       ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
       ```
     - Start the SSH agent and add the SSH key:
       ```bash
       eval "$(ssh-agent -s)"
       ssh-add ~/.ssh/id_rsa
       ```
     - Copy the public key to your clipboard:
       ```bash
       clip < ~/.ssh/id_rsa.pub
       ```
     - Add the key to your GitHub account under **Settings** > **SSH and GPG keys** > **New SSH key**.

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

